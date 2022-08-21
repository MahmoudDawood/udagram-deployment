# Application Infrastructure

### **Cloud infrastructure for Udagram deployment on *AWS***

## Infrastructure Diagram
![Diagram](../diagrams/Infrastructure.png)


## Used services
- [RDS](#rds) for backend database 
- [Elastic Beanstalk](#eb) for backend server
- [S3 bucket](#s3) for frontend hosting
- [S3 bucket](#s3) for media storage

---

## RDS
Service for managing relational databases.

![rds image](../diagrams/rds.PNG)
Created instance.

---

## S3
Service for cloud scalable storage.

![s3 image](../diagrams//s3.PNG)
![s3 image](../diagrams//s3.1.PNG)
Created instance.
<br>

![s3 image](../diagrams//s3.app.PNG)
Working Frontend deployed [here](http://udagram-app-bucket.s3-website-us-east-1.amazonaws.com)

---

## EB
Service for running and mangain web applications.

![eb instance](../diagrams/eb.PNG)
![eb instance](../diagrams/eb2.PNG)
Created instance.
<br>

![eb instance](../diagrams/eb-env.PNG)
Elastic beanstalk created environment variables.
<br>

![eb instance](../diagrams/eb-endpoint.PNG)
![eb instance](../diagrams/eb-endpoint2.PNG)
Working Backend deployed [here](http://udagram-api-dev.eba-2tikbxrx.us-east-1.elasticbeanstalk.com/)
<br>

## Hosted Udagram Application deployed [here](http://udagram-app-bucket.s3-website-us-east-1.amazonaws.com) 