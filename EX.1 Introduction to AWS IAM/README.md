# Lab 1 - Introduction to AWS Identity and Access Management (IAM)

## Title
Introduction to AWS Identity and Access Management (IAM)


## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.


## Prerequisites
- Basic understanding of cloud computing concepts  
- AWS Academy Lab access  
- Web browser with internet connectivity  


## Tools Used
- AWS Management Console  
- AWS Identity and Access Management (IAM)  
- Amazon EC2  
- Amazon S3  


## Tasks Performed

### Task 1: Explore IAM Users and Groups
- Reviewed pre-created IAM users: user-1, user-2, user-3  
- Explored IAM groups: EC2-Admin, EC2-Support, S3-Support  
- Inspected managed and inline policies attached to groups  
**Screenshot:**  
<img width="1252" height="507" alt="image" src="https://github.com/user-attachments/assets/a8b4c415-3d63-465f-ad87-a4d52dfe8290" />

<img width="1255" height="502" alt="image" src="https://github.com/user-attachments/assets/d65adb4a-cd30-41ee-ab72-4bb66489722f" />


### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  

<img width="1920" height="1200" alt="Screenshot (101)" src="https://github.com/user-attachments/assets/623b357b-f6a8-4f44-aaca-cce2e9dcee93" />

<img width="1920" height="1200" alt="Screenshot (100)" src="https://github.com/user-attachments/assets/f47d8b63-aae1-4ddc-b635-875568250e2a" />

<img width="1920" height="1200" alt="Screenshot (99)" src="https://github.com/user-attachments/assets/a323e8fa-06c2-450a-90f8-25ea3902e175" />



### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**  
User-1

<img width="1920" height="1200" alt="Screenshot (102)" src="https://github.com/user-attachments/assets/8629dbe3-50ee-40ee-a948-378d49821bcc" />



User-2

<img width="1920" height="1200" alt="Screenshot (104)" src="https://github.com/user-attachments/assets/36445090-53a8-43e4-9176-2605ffcba13a" />

<img width="1920" height="1200" alt="Screenshot (103)" src="https://github.com/user-attachments/assets/c3d4fb4a-3c2d-4440-b92a-5ffa73454a32" />

User-3


<img width="1920" height="1200" alt="Screenshot (106)" src="https://github.com/user-attachments/assets/76882bfc-65c0-4c68-9133-1cb4f0f6ab20" />



## Workflow
1. Accessed IAM console and reviewed users and groups.  
2. Inspected policy permissions attached to groups.  
3. Assigned users to groups based on their roles.  
4. Logged in as each IAM user using the sign-in URL.  
5. Validated permissions by accessing AWS services.  


## Learning Outcomes
- Understood the role of IAM in AWS security.  
- Learned how IAM users, groups, and policies interact.  
- Gained practical experience implementing role-based access control.  
- Verified permission enforcement through real-time service testing.  


## Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.


## Author
**Name:** Abishek P 212224240002
**Course:** Introduction to Cloud Computing  

