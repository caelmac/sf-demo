# Readme for Serverless AWS Step Function Demo Project

This is a demo project for a serverless AWS Step Function. It includes several serverless functions that can be used and deployed using the code in this repository.

### Requirements
To deploy and run this project, you will need:

### An AWS account
The AWS CLI installed on your machine
Node.js and NPM installed on your machine
Installation
To install the necessary dependencies for this project, run the following command:

npm install
### Deployment
To deploy the project, you can use the Serverless Framework with the following command:

sls deploy
This will create the necessary resources in your AWS account and deploy the functions.

Usage
Once the project is deployed, you can trigger the AWS Step Function using the AWS console, the AWS CLI, or an SDK.

### Serverless Functions
The following functions are included in this project:

checkInventory
calculateTotal
redeemPoints
billCustomer
restoreRedeemPoints
restoreQuantity
sqsWorker