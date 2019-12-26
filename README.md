# wildrydes-site
This set of artifacts were created as part of the [AWS Serverless Workshop](https://github.com/aws-samples/aws-serverless-workshops/).  Click on the [AWS Serverless Workshop](https://github.com/aws-samples/aws-serverless-workshops/) to try it yourself!

## Overview ##
The workshop solution uses the following AWS services:
* AWS Amplify - simplify application lifecycle, including builds and deploys the web application by following a continuous integration and delivery model
* Amazon Cognito - lets you add user sign-up, sign-in, and access control to your web and mobile apps quickly and easily.  In this solution, it's used to manage users, federate identities, and manage user pools.
* AWS Lambda
* Amazon API Gateway
* Amazon S3 - object storage for hosting static web site content (HTML, CSS, JavaScript, images and other files)
* Amazon DynamoDB

## Troubleshooting Tips ##

* If you don’t specify in #5 to check “Enable SRP (secure remote password) protocol based authentication (ALLOW_USER_SRP_AUTH)” in https://github.com/aws-samples/aws-serverless-workshops/tree/master/WebApplication/2_UserManagement, you get the following msg: "InvalidParameterException: USER_SRP_AUTH is not enabled for the client."

* Refers to https://github.com/aws-samples/aws-serverless-workshops/tree/master/WebApplication/3_ServerlessBackend.  Change https://github.com/aws-samples/aws-serverless-workshops/blob/master/WebApplication/3_ServerlessBackend/requestUnicorn.js (RideId entries to RideID, as how it’s called in the Dynamo table)
