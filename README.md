# aws-cf-ec2-s3-securitygroup
This is a simple AWS CloudFormation JSON file that is used to describe and deploy an ec2 instance, s3 bucket and security group on the ec2 instance.

Before using this template, it is required to already have a keypair already generated to use for this exercise.
I have only defined this script to run a t1.micro or a t2.nano ec2 instance type. Feel free to change it as you need. This will be selected in the Parameter's list when creating the stack in CloudFormation 

Below is the picture of the architecture that is described in the CloudFormation JSON file

![image](https://user-images.githubusercontent.com/98171905/207647828-2a065034-6dc5-4716-969f-f3e27f6afc36.png)
