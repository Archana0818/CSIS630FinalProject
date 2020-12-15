# CSIS630FinalProject

I have created Specific Energy Calculator using AWS Services.

AWS services I used to create it :
s3 - for frontend
Lambda and API for backend

Below are the steps to create this project:

- Download the index.html file and upload that in S3 bucket of AWS. 
- change the settings of S3 bucket so that it can host static website.
-Download the file named lambda function.
-Create lambda function in AWS with basic function using python. The function I used is in the file named lambda function. 
-create REST API. Create post method and enable CORS. Link the API with the labda function created above. Deploy the API and then past the API URL endpoint in the index file and upload that again in s3 and delete the previous index.html file. 
