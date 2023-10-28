# TeamPlan Project
This mobile app organizes tasks and deadlines in teams.
This project was made as part of my Computer Science Bachelor's Degree.

## Utilities
The project uses ionic 6.18.1 for frontend with the Router, Storage, and HttpClient modules installed.
The project uses PHP 7.3.21 for the backend connected to a MySQL database using mysqli(). The backend was run and tested on a WAMP localhost server.

## Navigation
The app folder contains all the pages used in the application: add-task, home, login, signup, and task-info. Inside the app folder, there is a components folder that contains any components used throughout the project: card-component and popover. The folder also contains the services that are used to communicate with the backend. The icons used in the application are placed in the assets folder.

## Running the application
For the frontend, open the command prompt and navigate to the project folder that contains the “src” folder. Run the command “ionic lab” in order to start the application on IOS and Android devices. The frontend was designed and tested in the ionic lab and might not look the same on a web browser. When the application starts, the login page will be displayed for signing in. To create a new account, press on the sign-up button and enter your credentials. Afterwards, you will be able to sign in and test the functionalities of the application

For the backend, the APIs must be placed in a folder accessible to the localhost. The application runs on http://localhost:80/MobileProjectAPIs/. A database dump is provided with the SQL code for the table definitions. The “connection.php” file in the APIs contains the information about opening up the database in WAMP such as server, username, password, and database name. 

## Pages

### Main Page: Listing of all the projects, tasks, and assigned team members
![Image not found](/WebsiteScreenshots/Mainpage.jpg?raw=true "Main Page")
### Add Task: Add task information to a specific project and assign to project member
![Image not found](/WebsiteScreenshots/AddTask.jpg?raw=true "Main Page")
### Task Objectives: View task information and objectives
![Image not found](/WebsiteScreenshots/TaskObjectives.jpg?raw=true "Main Page")
### Task Status: Check if task is submitted, and download submitted file
![Image not found](/WebsiteScreenshots/TaskStatus.jpg?raw=true "Main Page")
### Sign in: Sign in to existing account
![Image not found](/WebsiteScreenshots/Signin.jpg?raw=true "Main Page")
### Sign in: Register a new account
![Image not found](/WebsiteScreenshots/SignUp.jpg?raw=true "Main Page")
