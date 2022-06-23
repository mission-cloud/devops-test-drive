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

### Infra
Now that you have code and can build it, create a repository for it's artifact ie: container image in ECR.

### DevOps
Create a CICD configuration file (yaml or similar) that will: 
* build and package your code.
* deploy your artifact to AWS.
