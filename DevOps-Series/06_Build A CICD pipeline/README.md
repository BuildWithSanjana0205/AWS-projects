Project 6: Build a CI/CD Pipeline with AWS

Automated the end-to-end software delivery process using AWS CodePipeline, integrating CodeBuild and CodeDeploy to build, test, and deploy applications directly from GitHub commits.

📌 Objective

Learn how to orchestrate a complete CI/CD pipeline that automatically handles code changes from commit to live deployment, ensuring faster, safer, and more reliable software delivery.

🛠️ AWS Services & Tools

AWS CodePipeline (CI/CD orchestration)

AWS CodeBuild (build & test automation)

AWS CodeDeploy (deployment automation)

Amazon EC2

Amazon S3 (artifact store)

AWS IAM (roles & permissions)

GitHub (source control)

🏗️ Architecture Diagram

🚀 Steps Performed
🔹 Pipeline Creation

Created a CodePipeline to orchestrate CI/CD workflow.

Configured the Source stage to pull code directly from GitHub.

🔹 Build Stage (CodeBuild)

Configured CodeBuild to automatically build, test, and package the Java application.

Used buildspec.yml to define build instructions.

🔹 Deploy Stage (CodeDeploy)

Configured CodeDeploy to deploy the application to target EC2 instances.

Used appspec.yml and deployment scripts for dependency installation, service start/stop, and reverse proxy setup.

🔹 End-to-End Testing

Pushed changes to index.jsp in GitHub.

Verified that CodePipeline automatically triggered a build → packaged → deployed → served updated app on EC2.

Observed changes live in the browser within minutes.

🎯 Outcome

Built a fully automated CI/CD pipeline using AWS services.

Achieved continuous integration (builds triggered by commits) and continuous deployment (auto deployment to EC2).

Reduced manual intervention, ensuring faster and more reliable releases.

✅ Key Learnings

CI/CD Orchestration: how CodePipeline ties Source → Build → Deploy into one flow.

Pipeline Configuration: stages, execution modes, webhook events, artifact storage.

Enterprise CI/CD Concepts: automating the full journey from developer commit → production app.

📄 Detailed Documentation: View Full Project Document