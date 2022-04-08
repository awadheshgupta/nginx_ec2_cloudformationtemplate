` `Cloudformation template:

Creates EC2 instance in AWS

Starts Nginx server on that EC2 with “Hello world” html

Steps to execute :

1. Please save webinstance\_ec2\_nginx.yaml to your choice location.
1. Open AWS UI, CloudFormation – Create stack 

   ![](screenshots/image001.png)



![](screenshots/image002.png)

Input required:
Stack name
AMI image id (We can get that from AWS Market place or customized AMI)

Subnet

VPC


1. ![](screenshots/image002.png)

1. ![](screenshots/image003.png)

1. ![](screenshots/image004.png)
   Click on Create stack.
1. Once completed successfully. 

![](screenshots/image005.png)![](screenshots/image006.png)

![](screenshots/image007.png)


   ![](screenshots/image007.png)
1. Validation of Nginx services.
   ![](screenshots/image008.png)
