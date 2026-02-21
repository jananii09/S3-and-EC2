# EX NO: 2 CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-
# NAME: JANANI SHREE A
# REGISTER NUMBER: 212224100023
# AIM :
To create an AWS account, set up a root user, and create an IAM user with specified permissions.

# PROBLEM STATEMENT :
This experiment involves creating an AWS account, configuring security settings for the root user, and setting up an IAM user. IAM users allow for secure, managed access to AWS resources without exposing the main account's root credentials.

## Procedure:
# Sign in to the AWS Management Console:
• Go to the AWS Management Console and log in with your AWS credentials.
# Navigate to the EC2 Dashboard:
• Once logged in, locate and click on the "EC2" service in the AWS Management Console.
# Launch an Instance:
• On the EC2 dashboard, click the "Launch Instance" button.
# Choose an AMI (Amazon Machine Image):
• Select the operating system and software you want to use for your instance (e.g., Amazon Linux, Ubuntu, Windows).
• Click "Select" to choose the AMI.
# Choose an Instance Type:
• Select the type of instance you need (e.g., t2.micro, m5.large) based on your workload requirements.
• Click "Next: Configure Instance Details".
# Configure Instance Details:
• Set the number of instances to launch, the availability zone, and other optional settings like networking and security.
• Click "Next: Add Storage".
# Configure Storage:
• Specify the size and type of storage for your instance.
• Click "Next: Add Tags".
# Add Tags (Optional):
• Add tags to your instance for easier identification and management.
• Click "Next: Configure Security Group".
# Configure Security Group:
• Choose or create a security group to control inbound and outbound traffic to your instance.
• Click "Review and Launch".
# Review and Launch:
• Review all the configurations and click "Launch".
Create a Key Pair (if you haven't already):
• You'll be prompted to create a new key pair or choose an existing one.
• Download the key pair (.pem file) and store it securely.
# Launch the Instance:
• Click "Launch Instance" to start the instance creation process.
# Connect to your Instance:
• Once the instance is running, you can connect to it using SSH (for Linux) or RDP (for Windows).
• Use the key pair you downloaded earlier to connect.

# OUTPUT

<img width="1296" height="667" alt="image" src="https://github.com/user-attachments/assets/dab63cfc-6b19-4e47-9242-9154f0df28be" />

<img width="1266" height="687" alt="image" src="https://github.com/user-attachments/assets/e559766c-dbd3-422a-bbb1-7a6ea48bb88b" />

<img width="1404" height="719" alt="image" src="https://github.com/user-attachments/assets/e7fca864-267a-48d5-9c2a-6ac69589e3ac" />

<img width="1391" height="745" alt="image" src="https://github.com/user-attachments/assets/e03b40c0-79bf-41e2-998d-45ca6f4113b0" />



# RESULT
The AWS account was successfully created, with set up for the root user . Additionally, an IAM user was created with specified permissions, allowing for secure, controlled access to AWS resources without the use of the root account.
