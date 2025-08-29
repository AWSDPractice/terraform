# terraform
terraform and aws ki configuration or connect cheyyadaniki after downloading terraform we have to download and install aws cli
AFTER THATTHROUGH VISUAL STUDIO  we have to write code for terroform 
for connection of terraform and visual studio we have to write first provider.tf code.. in this provider we should write configuration of terraform 
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
