# Server
This folder contains the server side (backend) scripts for the sales prediction webapp. Before contributing to this project, make sure your environment has the installed pip packages shown in the requirement.txt file.

# Files and Folders

### Procfile:

Heroku apps include a Procfile that specifies the commands that are executed by the app on startup. Procfile can be usedd to declare a variety of process types, including: the app's web server, multiple types of worker processes and even a singleton process, such as a clock.

### App.py
This file contains the API for the web application. To run the file use the command ```python3 app.py```. This will start the server on 5000 port. The API can be tested in the Postman client by sending a POST API call. 

### Finalized Model:
This file contains the code for our prediction model. The regression model uses CatBosst to make predictions for sales. A major beneit of using catboost regression is that it can work on categorical features directly without having to label encode the categorical features.

The RMSE for the model is 1.5. The model can be improved further by using ensemble learning techniques.

### Requirements
This file consists of the necessary pip packages to be installed before contributing to the package. All the files can be installed into your environment using the following command:
```
sudo pip3 install -r requirements.txt
```
