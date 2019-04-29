# Netskope AWS Cloudformation Template

Netskope API Protection, previously called Introspection, is a cloud to cloud connection that provides near real-time data and threat protection for both IaaS and SaaS providers.  Before Netskope can connect to any AWS accounts, there is some prep work involved on the AWS side.  This Cloudformation Template will automatically configure an AWS account with the necessary requirements.  The template will configure features such as an S3 Bucket, SNS Topic, Cloudtrail Trail, and an IAM Role.

* If deploying only Netskope Continoius Security Assessment and Inventory(CSA), choose the "Security Assessment" Template.
* If deploying any additional features along with CSA, choose the "Security All Features" Template.

