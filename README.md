# Fullstack Task Manager (MERN)
## Overview
The Cloud-Based Task Manager is a web application designed to streamline team task management. Built using the MERN stack (MongoDB, Express.js, React, and Node.js), this platform provides a user-friendly interface for efficient task assignment, tracking, and collaboration. The application caters to administrators and regular users, offering comprehensive features to enhance productivity and organization.

## Why/Problem?
In a dynamic work environment, effective task management is crucial for team success. Traditional methods of task tracking through spreadsheets or manual systems can be cumbersome and prone to errors. The Cloud-Based Task Manager aims to address these challenges by providing a centralized platform for task management, enabling seamless collaboration and improved workflow efficiency.

## Background:
With the rise of remote work and dispersed teams, there is a growing need for tools that facilitate effective communication and task coordination. The Cloud-Based Task Manager addresses this need by leveraging modern web technologies to create an intuitive and responsive task management solution. The MERN stack ensures scalability, while the integration of Redux Toolkit, Headless UI, and Tailwind CSS enhances user experience and performance.

# Admin Features:
1. User Management:
   1. Create admin accounts.
   2. Add and manage team members.
2. Task Assignment:
   1. Assign tasks to individual or multiple users.
   2. Update task details and status.
   3. Task Properties:

3. Label tasks as todo, in progress, or completed.
4. Assign priority levels (high, medium, normal, low).
5. Add and manage sub-tasks.
6. Asset Management:
   1. Upload task assets, such as images.
   2. User Account Control:

7. Disable or activate user accounts.
8. Permanently delete or trash tasks.
    
# User Features:
1. Task Interaction:
   1. Change task status (in progress or completed).
   2. View detailed task information.
2. Communication:
   1. Add comments or chat to task activities.
      
## General Features:
1. Authentication and Authorization:
   1. User login with secure authentication.
   2. Role-based access control.
      
2. Profile Management:
   1. Update user profiles.
      
3. Password Management:
   1. Change passwords securely.
      
4. Dashboard:
   1. Provide a summary of user activities.
   2. Filter tasks into todo, in progress, or completed.
      
# Technologies Used:
## Frontend:

1. React (Vite)
2. Redux Toolkit for State Management
3. Headless UI
4. Tailwind CSS
   
## Backend:

1. Node.js with Express.js
   
## Database:

1. MongoDB for efficient and scalable data storage.
   
The Cloud-Based Task Manager is an innovative solution that brings efficiency and organization to task management within teams. By harnessing the power of the MERN stack and modern frontend technologies, the platform provides a seamless experience for both administrators and users, fostering collaboration and productivity.

 

# SETUP INSTRUCTIONS
## Server Setup
Environment variables
First, create the environment variables file .env in the server folder. The .env file contains the following environment variables:

MONGODB_URI = your MongoDB URL
JWT_SECRET = any secret key - must be secured
PORT = 8800 or any port number
NODE_ENV = development
 

## Set Up MongoDB:
Setting up MongoDB involves a few steps:

1. Visit MongoDB Atlas Website

2. Go to the MongoDB Atlas website: https://www.mongodb.com/cloud/atlas.
   1. Create an Account
   2. Log in to your MongoDB Atlas account.
   3. Create a New Cluster
   4. Choose a Cloud Provider and Region
   5. Configure Cluster Settings
Create Cluster

Wait for Cluster to Deploy

Create Database User

Set Up IP Whitelist

Connect to Cluster

Configure Your Application

Test the Connection

Create a new database and configure the .env file with the MongoDB connection URL.

Steps to run server
Open the project in any editor of choice.
Navigate into the server directory cd server.
Run npm i or npm install to install the packages.
Run npm start to start the server.
If configured correctly, you should see a message indicating that the server is running successfully and Database Connected.

 

Client Side Setup
Environment variables
First, create the environment variables file .env in the client folder. The .env file contains the following environment variables:

VITE_APP_BASE_URL = http://localhost:8800 #Note: Change the port 8800 to your port number.
VITE_APP_FIREBASE_API_KEY = Firebase api key
Steps to run client
Navigate into the client directory cd client.
Run npm i or npm install to install the packages.
Run npm start to run the app on http://localhost:3000.
Open http://localhost:3000 to view it in your browser.
 
