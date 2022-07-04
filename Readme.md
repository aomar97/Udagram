### Project Title - Deploy a high-availability web app using CloudFormation

This project deploys a high availability web app downloaded from a S3 Bucket Using cloudformation
Creating IAM Roles and Policies
Associating autoscaling group with a loadbalancer
Deploys jump boxes to be able to troubleshoot the private server instances in the private subnets
The Diagram app is automatically downloaded from the S3 bucket and the apache server starts upon the instance creation
Creating a Key bucket to store the keys for the jump box, and instances then removing them from the code

![Project Diagram](https://user-images.githubusercontent.com/108636104/177224523-f4b2c9f3-2166-449d-b8f7-8e74d196c0ef.png)
