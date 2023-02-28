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


### AWS Step Function
AWS Step Functions is a serverless workflow service that lets you coordinate distributed applications and microservices using visual workflows. With Step Functions, you can define workflows that integrate with AWS services, including Lambda functions, ECS tasks, SNS topics, and more.

Step Functions allows you to build applications that automatically respond to state changes, retry operations, and handle errors. You can also use Step Functions to create complex workflows with conditional branching, parallel processing, and error handling.

The core concept of Step Functions is the state machine, which defines the workflow using a JSON or YAML document. The state machine includes a series of states, each of which represents a step in the workflow. Each state can include AWS service integrations, function invocations, and branching logic.

Overall, AWS Step Functions simplifies the process of building and managing complex workflows, making it an ideal choice for serverless applications.