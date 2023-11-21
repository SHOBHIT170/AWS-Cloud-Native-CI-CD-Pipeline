# Setting up a CI/CD Pipeline with AWS CodePipeline and CodeDeploy

Description:

This guide helps you automate the process of delivering your software using AWS services - CodePipeline and CodeDeploy. The pipeline takes care of building, testing, and deploying a sample application stored in an AWS S3 bucket to servers on Amazon EC2.

Step-by-Step Overview:

1. Create an S3 Bucket for the Application:
    Create a versioned S3 bucket to store the source code and application artifacts.
    Enable versioning to track changes to objects in the bucket.
    
2. Create Amazon EC2 Windows Instances and Install CodeDeploy Agent:
    Set up Windows Server Amazon EC2 instances to deploy the sample application.
    Install the CodeDeploy agent on the instances to facilitate deployments.

3. Create an Application in CodeDeploy:
    Establish a CodeDeploy application and deployment group for managing deployments.

4. Create Your First Pipeline in CodePipeline:
    Utilize AWS CodePipeline to create a two-stage pipeline.
    Connect the pipeline to the versioned S3 bucket as the source and use CodeDeploy for deployment.

5. Add Another Stage to Your Pipeline:
    Extend the pipeline by adding another deployment stage, demonstrating flexibility in the CI/CD process.

Clean Up Resources:
Follow the instructions provided to clean up resources, ensuring you are not incurring unnecessary costs.
