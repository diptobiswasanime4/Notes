
Amazon Virtual Private Cloud (VPC) is a user-defined logically isolated virtual network.

This is similar to a traditional network of a data center.

VPC will have one [[Subnet|subnet]] in each [[Availability Zone]]. [[EC2 (Elastic Compute Cloud)|EC2 instances]] are kept within the subnet. There is an [[Internet Gateway]] for communication in between the VPC and the outside internet.

![[VPC.png]]
## [[Subnet]]

A subnet is a range of [[IP Address|IP addresses]] in the VPC. [[AWS| AWS resources]] are deployed in the subnet.

## How to work with Amazon VPC ?

1. Management Console
2. Command Line Interface (CLI)
3. SDKs
4. Query API

