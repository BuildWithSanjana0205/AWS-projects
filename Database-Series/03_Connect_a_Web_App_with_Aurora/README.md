# 🏗️ Project 3: Connect a Web App with Aurora

This project extends the previous setup (Aurora + EC2) by deploying a **web application** on EC2 and securely connecting it with an **Aurora MySQL database**.  
It demonstrates how frontend input can interact with backend databases on AWS, forming the foundation for full-stack cloud applications.

---

## 📌 Objective

To build a simple web app on EC2 and integrate it with an Aurora MySQL database, enabling real-time interaction between the application and the database.

---

## 🛠️ AWS Services Used

- **Amazon Aurora (MySQL-Compatible)**
- **Amazon EC2**
- **VPC Security Groups**
- **MariaDB/MySQL CLI**
- **Nano (Linux text editor)**

---

## 🚀 Steps Performed

### 🔹 Launch EC2 & Aurora
- Provisioned an EC2 instance and Aurora MySQL database cluster.  
- Configured security groups to allow EC2-to-Aurora connectivity.  

### 🔹 Build a Web App
- Installed required packages on EC2 (Apache, PHP, MySQL client).  
- Created a basic **HTML + PHP web form** to capture user input.  
- Wrote a **PHP script** to insert form data into the Aurora DB.  

### 🔹 Configure & Test Database
- Used **MySQL CLI** to verify Aurora connectivity.  
- Ran SQL queries to confirm data flow from web app → Aurora database.  
- Edited PHP/HTML files directly on EC2 using **Nano**.  

---

## 📊 Outcome

- A working **web app** hosted on EC2 connected seamlessly to **Aurora MySQL**.  
- Verified data insertion and retrieval using SQL CLI commands.  
- End-to-end integration of **frontend + backend** services on AWS.  

---

## 📷 Screenshots

Relevant screenshots are available in the `screenshots/` folder.  

---

## ✅ Key Learnings

- How to integrate **Aurora databases with web apps**.  
- Difference between **reader/writer endpoints** in Aurora clusters.  
- Using **MySQL CLI** for database validation.  
- Editing and deploying application files with **Nano** on EC2.  
- Practical exposure to **full-stack architecture on AWS**.  

---

📄 **Detailed Documentation:** [View Full Project Document](LINK_TO_YOUR_DOCUMENT)  
> Replace with your actual link (Google Drive, Notion, etc.).

---

👉 *This is Project 3 of a 5-part AWS Database Series.*
