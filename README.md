This lab is an environment for creating an Amazon VPC and Amazon EC2 instance 
(and other supporting elements) using an AWS CloudFormation template.  
-

The goal of this lab is to create a CloudFormation template with the following components.

    * An Amazon Virtual Private Cloud
    * An internet gateway attached to the VPC
    * Security groups for accessing the VPC configured to allow SSH from anywhere
    * A private subnet within the VPC
    * An Amazon EC2 instance (a T3.micro) within the private subnet 
    Note: It is not necessary to access the EC2 via SSH or Remote Desktop for a successful solution
    

Build and test the solution until all components build.
-



Run the following command to see the account number and your user ID:

     * aws sts get-caller-identity


If you have any EC2 instances running in the sandbox, running this command would provide information about them:

    * aws ec2 describe-instances
