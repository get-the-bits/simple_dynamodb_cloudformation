AWS CloudFormation Template describing a DynamoDB Table
===
----

Use
---
```bash
$ aws cloudformation create-stack --stack-name simpleDynamoTable --template-body file://<ABSOLUTE_PATH_TO_TEMPLATE> --parameters ParameterKey=TableName,ParameterValue=user-table
```
