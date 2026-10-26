# AWS-Projects

Project-01: Automated EC2-to-S3 Backup and Restore Using AWS

<img width="955" height="547" alt="image" src="https://github.com/user-attachments/assets/ca6dd01e-5577-4684-b1bf-e224b88da0e5" />




<img width="15" height="23" alt="image" src="https://github.com/user-attachments/assets/508a4203-b4c5-41ee-b807-9be06331d326" /> Step - 01: EC2 — Compute 
Runs the application and creates or processes data


<img width="17" height="16" alt="image" src="https://github.com/user-attachments/assets/47c1e6c8-f2f6-4d1c-bc29-01c28c97df42" /> Step -02: S3 — Storage
Stores copies of files independently of the EC2 instance


<img width="11" height="16" alt="image" src="https://github.com/user-attachments/assets/54bbca33-2d64-4f47-b13c-12daed6d7c0d" /> Step - 03: IAM — Access control
Authorizes the instance to upload and retrieve files securely



* The objective of this project was to implement a simple, secure backup and recovery solution using Amazon EC2 and Amazon S3.
* First, I launched an EC2 instance running Amazon Linux. I created an S3 bucket to store backup files and configured an IAM role with the required S3 permissions. I attached the role to the EC2 instance so that it could access S3 without storing access keys on the server.
* Next, I created a sample file on EC2 and used the AWS CLI to upload it to S3. I verified the backup by checking the S3 bucket. I then simulated data loss by deleting the local file and restored it from S3.
* Finally, I configured a scheduled script to automate the backup process.
* This project helped me understand EC2, S3, IAM roles and policies, AWS CLI commands, and basic backup and recovery operations.

  

