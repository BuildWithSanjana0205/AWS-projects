# 🏗️ Project 1: Visualize a Relational Database

This project demonstrates how to build a relational database on **Amazon RDS**, connect to it using **SQL Workbench**, and visualize the data with **Amazon QuickSight**.  
It covers provisioning, data loading, securing connectivity, and enabling cloud-based analytics.

---

## 📌 Objective

To create a cloud-hosted relational database using RDS (MySQL), populate it with sample data, and connect it to QuickSight for visualization.

---

## 🛠️ AWS Services Used

- **Amazon RDS** (MySQL engine)
- **Amazon QuickSight**
- **SQL Workbench**
- **IAM & Security Groups**

---

## 🚀 Steps Performed

### 🔹 Create RDS Instance
- Launched an RDS MySQL database with free-tier settings.  
- Configured DB identifier, username, and password.  

### 🔹 Configure Connectivity
- Modified security groups to allow MySQL access.  
- Made the RDS instance publicly accessible for initial testing.  
- Connected successfully using **SQL Workbench**.  

### 🔹 Create Tables & Load Data
- Created a schema (`QuickSightDatabase`) in SQL Workbench.  
- Designed relational tables (`newhire`, etc.).  
- Inserted sample employee records for visualization.  

### 🔹 Secure the Setup
- Created dedicated security groups for **QuickSight** and **RDS**.  
- Updated IAM role permissions for QuickSight VPC connections.  
- Reconfigured RDS to private access and allowed only QuickSight’s security group.  

### 🔹 Connect RDS to QuickSight
- Added a VPC connection for QuickSight.  
- Linked QuickSight with the secured RDS database.  
- Built sample dashboards for analysis.  

---

## 📊 Outcome

- Successfully created and populated an RDS instance.  
- Established secure connectivity with QuickSight.  
- Generated interactive dashboards to visualize relational data.  

---

## 🏗️ Architectural Diagram

The diagram below illustrates how **Amazon RDS (MySQL)** connects with **SQL Workbench** for querying and **Amazon QuickSight** for visualization, secured with IAM roles and security groups.  
[View Architecture Diagram](./03_Architectural_Diagram.png)

---

## 📷 Screenshots

Relevant screenshots are available in the `screenshots/` folder.  

---

## ✅ Key Learnings

- How to set up and configure **Amazon RDS (MySQL)**.  
- Securely connect third-party tools (SQL Workbench & QuickSight) with RDS.  
- Basics of **relational schema design and data loading**.  
- Building **cloud-native visualizations** in QuickSight.  

---

📄 **Detailed Documentation:** [View Full Project Document](LINK_TO_YOUR_DOCUMENT)  
> Replace with your actual link (Google Drive, Notion, etc.).

---

👉 *This is Project 1 of a 5-part AWS Database Series.*
