Log Service Project   
---

                     (server photos attached above)

How to Launch;
                                       
Prerequisites
----
AWS Account: Make sure you have an AWS account.

AWS CLI: Install the AWS Command Line Interface.

AWS SAM CLI: Install the AWS Serverless Application Model CLI.

Node.js/Python: Depending on your function implementation.


Setup
---
Clone the Repository:

git clone https://github.com/Talhah10/Log-Service.git

'cd log-service'


Configure AWS CLI: 
-----
Run the following command and enter your AWS Access Key, Secret Access Key, and desired region:

'aws configure'

Deploy the Service: Use the SAM CLI to deploy your service:
---
'sam deploy --guided'

Follow the prompts to set up your stack name and configurations.


To run the API locally, use:
--
'sam local start-api'

You can now test your API endpoints using a tool like Postman or curl.

Accessing the API

After a successful deployment, you’ll get an endpoint URL. Use this to make API requests to your log service.


Cleaning Up
--

To delete the deployed resources:

'aws cloudformation delete-stack' --stack-name my-log-service-stack


