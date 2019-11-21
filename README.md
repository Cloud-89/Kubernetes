# Installation of AWS CLI
 curl https://s3.amazonaws.com/aws-cli/awscli-bundle.zip -o awscli-bundle.zip
 yum install unzip python     /*If your system don't have unzip & python */
 unzip awscli-bundle.zip
 -> 
# Kubernetes
# Installation kubernetes Using Kops
Step-1 
 -> Launch Linux EC2 instance in AWS
Step-2
 
 -> Create and attach IAM role to EC2 Instance with following Access.
     Kops need permissions to access
      -	S3
	    - EC2
	    - VPC
	    - Route53
	    - Autoscaling
	      etc.
Step-3
 -> 

