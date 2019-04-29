# Netskope AWS Cloudformation Template - Security Assessment


This CloudFormation Template will build a stack that enables all the requirements for the Netskope Security Assessment Feature.

For Security Assessment and Inventory, these requirements include an IAM Role.


#### Before running the template you will need to collect information from the Netskope Tenant. In the tenant, start the configuration of an AWS instance to find out the External ID that is unique to your tenant.

###### Parameters required to run the template
* Netskope External ID


<a href="https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=Netskope-AWS-CF&templateURL=https://s3.amazonaws.com/netskope-aws/netskope-aws-csa-inventory.yaml">  
   <img src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png"/></a>
