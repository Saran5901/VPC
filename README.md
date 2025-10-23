# VPC
VPC
1. Created a VPC
   It’s your private network in the cloud.
   CIDR range: 10.0.0.0/16

3. Created Subnets
   Public Subnet: 10.0.1.0/24 → can access the internet
   Private Subnet: 10.0.2.0/24 → no direct internet access

4. Added an Internet Gateway (IGW)
   Connected the public subnet to the internet.

5. Created Route Tables
   Public Route Table: sends traffic to the internet via IGW.
   Private Route Table: used only inside the VPC (no internet route).

6. Created EC2 Instance
   Created Both Public & Private Instances.
   And Change the Security groups
   And Connect with VPC
   Successfully VPC Connected with the internet

7. Result
   Successfully Connected with the Internet
   The Public IP is Enable
   The Private is Isolated
   
