# TW
This is a Mediawiki Automation Code.

Docker hub Mediawiki OS location.
https://hub.docker.com/repository/docker/ajitabh7/mediawiki7/tags?page=1 

PREREQUISITES
1) AWS account and connection set up with pub key and secret key.
2) Terraform and Git. 


STEPS:
 1. Clone the repo to local.

  git clone https://github.com/Ajitabh7/TW.git 


2. change the directory to terraform 
  cd TW/terraform
 
3. Initialize and apply terraform -->
   terraform init  &&  terraform apply

 MediaWiki URL can be accessible at  http://{AWS_Ec2_instance_publicip}:30301/wiki

