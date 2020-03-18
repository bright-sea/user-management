1. Login to AWS account

2. Open CloudFormation Service, create a new stack based on template usermanagement.yaml
   Give a stack name, for example: UserManagement

3. After stack creation successfully complete, open API Gateway service, find a new API like:
    
   UserManagement-UserMngtApiGateway 

   Open this APIGateway, click left "Stages" menu, click "prod" stage
   get Invoke URL like : 
   
   https://uldoe6jrel.execute-api.us-east-1.amazonaws.com/prod

4. Open any browser, copy about link and add "/LoadData" path, like:

   https://uldoe6jrel.execute-api.us-east-1.amazonaws.com/prod/LoadData

   Clik above link,  
   You will see a message on the screen : Load Data into Tables Successfully! 
   This insert some sample data into UserTable and AuditTable.    

5. Open postman collection: user-management and test all APIs.   

   