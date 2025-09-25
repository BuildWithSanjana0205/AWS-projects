🏗️ Project 3: Store Dependencies in CodeArtifact

Integrated AWS CodeArtifact with Maven to securely store and manage application dependencies, ensuring centralized access control and consistent builds across environments.

📌 Objective

Learn how to package, publish, and securely store application dependencies in AWS CodeArtifact as part of a DevOps pipeline.

🛠️ AWS Services & Tools

Amazon EC2

GitHub (Version Control)

Apache Maven (Build Automation)

AWS CodeArtifact

AWS IAM (Authentication & Permissions)

🏗️ Architecture Diagram

🚀 Steps Performed
🔹 Build & Package the Application

Built and packaged a Java web app using Maven on the EC2 instance.

Verified the generated .jar/.war file for deployment.

🔹 Version Control Integration

Connected the project to GitHub for source code management.

Ensured changes synced from EC2 to GitHub repo.

🔹 Configure CodeArtifact

Created a CodeArtifact domain and repository in AWS.

Retrieved repository endpoint and authentication token.

🔹 Maven Integration

Updated the settings.xml file with CodeArtifact authentication details.

Added repository configuration in the pom.xml.

Used the mvn deploy command to publish the package into CodeArtifact.

🔹 Troubleshoot & Authenticate

Encountered 401 Unauthorized errors due to misconfigured credentials.

Fixed by regenerating authentication tokens and updating settings.xml.

Successfully published artifacts after resolving issues.

🎯 Outcome

Packaged and deployed a Java web application into AWS CodeArtifact.

Secured dependency management with IAM roles and token-based authentication.

Laid the groundwork for enterprise-grade dependency management.

✅ Key Learnings

Hands-on with Maven Deploy plugin.

Understood how CodeArtifact + IAM + tokens ensure secure access.

Learned to properly configure settings.xml and repository endpoints.

⚡ Challenges Faced

Token expiry required frequent regeneration and updates.

Debugging authorization errors before achieving the satisfying “BUILD SUCCESS” ✅.

📄 Detailed Documentation: View Full Project Document

🔗 Next Project: Package an App with CodeBuild