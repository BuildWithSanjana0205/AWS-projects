# 🏗️ Project 2: Aurora Database with EC2

This project demonstrates how to set up an **Amazon Aurora MySQL database** and connect it with an **EC2 instance**.  
It highlights secure database-to-compute connectivity — a foundational step toward building cloud-hosted applications.

---

## 📌 Objective

To launch an Aurora MySQL database cluster and configure it to securely connect with an EC2 instance.

---

## 🛠️ AWS Services Used

- **Amazon Aurora (MySQL-Compatible)**
- **Amazon EC2**
- **Security Groups**
- **VPC Networking**

---

## 🚀 Steps Performed

### 🔹 Launch EC2 Instance
- Provisioned an EC2 instance from scratch.  
- Configured security group rules for inbound SSH/MySQL connections.  

### 🔹 Create Aurora Database
- Launched an Aurora MySQL database cluster.  
- Understood **engine type**, **instance configuration**, and **launch templates**.  
- Identified the role of **writer** and **reader** instances with their respective endpoints.  

### 🔹 Configure Connectivity
- Updated Aurora DB security group to allow inbound traffic from the EC2 instance.  
- Verified connection between EC2 and Aurora using MySQL client.  

---

## 📊 Outcome

- Successfully connected an EC2 instance to an Aurora MySQL database.  
- Understood cluster-based architecture with **reader/writer endpoints**.  
- Gained insight into integrating managed databases with compute resources.  

---

## 📷 Screenshots

Relevant screenshots are available in the `screenshots/` folder.  

---

## ✅ Key Learnings

- Fundamentals of **Amazon Aurora** as a cloud-native relational database.  
- Difference between **reader and writer endpoints**.  
- How to configure **secure connectivity between EC2 and Aurora**.  
- Foundation for building **full-stack applications** on AWS.  

---

📄 **Detailed Documentation:** [View Full Project Document](LINK_TO_YOUR_DOCUMENT)  
> Replace with your actual link (Google Drive, Notion, etc.).

---

👉 *This is Project 2 of a 5-part AWS Database Series.*
