
<p align="center"><img width=55% src="https://github.com/Santosh3007/todo-app/blob/main/assets/Logo1.png" /></p>
<h1 align="center">Get It Done</h1>
<p align="center"> <a href="http://todo-frontend-env.eba-whhqv9zi.ap-southeast-1.elasticbeanstalk.com">Try it out!</a></p>

## Overview
A task manager designed to help you manage and keep track of your everyday tasks and goals to make sure you **get it done** on time. Never forget anything ever again and all you have to do is use the app!

<br/>
<p align="center"><img width=45% src="https://github.com/Santosh3007/todo-app/blob/main/assets/LoginPage.png" />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img width=45% src="https://github.com/Santosh3007/todo-app/blob/main/assets/HomePage.png" /></p>
<p align="center"><img width=45% src="https://github.com/Santosh3007/todo-app/blob/main/assets/TaskView.png" />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img width=45% src="https://github.com/Santosh3007/todo-app/blob/main/assets/Account.png" /></p>
<br/>

Login using the following credentials for a test account
```
Email: test@gmail.com
Password: testtest
```

## Setup to run locally

Prerequisites

Make sure you have docker and docker-compose installed on your machine before carrying on.


Clone the current git repository using the following command

```git
git clone git@github.com:Santosh3007/todo-app.git
```

The above command will not clone the submodule folders, so if you want to clone the source code for the frontend and backend as well, please use the following command
```git
git clone --recursive git@github.com:Santosh3007/todo-app.git
```

Once you have installed docker installed and running, navigate into the todo-app directory and run the following command to start the application
```
docker-compose up
```

Once the docker container is running, open http://localhost/ on your browser to view the application.

This repository consists of two submodules:

1. `todo-app-frontend` contains the code for the frontend, hosted at [http://todo-frontend-env.eba-whhqv9zi.ap-southeast-1.elasticbeanstalk.com/home](http://todo-frontend-env.eba-whhqv9zi.ap-southeast-1.elasticbeanstalk.com)
2. `todo-app-api` contains the code for the backend, hosted at [http://todo-api-env.eba-xaznfkbj.ap-southeast-1.elasticbeanstalk.com/](http://todo-api-env.eba-xaznfkbj.ap-southeast-1.elasticbeanstalk.com/)


