# lab_cf
This lab implements a scalable, secure cloud network architecture using AWS CloudFormation for a company called FridayHITT. 
 The aims of this lab are:
  1.	A scalable, secure design was created from cloud formation and an infrastructure created.
      It must meet the business requirements of a network with public and private subnets, EC2 instances, security groups, routing tables, and other AWS services.
  3.	The infrastructure has a public EC2 instance and a private EC2 instance. The private instance should only be accessed securely, through a jump box (bastion host).
  4.	Security groups allow only essential traffic between components and from IP ranges.
  5.	Routing tables and an Internet Gateway were configured to allow controlled access to the internet and block any unauthorised communication.
  6.	A jump box was to be deployed in the public subnet, to securely connect to the EC2 instance in the private subnet using SSH.
  7.	The design supports multiple Availability Zones (AZs) for high availability.

