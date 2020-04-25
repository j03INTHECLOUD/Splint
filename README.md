# Splint
Orchestrator for fixing Azure Resource Deployments:
This project will consist of an orchestrtor to allow the use of ARM templates and az cli script to allow the automated deployment of Azure Infrastructure.

### Main Idea:
- Allow ARM tmeplate to create the base infrastructure
- Use ARM output to be use by az cli script to configure the infrastructure
- Have a base set of templates and configuration scripts
- Allow to users to bring there own templates and az cli scripts
- build a mainfest system to order deployments
- have the pipline run on a container
