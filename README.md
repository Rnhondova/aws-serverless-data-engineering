# AWS Serverless Data Engineering
Serverless data engineering using aws lamda, dynamoDB and SQS

This is for project 4 of the Cloud Computing class at Duke University by Noah Gift.

## Diagram

The diagram for the project is shown below:

![Overview](https://camo.githubusercontent.com/bb29cd924f9eb66730bbf7b0ed069a6ae03d2f1a/68747470733a2f2f757365722d696d616765732e67697468756275736572636f6e74656e742e636f6d2f35383739322f35353335343438332d62616537616638302d353437612d313165392d393930392d6135363231323531303635622e706e67)


## AWS Lambda Build and Deploy

This project was built in AWS Cloud9 where sam functionality is pre-built.

1.  `sam init`
2.  `sam build`
3.  `sam deploy --guided`

## Deploy and Testing (Key Concepts)

Test two ways:  

`sam local invoke`
`sam local start-api`

Then curl `curl http://127.0.0.1:3000/hello`

* API Gateway
* CloudWatch Logs
* IAM Security settings

## Other AWS elements required

Set up the following AWS services:

* DynamoDB
* Simple Queue Service(SQS)

Also remeber to set up the an IAM role that allows a lamda function admin access.


## Other Videos 

* Learn to write an AWS Lambda Function in Python in Five Minutes:

[![Learn to write an AWS Lambda Function in Python in Five Minutes](https://img.youtube.com/vi/AlRUeNFuObk/0.jpg)](https://youtu.be/AlRUeNFuObk)


### Credit
These projects [here](https://github.com/noahgift/awslambda) and this [one](https://github.com/Klalena/AWS-Serverless-Data-Engineering-Pipeline).
