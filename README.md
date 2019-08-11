# Introduction  
What project you will deploy and project GitHub URL (your implementation is preferred)  
Describe your project at a high level (microserver, psql, java)  
  
# Docker Architecture Diagram  
- trading_app docker diagram including:  
![Docker_arch](https://user-images.githubusercontent.com/51926543/62839892-773e5700-bc5f-11e9-9830-577b6c7328d9.png)

  
- Two docker files  
  - trading-app  
   - talk about the process (e.g. compile and package jar and run the app)  
  - jrvs-psql  
   - talk about how to create tables (e.g. schema.sql)  
  
# Cloud Architecture Diagram  
- trading app diagram  
  - use [draw.io](http://draw.io/) and aws icons (it's in the [draw.io](http://draw.io/) library)  
  - include ec2, alb, auto scaling, target group, rds  
  - security groups  
  - label all important ports(e.g. ALB HTTP, ec2 tpc:5000, RDS tcp:5432)  
    
# AWS EB and Jenkins CI/CD Pipeline Diagram  
- Please refer to Jenkins guide architecture diagram.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTQzNjUxMjc3LC0xMDgxOTYzMTY5XX0=
-->