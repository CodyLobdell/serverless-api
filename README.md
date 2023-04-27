# serverless-api
Lab 18


Notes
Creating a serverless API: Checklist

 IAM User role with access to Lambda and DynamoDB Full Access
 Dynamo DB Table Created
 Lambda function(s) that use Dynamoose to attach to the table
 Created with the correct IAM Role (Step 1)
 API Endpoints that all the appropriate functions for each action type
Creating a Dynamo DB Table at AWS
Open the DynamoDB Dashboard
Choose Create Table
Name your table
Choose a field name to use as primary key
Generally, "id", and you'll need to supply this when you add records
Working with Dynamo from Node
When writing code that connects to a Dynamo Database, you'll need to know your AWS credentials and install dynamoose as a dependency

https://dynamoosejs.com/getting_started/Introduction

Create a Schema with Dynamoose
This is just like Mongoose!