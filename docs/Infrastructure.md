# Infrastructure

### Cloud infrastructure for Udagram deployment on *AWS*

## Infrastructure Diagram
![Diagram](../diagrams/Infrastructure.png)

## Used services // refer to sections
- RDS for backend database 
- Elastic Beanstalk for backend server
- S3 bucket for frontend hosting
- S3 bucket for media storage

## RDS
Service for managing relational databases.

![rds image](../diagrams/rds.PNG)
Created instance.

## S3
Service for cloud scalable storage.

![s3 image](../diagrams//s3.PNG)
![s3 image](../diagrams//s3.1.PNG)
Created instance.

![s3 image](../diagrams//s3.app.PNG)
Working Frontend deployed [here](http://udagram-app-bucket.s3-website-us-east-1.amazonaws.com)

## EB
Service for running and mangain web applications.

![eb instance](../diagrams/eb.PNG)
![eb instance](../diagrams/eb2.PNG)
Created instance.

![eb instance](../diagrams/eb-env.PNG)
Elastic beanstalk created environment variables.

![eb instance](../diagrams/eb-endpoint.PNG)
![eb instance](../diagrams/eb-endpoint2.PNG)
Working Backend deployed [here](http://udagram-api-dev.eba-2tikbxrx.us-east-1.elasticbeanstalk.com/)

## Hosted Udagram Application deployed [here](http://udagram-app-bucket.s3-website-us-east-1.amazonaws.com) 