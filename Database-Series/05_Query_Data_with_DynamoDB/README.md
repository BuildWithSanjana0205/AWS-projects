# 🏗️ Project 5: Query Data with DynamoDB

This project extended my work with **Amazon DynamoDB** by focusing on how to **query data** and introducing the concept of **transactions** in a NoSQL database.  
I practiced querying tables using both the **AWS Console** and **AWS CloudShell**, and performed atomic write operations with transactions.

---

## 📌 Objective

To learn how to **query and retrieve data** from DynamoDB and explore the use of **transactions** for atomic operations.

---

## 🛠️ AWS Services Used

- **Amazon DynamoDB**  
- **AWS CloudShell**  
- **AWS CLI (within CloudShell)**  

---

## 🚀 Steps Performed

### 🔹 Create and Load Data into DynamoDB
- Created a DynamoDB table from scratch using **AWS CloudShell**.  
- Defined **Partition Key** and **Sort Key** for structured querying.  
- Loaded sample data into the table using CloudShell commands.  

### 🔹 Query Operations
- Queried the DynamoDB table using the **AWS Console**:  
  - Retrieved items by specifying the **Partition Key**.  
  - Observed limitations compared to CLI (must specify a Partition Key).  
- Queried the same table using **CloudShell** with AWS CLI commands for more flexibility.  

### 🔹 Transactions in DynamoDB
- Performed a **transaction write** to add multiple items atomically.  
- Understood how transactions ensure **atomicity, consistency, and reliability** when modifying multiple items.  

### 🔹 Capacity Planning
- Used the **Capacity Calculator** with inputs such as:  
  - Average item size  
  - Read/write throughput  
  - Consistency type  
- Understood outputs: **Read Capacity Units (RCU)** and **Write Capacity Units (WCU)**.  

---

## 📊 Outcome

- Successfully queried DynamoDB data using both Console and CloudShell.  
- Gained experience with **transactions** for atomic multi-item writes.  
- Strengthened understanding of **Partition Key vs. Sort Key** in query design.  
- Built confidence in managing DynamoDB with both GUI and CLI tools.  

---

## 📷 Screenshots

Relevant screenshots are available in the `screenshots/` folder.  

---

## ✅ Key Learnings

- **Query in DynamoDB**:  
  - A Query retrieves items based on the **Partition Key**.  
  - CLI/SDK allows more flexibility compared to Console-based queries.  

- **Transactions in DynamoDB**:  
  - Provide **atomic writes** across multiple items.  
  - Ensure data consistency in NoSQL environments.  

- **Difference from Relational Databases**:  
  - Relational DBs allow complex queries across tables.  
  - DynamoDB queries are focused on efficiency with **key-value lookups**.  

- Improved skills in:  
  - CloudShell CLI commands for table creation, data loading, and queries.  
  - Handling unprocessed data.  
  - Planning capacity using RCUs and WCUs.  

---

📄 **Detailed Documentation:** [View Full Project Document](LINK_TO_YOUR_DOCUMENT)  
> Replace with your actual link (Google Drive, Notion, etc.).

---

👉 *This is Project 5 of a 5-part AWS Database Series.*  
🎉 *Series Completed!*  
