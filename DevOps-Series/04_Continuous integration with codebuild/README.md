🏗️ Project 4: Package an App with CodeBuild

Automated the compilation, testing, and packaging of a Java web application using AWS CodeBuild, ensuring consistent and reliable builds directly from source code.

📌 Objective

Learn how to set up AWS CodeBuild for continuous integration, automating the build process whenever changes are pushed to the code repository.

🛠️ AWS Services & Tools

Amazon EC2

Git & GitHub

Apache Maven

Amazon Corretto 8

AWS CodeArtifact

AWS CodeBuild

Amazon S3 (Build Artifacts Storage)

AWS IAM (Permissions & Roles)

🏗️ Architecture Diagram

🚀 Steps Performed
🔹 Prepare the Environment

Launched an EC2 instance and connected via SSH.

Installed Git for version control.

Installed Maven and Amazon Corretto 8 to build the Java application.

Generated a Java web app structure using Maven.

🔹 Integrate with CodeArtifact

Configured CodeArtifact to securely store project dependencies.

Ensured authentication and repository setup for Maven builds.

🔹 Set Up CodeBuild Project

Created a CodeBuild project in AWS.

Connected CodeBuild to GitHub repository for source code integration.

Created an S3 bucket to store build artifacts.

🔹 Automate the Build

Added a buildspec.yml file to define build stages and commands.

Configured IAM permissions for CodeBuild to access CodeArtifact and S3.

Triggered the build process and verified a successful run.

🎯 Outcome

Automated the Java application build process with AWS CodeBuild.

Stored build artifacts securely in Amazon S3.

Achieved a fully functional continuous integration workflow.

✅ Key Learnings

Understood what CodeBuild is and its role in CI/CD pipelines.

Learned the purpose of a buildspec.yml file for build instructions.

Explored the stages of a build: install → pre_build → build → post_build.

📄 Detailed Documentation: View Full Project Document

🔗 Next Project: Deploy an App with CodeDeploy