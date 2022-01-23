#USER MANAGMENT SYSTEM

NodeJS + MongoDB API for User Management, Authentication and Registration

For documentation and instructions check out #readme


Running the NodeJS + MongoDB API Locally
Install NodeJS and NPM from  https://nodejs.org/en/download/.
Install MongoDB Community Server from  https://www.mongodb.com/download-center.
Run MongoDB, instructions are available on the install page for each OS at https://docs.mongodb.com/manual/administration/install-community/
Download or clone the project source code from https://github.com/akashranjanofficial/user-management-system
Install all required npm packages by running npm install from the command line in the project root folder (where the package.json is located).
Start the api by running npm start from the command line in the project root folder, you should see the message Server listening on port 4000. Follow the instructions below to test with Postman or hook up with one of the example single page applications available (React, Angular or Vue).


Running a React client application with the NodeJS API
For full details about the example React application see the post React Hooks + Redux - User Registration and Login Tutorial & Example. But to get up and running quickly just follow the below steps.

Download or clone the React tutorial code from 
Install all required npm packages by running npm install from the command line in the project root folder (where the package.json is located).
Remove or comment out the 2 lines below the comment // setup fake backend located in the /src/index.jsx file.
Start the application by running npm start from the command line in the project root folder, this will launch a browser displaying the application and it should be hooked up with the NodeJS + MongoDB API that you already have running.
