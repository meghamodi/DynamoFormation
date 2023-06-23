# DynamoFormation
This project contains CloudFormation template that facilitate the automated creation and configuration of DynamoDB tables in AWS.

The steps required to create DynamoDB tables:- 
1. Go to AWS console -> open CloudFormation -> 


**- Create Stack**

    click on create stack(with new resources) -> Template is ready-> upload the template file(JSON or yaml).


**- Specify Stack details**

  Enter stack name(could be anything).In the parameters, it shows the primary key(InventoryId) and type of it (String)


**- Configure stack options**

  No changes


**- Review the changes** and click Submit for creating the stack. It might take few seconds to create the stack.



After the completion, go to **DynamoDB in AWS console** and you could see the table being created using **CloudFormation(Infrastructure as Code)**
  
