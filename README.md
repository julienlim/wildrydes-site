# wildrydes-site
This set of artifacts were created as part of the [AWS Serverless Workshop](https://github.com/aws-samples/aws-serverless-workshops/).  Click on the [AWS Serverless Workshop](https://github.com/aws-samples/aws-serverless-workshops/) to try it yourself!

## Troubleshooting Tips ##

* If you don’t specify in #5 to check “Enable SRP (secure remote password) protocol based authentication (ALLOW_USER_SRP_AUTH)” in https://github.com/aws-samples/aws-serverless-workshops/tree/master/WebApplication/2_UserManagement, you get the following msg: "InvalidParameterException: USER_SRP_AUTH is not enabled for the client."

* Refers to https://github.com/aws-samples/aws-serverless-workshops/tree/master/WebApplication/3_ServerlessBackend.  Change https://github.com/aws-samples/aws-serverless-workshops/blob/master/WebApplication/3_ServerlessBackend/requestUnicorn.js (RideId entries to RideID, as how it’s called in the Dynamo table)
