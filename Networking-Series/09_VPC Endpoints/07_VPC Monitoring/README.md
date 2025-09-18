# 🏗️ Project 7: VPC Monitoring with Flow Logs

Introduced VPC monitoring by capturing and analyzing network traffic using **Amazon VPC Flow Logs** and **Amazon CloudWatch**, enabling visibility into communication patterns inside the VPC.

---

## 📌 Objective
Gain hands-on experience with monitoring and analyzing VPC traffic by creating flow logs, configuring permissions, and using CloudWatch for log storage and analysis.

---

## 🛠️ AWS Services & Concepts
- Amazon VPC  
- VPC Flow Logs  
- Amazon CloudWatch Logs  
- IAM Roles & Policies  
- VPC Peering Traffic Analysis  

---

## 🏗️ Architecture Diagram
![Architecture Diagram](LINK_TO_DIAGRAM)

---

## 🚀 Steps Performed
1. **Created VPC Flow Logs for a Subnet**  
   - Enabled flow logs at the subnet level to capture accepted and rejected traffic  
   - Chose CloudWatch Logs as the destination for storing log data  

2. **Configured IAM Roles and Policies**  
   - Created an IAM role with the required permissions for VPC Flow Logs  
   - Attached a custom policy allowing CloudWatch to write log events  

3. **Generated Traffic Through VPC Peering**  
   - Used instances in peered VPCs to create network activity  
   - Performed connectivity tests (Ping, Curl, SSH) to generate meaningful log entries  

4. **Analyzed Flow Logs in CloudWatch**  
   - Viewed detailed entries showing source/destination IPs, ports, and traffic status  
   - Identified allowed vs. denied traffic patterns for better security visibility  

---

## 🎯 Outcome
- Successfully captured and monitored VPC traffic using Flow Logs  
- Validated how traffic flows across subnets and peered VPCs  
- Reinforced understanding of CloudWatch as a monitoring and analysis tool  

---

## ✅ Key Learnings
- How to enable and configure VPC Flow Logs  
- Importance of IAM roles and policies for logging permissions  
- Practical use of CloudWatch Logs for analyzing network traffic  
- How VPC Peering activity can be monitored for auditing and troubleshooting  

---

📄 **Detailed Documentation:** [View Full Project Document](LINK_TO_YOUR_DOCUMENT)  

🔗 Next Project: [Access S3 from a VPC](LINK_TO_NEXT_PROJECT)  

✅ *This is Project 7 of a 9-part AWS Networking Series.*
