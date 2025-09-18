# 🏗️ Project 9: Access S3 from a VPC Using VPC Endpoints

Created a secure, private connection between a VPC and Amazon S3 using a **VPC Endpoint**, ensuring traffic never traverses the public internet.

---

## 📌 Objective
Gain hands-on experience with VPC Endpoints to enable private, secure communication between VPC resources and Amazon S3.

---

## 🛠️ AWS Services & Concepts
- Amazon VPC  
- Amazon S3  
- EC2 Instances  
- VPC Endpoints  
- Gateway & Interface Endpoints  
- Endpoint Policies  

---

## 🏗️ Architecture Diagram
![Architecture Diagram](LINK_TO_DIAGRAM)

---

## 🚀 Steps Performed
1. **Connected to the EC2 Instance in the VPC**  
   - Launched and accessed an EC2 instance inside the VPC  
   - Prepared the environment for testing S3 connectivity  

2. **Created a VPC Endpoint for S3**  
   - Configured a **Gateway VPC Endpoint** for S3  
   - Associated the endpoint with the correct route tables  

3. **Configured a Secure Bucket Policy**  
   - Updated the S3 bucket policy to only allow access through the VPC Endpoint  
   - Blocked all direct internet-based access for enhanced security  

4. **Accessed the S3 Bucket Using the Endpoint**  
   - Ran AWS CLI commands (`aws s3 ls`, `aws s3 cp`) from the EC2 instance  
   - Verified that traffic flowed securely through the VPC Endpoint without touching the public internet  

---

## 🎯 Outcome
- Established a private, secure connection between the VPC and S3  
- Confirmed that S3 access was restricted to the VPC Endpoint  
- Reinforced the importance of private connectivity in secure cloud architectures  

---

## ✅ Key Learnings
- Difference between **Gateway** and **Interface** VPC Endpoints  
- How **Endpoint Policies** restrict access to AWS services  
- Importance of using VPC Endpoints for secure, private communication  
- Eliminating internet dependency for accessing AWS services from within a VPC  

---

📄 **Detailed Documentation:** [View Full Project Document](LINK_TO_YOUR_DOCUMENT)  

🎉 This marks the completion of the series!  

✅ *This is Project 9 of a 9-part AWS Networking Series.*
