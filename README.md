# Vulpex WebApp

Vulpex is a web application deployed over Heroku that uses Machine Learning model to predict sales of Video Games. Python Flask is used to create the backend APIs. Netlify is used to host the web app online. CatBoost Regression is used for making predictions.

The project was started in 2020 and is distributed under the MIT license and is maintained by [Ashwin Raj](https://github.com/ashwinraj-in)

# Installation and Development
### Dependencies
- Python (>= 3.7.9)
- Flask (>=1.1.2)
- Node.js (>=12.18.3) 

### Files and Folders
Folders that are necessary for the functioning of web app are as mentioned below:
- [Server](https://github.com/ashwinraj-in/Vulpex-WebApp/tree/master/Server):
  This folder consists the backend files of the web app. This stores and manipulates the data.

- [Frontend](https://github.com/ashwinraj-in/Vulpex-WebApp/tree/master/Frontend):
  It consists of file used to develop graphical interface through the use of HTML, CSS and Javascript.
 
- [Data](https://github.com/ashwinraj-in/Vulpex-WebApp/tree/master/Data): It contains the data used for building the machine learning model for target prediction.

## Creating and Deploying Backend API
Python Flask is used to deploy the backend APIs. The application uses a POST API, and it is recommended to install Postman tool. The tool is used to send a POST request to the server. This is the backend for the application. Heroku is used as the API hosting platform for the application. Sign up on Heroku website and install Heroku CLI to work on it.

## Creating a client-side app using react and bootstrap
Before proceeding further install Node.js and yarn package manager. First, we need to import relevant bootstrap files in the index.html file found in the public folder within our app. The final UI is a collection dropdown item. We are making use of Axios npm module to make a POST API call to backend Heroku server.

## Deploying the Client-Side app to Netlify 
Netlify allows to instantly build and deploy static websites from git. It has a quite easy process when deploying applications made using create-react-app module. Deployment to netlify is straight forward and easy process and can be achieved by going through their official documents here: [Netlify Deploy](https://www.netlify.com/blog/2016/09/29/a-step-by-step-guide-deploying-on-netlify/https://www.netlify.com/blog/2016/09/29/a-step-by-step-guide-deploying-on-netlify/)

# Contribution

New contributors of all experience levels are welcomed to contribute to this project. Some basic information about the project has been included in this README. For major changes, it is recommended that you open an issue first to discuss what you would like to change.

### Clone the repository
To contribute to this project you have to clone the repository and send a pull request.
```
git clone https://github.com/ashwinraj-in/Vulpex-WebApp
```
### Installing Required Libraries
The web application requires some requirements that can be installed using the following code.
```
sudo pip3 install -r requirements.txt
```

# License and Project Status
The software and other resources are distributed under MIT license. The project is completed and all the files are available in this repository. The UI is basic and the design can be improved using CSS for improving the visuals. 
