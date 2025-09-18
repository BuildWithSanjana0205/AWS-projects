# 🏗️ Project 5: Testing VPC Connectivity

Built on previous projects to validate communication and connectivity between different VPC components, ensuring proper network setup and functionality.

---

## 📌 Objective
Gain practical experience testing VPC connectivity, verifying communication between EC2 instances across subnets, and checking internet access for public servers.

---

## 🛠️ AWS Services & Concepts
- Amazon VPC  
- Public & Private Subnets  
- EC2 Instances  
- EC2 Instance Connect  
- ICMP Protocol  
- Ping & Curl  

---

## 🏗️ Architecture Diagram
![Architecture Diagram](LINK_TO_DIAGRAM)

---

## 🚀 Steps Performed
1. **Tested connectivity of a public EC2 instance**  
   - Launched an EC2 instance in a public subnet  
   - Verified it could be accessed from the internet using its public IP  
   - Ensured proper security group rules were applied to allow inbound traffic  

2. **Verified communication between two EC2 instances in different subnets**  
   - Launched instances in both private and public subnets  
   - Used **Ping** and **ICMP** to test connectivity between them  
   - Checked that private instances could communicate internally while remaining isolated from the internet  

3. **Checked internet connectivity for a public server**  
   - Used **Curl** and other CLI tools to confirm outbound internet access  
   - Ensured that NAT Gateway settings allowed private instances to access external resources when needed  

4. **Used EC2 Instance Connect for browser-based CLI access**  
   - Accessed instances securely through the AWS Management Console without SSH keys  
   - Tested connectivity commands directly from the browser  

5. **Applied ICMP, Ping, and Curl to validate reachability and outbound connections**  
   - ICMP for network-level reachability  
   - Ping for latency and connectivity checks  
   - Curl to test HTTP/HTTPS outbound access  

---

## 🎯 Outcome
- Public EC2 instance successfully reachable from the internet  
- Communication verified between instances in different subnets  
- Internet access confirmed for public servers and private instances (via NAT Gateway)  
- Reinforced understanding of network connectivity testing within a VPC  

---

## ✅ Key Learnings
- How to validate EC2 instance connectivity across subnets  
- Using **Ping** and **ICMP** to test network reachability  
- Using **Curl** to verify outbound connectivity from a public subnet  
- EC2 Instance Connect as a secure, browser-based access method  
- Understanding the role of NAT Gateways in providing controlled internet access  

---

📄 **Detailed Documentation:** [View Full Project Document](LINK_TO_YOUR_DOCUMENT)  

🔗 Next Project: [VPC Peering](LINK_TO_NEXT_PROJECT)  

✅ *This is Project 5 of a 9-part AWS Networking Series.*
