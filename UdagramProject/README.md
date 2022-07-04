### Project Title - Deploy a high-availability web app using CloudFormation
This project deploys a high availability web app downloaded from a S3 Bucket Using cloudformation
Creating IAM Roles and Policies
Associating autoscaling group with a loadbalancer
Deploys jump boxes to be able to troubleshoot the private server instances in the private subnets
The Diagram app is automatically downloaded from the S3 bucket and the apache server starts upon the instance creation
Creating a Key bucket to store the keys for the jump box, and instances then removing them from the code