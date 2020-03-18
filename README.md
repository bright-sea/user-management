1. Login to AWS account

2. Open CloudFormation Service, create a new stack based on template usermanagement.yaml
   Give a stack name, for example: UserMngt

3. After stack complete successfully, open Lambda service, find Lambda function with name like:
   
   UserMngt-IngestDataLambda-XXXXXXXXXXXX    

   Click to open this Lambda function, click "test" button, 
   create a test event if a dialog popup (just give any test event name), then run "test". 
   This lambda function will insert some sample data into UserTable and AuditTable   

   