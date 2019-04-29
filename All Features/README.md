# Netskope AWS CloudFormation Template - All Features

This CloudFormation Template will build a stack that enables all the requirements for the Netskope Security Assessment Feature.

These requirements include an S3 Bucket, SNS Topic, Cloudtrail Trail, and an IAM Role.


#### Before running the template you will need to collect information from the Netskope Tenant. In the tenant, start the configuration of an AWS instance to find out the External ID that is unique to your tenant.

###### Parameters required to run the template
* Netskope External ID 
* Unique S3 Bucket Name



<a href="https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=Netskope-AWS-CF&templateURL=https://s3.amazonaws.com/netskope-aws/netskope-aws-all.yaml">  
   <img src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png"/></a>
