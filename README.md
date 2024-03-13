# Launching Jenkins Server via CloudFormation Template

This guide will walk you through the steps to launch a Jenkins server on AWS using a CloudFormation template.

## Prerequisites
- An AWS account with appropriate permissions to create resources using CloudFormation.
- AWS CLI installed and configured on your local machine.

## Steps

1. Clone the repository
git clone https://github.com/anii234/aws_jenkinServer.git

2. Navigate to the directory containing the CloudFormation template.
cd aws_jenkinServer


3. Modify the CloudFormation template (if necessary) to customize parameters such as instance type, key pair, etc. The template may contain parameters like `KeyName`, `InstanceType`, etc.

4. Validate the CloudFormation template to ensure its syntax is correct.


5. Deploy the CloudFormation stack using the template or upload the template via AWS console.

7. Once the stack creation is complete, navigate to the AWS Management Console.

8. Go to the EC2 dashboard and find the public IP address or public DNS of the Jenkins server instance.

9. Access Jenkins by opening a web browser and navigating to `http://<Jenkins_Public_IP>:3000`.

## Cleanup
To avoid incurring unnecessary charges, don't forget to delete the CloudFormation stack once you're done using Jenkins.

To delete the stack using AWS CLI, run:

