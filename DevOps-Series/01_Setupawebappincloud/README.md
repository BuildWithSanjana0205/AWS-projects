🏗️ Project 1: Set Up a Web App in the Cloud

Deployed a Java-based web application on AWS by creating an EC2 instance, configuring secure access, and connecting VS Code for remote development.

📌 Objective

Gain hands-on experience in setting up a cloud-hosted web application environment as the foundation of the DevOps CI/CD pipeline.

🛠️ AWS Services & Tools

Amazon EC2

SSH with .pem key

Maven (Build Automation)

Amazon Corretto 8 (OpenJDK Distribution)

Visual Studio Code (Remote - SSH Extension)

🏗️ Architecture Diagram

🚀 Steps Performed
🔹 Launch & Configure EC2

Created an Amazon EC2 instance to act as the web app server.

Configured the .pem file in VS Code terminal using icacls for secure permissions.

Verified SSH connectivity using the ssh -i command to log in remotely.

🔹 Set Up Build Environment

Installed Maven for Java build automation.

Installed Amazon Corretto 8 as the JDK to compile and run Java applications.

Confirmed environment setup for smooth project generation and execution.

🔹 Build the Web Application

Generated a Java web app structure with Maven (pom.xml, src/webapp, etc.).

Verified that the project structure followed best practices and dependencies were managed automatically.

🔹 Connect VS Code to EC2

Installed the Remote - SSH extension in VS Code.

Added the EC2 instance as a host and established a direct connection.

Used full IDE features (file navigation, editing pom.xml and index.jsp) directly on the remote server.

🎯 Outcome

Successfully deployed and managed a Java web application in the cloud.

Established a secure workflow for development and server management via VS Code.

Built the base environment for future DevOps pipeline projects.

✅ Key Learnings

Understood EC2 setup, SSH connectivity, and key file management.

Learned how Maven + Corretto streamline Java application builds.

Became comfortable with VS Code remote development instead of Notepad++.

📄 Detailed Documentation: View Full Project Document

🔗 Next Project: Connect a GitHub Repo with AWS