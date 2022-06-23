# devops-test-drive
This repository is used to evaluate DevOps engineer candidates

## Setup
Please clone this repository.  

Create a branch that mirrors your name.  

Once you are done with your code changes please submit a PR!  

Good luck!

## Requirements

### Code
Using the [PokeAPI](https://pokeapi.co/) create a list of Pokemon and each of their moves. ie: 
`{"Bulbasaur": ["razor-wind", "swords-dance"]}`
Upload this list to the AWS SSM Parameter store.

### Infra
Now that you have code, create a repository for it's artifact using your choice of IaC tool.
Decide on how you will run this code in the context of an AWS service/s.  
ie: ECR repo to push your container image to so your code can run on ECS/Lambda.

### DevOps
Create a CICD configuration file (yaml or similar) that will: 
* build and package your code.
* deploy your artifact to AWS.
