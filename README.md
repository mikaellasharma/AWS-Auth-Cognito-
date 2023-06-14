# AWS-Auth-Cognito-

## Masters Final Project 464 ##

The starter ReactJS UI you have is for creating a serverless authentication app in React using AWS Amplify and Cognito. 

This app provides the following functionality:

Sign-in: Users can sign in to the app using their credentials.
Sign-up: New users can register and create an account.
Forgot password: Users can initiate the password recovery process if they forget their password.
Email verification: During the sign-up process, users are verified through email to ensure their identity.

This app serves as a basic foundation for implementing authentication features in a React application using AWS Amplify and Cognito.

The project was bootstrapped with Create React App.

[ npm start ]
To run the app in development mode, use the command npm start. It will start the app on http://localhost:3000 in your browser. Edits to the code will trigger a reload, and lint errors will be shown in the console.

**npm test**
The command npm test launches the test runner in interactive watch mode for running tests.

**npm run eject**
The command npm run eject is a one-way operation that gives you full control over the build tool and configuration choices. Use with caution as there's no way to revert back after ejecting.

**npm run build**
The command npm run build builds the app for production, optimizing it for performance and creating the necessary files in the build folder.

**AWS Identity Tokens**
In AWS Cognito, the id_token contains sensitive user data such as name, age, and email address. It's meant for your application to process and should not be sent elsewhere.
The access_token is used to authorize access to external services, including other AWS services, over HTTP. It does not contain personal details and provides service access authorization. When using Postman, you need to pass the ID token to get data.

**Postman Link**
The provided link is a workshop tutorial for user-based embedding, which might provide additional insights and instructions.
https://catalog.us-east-1.prod.workshops.aws/workshops/cd8ebba2-2ef8-431a-8f72-ca7f6761713d/en-US/user-based-embedding/2-embedding-workflow


