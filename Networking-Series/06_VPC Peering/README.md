# 🏗️ Project 6: VPC Peering

Configured and tested VPC Peering to enable secure communication between two different VPCs, simulating cross-network connectivity within AWS.

---

## 📌 Objective
Gain hands-on experience with creating and managing VPC Peering connections to allow private communication across separate VPCs.

---

## 🛠️ AWS Services & Concepts
- Amazon VPC  
- VPC Peering  
- Route Tables  
- Security Groups  
- CIDR Blocks  
- Cross-VPC Communication  

---

## 🏗️ Architecture Diagram
![Architecture Diagram](LINK_TO_DIAGRAM)

---

## 🚀 Steps Performed
1. **Created Two VPCs**  
   - Set up two separate VPCs with unique CIDR blocks to avoid overlap  
   - Each VPC contained its own subnets and resources  

2. **Established a VPC Peering Connection**  
   - Initiated a VPC Peering request from VPC-A to VPC-B  
   - Accepted the request in VPC-B to establish the connection  

3. **Updated Route Tables**  
   - Modified route tables in both VPCs to include routes pointing to the peered VPC’s CIDR block  
   - Ensured that traffic between the two VPCs was directed correctly  

4. **Configured Security Groups**  
   - Allowed inbound and outbound rules for ICMP, SSH, and HTTP/HTTPS between instances in the peered VPCs  
   - Verified that traffic was not blocked by restrictive rules  

5. **Tested Cross-VPC Connectivity**  
   - Used **Ping** to confirm reachability between instances in different VPCs  
   - Validated application-level communication using **Curl** and SSH  

---

## 🎯 Outcome
- Successful VPC Peering connection established between two independent VPCs  
- Verified secure communication across private networks  
- Reinforced understanding of cross-VPC networking in AWS  

---

## ✅ Key Learnings
- Importance of unique, non-overlapping CIDR blocks for VPC Peering  
- Role of route tables in enabling communication across VPCs  
- Security group adjustments required for cross-VPC communication  
- Practical use cases of VPC Peering in multi-VPC architectures  

---

📄 **Detailed Documentation:** [View Full Project Document](LINK_TO_YOUR_DOCUMENT)  

🔗 Next Project: [VPC Monitoring with Flow Logs](LINK_TO_NEXT_PROJECT)  

✅ *This is Project 6 of a 9-part AWS Networking Series.*
