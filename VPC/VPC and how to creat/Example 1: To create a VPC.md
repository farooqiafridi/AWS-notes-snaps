Example 1: To create a VPC
---------------------------------------

The following create-vpc example creates a VPC with the specified IPv4 CIDR block and a Name tag.

# aws ec2 create-vpc --cidr-block 10.0.0.0/16 --tag-specification ResourceType=vpc,Tags=[{Key=Name,Value=MyVpc}]
 
 
    Example 1: To describe all of your VPCs
=================================================================================
The following describe-vpcs example retrieves details about your VPCs.

# aws ec2 describe-vpcs

# aws ec2 describe-vpcs --vpc-ids vpc-06e4ab6c6cEXAMPLE
