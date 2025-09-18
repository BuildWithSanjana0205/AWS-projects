# 🏗️ Project 8: Access S3 from a VPC

Explored how to connect an EC2 instance inside a VPC to an S3 bucket using the AWS CLI and access keys, without relying on VPC endpoints.

---

## 📌 Objective
Gain hands-on experience with enabling internet-based access from an EC2 instance in a VPC to Amazon S3 using the AWS CLI.

---

## 🛠️ AWS Services & Concepts
- Amazon VPC  
- Amazon S3  
- Amazon EC2  
- AWS CLI  
- Access Key & Secret Key  

---

## 🏗️ Architecture Diagram
![Architecture Diagram](LINK_TO_DIAGRAM)

---

## 🚀 Steps Performed
1. **Connected to the VPC**  
   - Launched an EC2 instance in the VPC and accessed it using SSH  
   - Ensured the instance had internet access via an Internet Gateway  

2. **Created IAM Access Keys for Authentication**  
   - Generated an **Access Key ID** and **Secret Access Key** for the IAM user  
   - Configured AWS CLI on the EC2 instance with the new credentials  

3. **Created an S3 Bucket**  
   - Set up a new S3 bucket to test connectivity  
   - Configured bucket policies for access as required  

4. **Accessed the S3 Bucket from EC2 Using AWS CLI**  
   - Ran CLI commands (`aws s3 ls`, `aws s3 cp`, etc.) from the EC2 instance  
   - Verified successful upload and download operations to/from the bucket  

---

## 🎯 Outcome
- EC2 instance inside the VPC successfully accessed S3 over the internet  
- Validated authentication using IAM access keys with the AWS CLI  
- Reinforced understanding of connecting VPC resources to AWS services without endpoints  

---

## ✅ Key Learnings
- How to configure and use the **AWS CLI** for resource access  
- Role of **Access Keys and Secret Keys** in authentication  
- How EC2 instances in a VPC can reach S3 via internet connectivity  
- Limitations of not using VPC Endpoints (e.g., dependence on internet access)  

---

📄 **Detailed Documentation:** [View Full Project Document](LINK_TO_YOUR_DOCUMENT)  

🔗 Next Project: [VPC Endpoints](LINK_TO_NEXT_PROJECT)  

✅ *This is Project 8 of a 9-part AWS Networking Series.*
