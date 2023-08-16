# Creating and Testing a Go AWS Lambda Function

A great hands on learning exercise I did to get some experience building and deploying Go Lambda functions to AWS. See cmds.txt for greater detail on the CLI commands used throughout this exercise.

## Steps
* Create the Lambda function in Go
* Create the necessary IAM role granting Lambda execution permission
* Attach the IAM role your current account
* Build the main Go file
* Zip the main file
* Create the Lambda function in your AWS account using the CLI
* Trigger the Lambda function by passing in JSON parameters
* If successful, Lambda function should trigger a 200 Handled message and the creation of a output.txt file
* Clean up the environment

## Technologies
* AWS CLI
* AWS Lambda
* Go
* Windows WSL
* Windows CMD