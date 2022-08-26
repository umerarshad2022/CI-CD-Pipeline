### CI-CD-Pipeline
- CI/CD Pipeline for Flask ML Deploy
- Generate SSH keys and connect your Azure environment with your Github account.
- ssh-keygen -t rsa
- Clone the repo using Azure cloud, and git commands
![Make_all](https://user-images.githubusercontent.com/111645872/186910526-f8fe2cba-57cb-4314-a7d9-b3282d7b25bd.JPG)
- Make a new project in Microsoft Azure, define organization and connect to Github repo.
- Create environment variable and activate it using python3.
- Run python app and test the make_prediction.sh script if it works
![python_app_py](https://user-images.githubusercontent.com/111645872/186911107-04e52a6d-cf16-4a4c-98c5-de8b69cf37eb.JPG)
![prediction_result](https://user-images.githubusercontent.com/111645872/186911172-0b1063a5-7196-42e4-b777-fe00b1c89e84.png)
- Run the webapp with your app name (FlaskML2022) and check its log trails

![Web_app_stats_Azure](https://user-images.githubusercontent.com/111645872/186911601-b7f068e5-3f48-4741-aa58-f5b1b9f7a062.JPG)

![Log_tail1](https://user-images.githubusercontent.com/111645872/186911757-a0e18b90-f93f-4b78-b0f1-1bae23400373.png)

![Log_tail2png](https://user-images.githubusercontent.com/111645872/186911793-ac2da23e-ea25-4c82-87c0-d2fcfab5cb2d.png)

- Verify the respective pipelines in Azure pipelines and check build and deployment jobs

![Final_build_1](https://user-images.githubusercontent.com/111645872/186912195-1e7dc479-cfad-43a9-9259-9551813f5298.JPG)

![Final_build_2](https://user-images.githubusercontent.com/111645872/186912435-3e3e3cf4-da5a-45f3-a10d-dc288dcf806e.JPG)

[](https://i.imgur.com/zkXdyXA.png)

- In make_predict_azure_app.sh, change post X to the value of your own webapp that was created earlier.

- Verify the make_predict_azure_app.sh again with your app URL

![flashML2022_Azureapp_URL_opening](https://user-images.githubusercontent.com/111645872/186913006-71ea48fc-5755-4852-9269-bafa5d97aab0.png)






