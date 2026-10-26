# AWS-Projects
Project-01: Automated EC2-to-S3 Backup and Restore Using AWS
<img width="955" height="547" alt="image" src="https://github.com/user-attachments/assets/ca6dd01e-5577-4684-b1bf-e224b88da0e5" />


The objective of this project was to implement a simple, secure backup and recovery solution using Amazon EC2 and Amazon S3.
First, I launched an EC2 instance running Amazon Linux. I created an S3 bucket to store backup files and configured an IAM role with the required S3 permissions. I attached the role to the EC2 instance so that it could access S3 without storing access keys on the server.
Next, I created a sample file on EC2 and used the AWS CLI to upload it to S3. I verified the backup by checking the S3 bucket. I then simulated data loss by deleting the local file and restored it from S3.
Finally, I configured a scheduled script to automate the backup process.
This project helped me understand EC2, S3, IAM roles and policies, AWS CLI commands, and basic backup and recovery operations.

