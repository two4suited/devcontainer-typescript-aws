# Description
Template for Devcontainer using Typescript with AWS,AWS CDK, AWS SAM installed

## Language
Typescript

## Tools
AWS CLI 
Docker in Docker
Git
AWS CDK
AWS SAM

## Additional Setup

- Using Codespaces - Add your AWS Key and Secret to the Codespaces Secrets in Github
- Using Locally - Add a mount in your devcontainer(after customizatoins) to your local .aws/credentials file

    	"mounts": [
            "source=/Users/briansheridan/.aws/credentials,target=/home/node/.aws/credentials,type=bind,consistency=cached"
	    ],