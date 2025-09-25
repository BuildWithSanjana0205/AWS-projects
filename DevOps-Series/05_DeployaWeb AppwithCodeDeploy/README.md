🏗️ Project 5: Deploy an App with CodeDeploy

Automated the deployment of a Java web application using AWS CodeDeploy, with infrastructure provisioned through CloudFormation and deployment processes managed via appspec.yml and custom scripts.

📌 Objective

Learn how to automate application deployments using AWS CodeDeploy, while exploring Infrastructure as Code with CloudFormation for scalable environment setup.

🛠️ AWS Services & Tools

Amazon EC2

AWS CloudFormation (Infrastructure as Code)

AWS CodeDeploy

AWS CodeArtifact

Apache Maven

Amazon Corretto 8

Amazon S3 (Artifacts Storage)

AWS IAM (Permissions & Roles)

🏗️ Architecture Diagram

🚀 Steps Performed
🔹 Launch Infrastructure with CloudFormation

Created a CloudFormation stack to provision an EC2 instance.

Gained first exposure to Infrastructure as Code (IaC) concepts.

Learned how CloudFormation templates define resources and configurations.

🔹 Prepare Deployment Files

Wrote deployment scripts for installing dependencies, starting, and stopping the server.

Created an appspec.yml file to guide CodeDeploy during the deployment process.

Updated the buildspec.yml file to package deployment files into the artifact.

🔹 Configure CodeDeploy

Created a CodeDeploy application representing the target workload.

Set up a deployment group with target EC2 instances and deployment settings.

Granted CodeDeploy permissions to access CodeArtifact and artifacts stored in S3.

🔹 Execute Deployment

Launched a CodeDeploy deployment from the packaged artifacts.

Monitored the deployment process through the AWS Console.

Verified the deployed application was running successfully on the EC2 instance.

🎯 Outcome

Automated deployment of a Java web application with AWS CodeDeploy.

Built and deployed infrastructure using CloudFormation templates.

Implemented enterprise-style CI/CD deployment automation.

✅ Key Learnings

AWS CodeDeploy Concepts: applications, deployment groups, and automated rollouts.

Infrastructure Setup: importance of CloudFormation and IaC in deployments.

Deployment Files: writing and managing appspec.yml, deployment scripts, and system services (systemctl).

📄 Detailed Documentation: View Full Project Document

🔗 Next Project: CI/CD with CodePipeline