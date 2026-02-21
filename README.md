# terraform
terraform and aws ki configuration (connect) cheyyadaniki - after downloading terraform 
we have to download and install aws cli
open git -enter aws configure- enter i am user (user already had admin access) access id and key -enter region then after you have to check it was successfully configured or not
enter aws s3 ls (without getting error it is successflly conigured)
create repo for terraform and through repo code configure with git use git clone 
after that through VISUAL STUDIO  we have to write code for terroform 
for connection of terraform and visual studio we have to write first provider.tf code.. in this provider we should write configuration of terraform 


for configuration scrpt
go to terraform aws providers registry
click on browse providers
clickon public cloud
click on aws
click on head of the rightside we have providers button -when you click on that script code will visible 
copy the script and paste on 
provider.tf file -already created in vs code 

terraform {
  required_providers {
    aws = {
      source  = "hashicorp/aws"
      version = "~> 6.0"
    }
  }
}

# Configure the AWS Provider
provider "aws" {
  region = "us-east-1"
}
after that we can start our codes  
