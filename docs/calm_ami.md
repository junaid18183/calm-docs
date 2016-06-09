# Before You Begin

Before you start using AWS with Calm, you need to deploy Calm from our AWS AMI. To do so, you’ll need the following:

* An AWS account with valid credentials

* An IAM user account with the following permissions and access:

    * EC2 Full Permissions

    * IAM Read Only Access

!!! tip "Note"
	To know more about creating an IAM user on AWS, go to [this AWS Documentation page](http://docs.aws.amazon.com/IAM/latest/UserGuide/id_users_create.html).

* The Access Key ID and the Secret Access Key for your IAM user account with AWS. 

## Setting up an IAM User Account

We have developed a script that creates an IAM user along with the necessary permissions and a security group for deploying a Calm AMI. This script can be used with AWS CloudFormation to create an IAM user. 

The script can be downloaded from: <link>

To create an IAM user with the AWS CloudFormation template, do the following:

* Download the script from:

2. Select **CloudFormation** from the AWS dashboard > **Management Tools**. 

3. Select **Create Stack**. 

4. Select **Select a sample template** under **Choose a template**, and choose the script to be uploaded from the directory that you saved the script in. 

## Instance Requirements

In order to use the Calm Community AMI seamlessly, it is advisable to configure the instance according to the following requirements:

* **Disk Space**: A minimum of 40 GB. 100 GB of disk space is advisable. 

* **Shutdown Behaviour**: Stop

# Launching the Calm Community AMI

To access your Calm AMI, do the following:

* Select the Calm AMI you launched from the list of **Running Instances** from your **EC2** dashboard. 

* Copy the **Public DNS** and paste it into any web browser and hit **Enter**. This initiates the **Calm Setup Wizard**.

The **Calm Setup Wizard** will now take you through creating a Calm account and setting up your Calm instance for use. 