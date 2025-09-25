🏗️ Project 2: Connect a GitHub Repo with AWS

Integrated Git version control with my cloud-hosted web app by connecting the EC2 instance to a GitHub repository, enabling code tracking and seamless collaboration.

📌 Objective

Learn and apply version control with Git by linking a cloud-hosted application on EC2 to a GitHub repository.

🛠️ AWS Services & Tools

Amazon EC2

Git (Version Control System)

GitHub (Remote Repository Hosting)

🏗️ Architecture Diagram

🚀 Steps Performed
🔹 Install Git on EC2

Installed Git on the EC2 instance to enable local version control.

Verified installation with git --version.

🔹 Set Up GitHub Repository

Created a GitHub account and initialized a new repository.

Configured the repo as the cloud-based storage for my web app code.

🔹 Initialize Local Repository

Navigated to the web app folder on EC2.

Ran git init to initialize a local Git repository.

Linked the local repo to GitHub using git remote add origin.

🔹 Work with Git Commands

Staged changes with git add.

Committed updates with git commit -m "message".

Pushed code to GitHub using git push origin main.

🔹 Configure Secure Authentication

Generated a GitHub Personal Access Token (PAT) since password auth is no longer supported.

Used the PAT for secure connection between EC2 and GitHub.

🔹 Verify Sync

Edited index.jsp file on EC2.

Pushed the changes and confirmed they appeared in GitHub repository.

🎯 Outcome

Successfully linked an EC2-hosted web app project to GitHub.

Achieved secure and efficient version control with Git.

Experienced the complete Git workflow: init → stage → commit → push.

✅ Key Learnings

Understood the importance of version control in DevOps.

Learned how to securely authenticate GitHub connections using Personal Access Tokens.

Practiced the core Git workflow commands inside a cloud environment.

📄 Detailed Documentation: View Full Project Document

🔗 Next Project: Store Dependencies in CodeArtifact