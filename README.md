# Cloud-Storage-creation-S3-and-Launching-an-EC2-Instance-in-AWS
Ex.2 Cloud storage creation (S3) and launching an (Ec2) instance in AWS
Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS. 
Procedure
a)	Steps to Create a first S3 Bucket:
Step 1: Sign in to the AWS Management Console
Go to https://console.aws.amazon.com/s3.
Step 2: Open the S3 Service
In the console, type S3 in the search bar and select S3 to open the service dashboard.
Step 3: Create Bucket
Click the Create bucket button.
Step 4: Configure Bucket Settings
•	Bucket name: Choose a globally unique name.
•	AWS Region: Select the region where you want to store your data.
Step 5: Object Ownership
Choose between:
	ACLs disabled (recommended) – Bucket owner has full control.
	ACLs enabled – Control access via access control lists.
Step 6: Block Public Access Settings
By default, all public access is blocked. Leave it as-is unless you need public access.
Step 7: Bucket Versioning (optional)
Choose whether to enable versioning for objects in the bucket.
Step 8: Encryption (optional)
Select encryption options (SSE-S3, SSE-KMS, or none).
Step 9: Advanced Settings (optional)
Add tags, configure logging, etc.
Step 10: Create the Bucket
Click Create bucket at the bottom of the page.
b)	i. Steps to launch an EC2 Instance
1.	Go to the EC2 Dashboard in AWS Console.
2.	Click on “Launch Instance”.
3.	Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).
4.	Select an instance type (e.g., t2.micro for Free Tier).

5.	Create or choose a key pair for SSH access.
6.	Configure network settings (use default VPC/subnet).
7.	Configure storage (default root volume is fine).
8.	Review the settings and click “Launch Instance”.
9.	Wait for the instance to enter the running state.

c)	Step 3: Connect to Your Instance
•	Linux: Use SSH command with your .pem key.
•	Windows: Use RDP with decrypted admin password.

d)	Steps to Clean Up (Terminate the Instance)
1.	Go to EC2 Instances.
2.	Select your instance → Instance State → Terminate.


Snap Shots:
 
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/de692483-f13a-4128-aa24-24f814264f71" />

<img width="1920" height="1020" alt="Screenshot 2026-11-10 181655" src="https://github.com/user-attachments/assets/e9585705-6f96-426b-a14e-3001aec3f93c" />

<img width="1920" height="1020" alt="Screenshot 2026-11-10 181816" src="https://github.com/user-attachments/assets/3ed44aaa-cecc-4f5c-877e-5a618eaaf849" />

<img width="1920" height="1020" alt="Screenshot 2026-11-10 181859" src="https://github.com/user-attachments/assets/6cc05ee1-5705-4f56-a8ff-def621245b56" />

<img width="1920" height="1020" alt="Screenshot 2026-11-10 181929" src="https://github.com/user-attachments/assets/b511c6f9-8691-4a81-9b78-b52dd7e9d578" />

<img width="1920" height="1020" alt="Screenshot 2026-11-10 181959" src="https://github.com/user-attachments/assets/8a843f6d-8d33-46dc-9b1d-40268813e002" />

<img width="1920" height="1020" alt="Screenshot 2026-11-10 182739" src="https://github.com/user-attachments/assets/752c41a4-0fe5-403f-86b2-75fcaecbf4a2" />

<img width="1920" height="1020" alt="Screenshot 2026-11-10 183007" src="https://github.com/user-attachments/assets/01c7d0f0-2528-464d-bff4-4228d6e99ec7" />

<img width="1920" height="1020" alt="Screenshot 2026-11-10 183029" src="https://github.com/user-attachments/assets/b14906a5-b2b3-4412-a563-d22fb2a91223" />


<img width="1920" height="1020" alt="Screenshot 2026-11-10 183338" src="https://github.com/user-attachments/assets/667462ee-8e35-4350-810a-537e5515dbc6" />

<img width="1920" height="1020" alt="Screenshot 2026-11-10 183623" src="https://github.com/user-attachments/assets/3d556181-79db-4574-9bbc-a2a8e925196e" />

<img width="1920" height="1020" alt="Screenshot 2026-11-10 183632" src="https://github.com/user-attachments/assets/63578033-44bc-44a2-a192-5feb2c85bed6" />

<img width="1920" height="1020" alt="Screenshot 2026-11-10 183731" src="https://github.com/user-attachments/assets/8461d200-84c6-4157-9afd-7d9b8ece543f" />

<img width="1920" height="1020" alt="Screenshot 2026-11-10 183840" src="https://github.com/user-attachments/assets/2e864540-6003-495b-afcc-2e7442bcc683" />

<img width="1920" height="1020" alt="Screenshot 2026-11-10 183934" src="https://github.com/user-attachments/assets/43f07dca-6c54-4847-961b-fb782db3ad5c" />


<img width="1920" height="1020" alt="Screenshot 2026-11-10 183944" src="https://github.com/user-attachments/assets/89d1057d-4575-4edc-8456-6ef3721385c7" />

<img width="1920" height="1020" alt="Screenshot 2026-11-10 191021" src="https://github.com/user-attachments/assets/d90ea9e6-9b96-47b3-b45c-2d89b66b5669" />

<img width="1920" height="1020" alt="Screenshot 2026-11-10 191054" src="https://github.com/user-attachments/assets/2c15eb58-8241-4266-ba8e-d4d53e5a9b36" />


<img width="1920" height="1020" alt="Screenshot 2026-11-10 191429" src="https://github.com/user-attachments/assets/ea495424-2aa3-422e-9774-ebfeda496770" />

<img width="1920" height="1020" alt="Screenshot 2026-11-10 191708" src="https://github.com/user-attachments/assets/66dbd738-ff68-4c33-8c61-3416f868887b" />

<img width="1920" height="1020" alt="Screenshot 2026-11-10 191816" src="https://github.com/user-attachments/assets/74d7d930-9a70-4285-bdee-c9c2443b4ac0" />

<img width="1920" height="1020" alt="Screenshot 2026-11-10 192341" src="https://github.com/user-attachments/assets/16d81bb8-5e40-4c22-9c60-025a179f9128" />

<img width="1920" height="1020" alt="Screenshot 2026-11-10 192633" src="https://github.com/user-attachments/assets/a885c72e-d09c-4283-9ad9-ec3ba8cc23b6" />

<img width="1920" height="1020" alt="Screenshot 2026-11-10 192641" src="https://github.com/user-attachments/assets/f8910355-7248-44e6-bac1-095b0eb1e568" />


<img width="1920" height="1020" alt="Screenshot 2026-11-10 192735" src="https://github.com/user-attachments/assets/0ed66001-1d90-446f-85c8-83acc786d8e6" />


<img width="1920" height="1020" alt="Screenshot 2026-11-10 192806" src="https://github.com/user-attachments/assets/9c1f20b1-c960-40e2-9cd7-6e9e8619c7f0" />

<img width="1920" height="1020" alt="Screenshot 2026-11-10 192917" src="https://github.com/user-attachments/assets/6d1adb2d-27d8-45dc-99da-25c4c6e556e0" />


Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
 
