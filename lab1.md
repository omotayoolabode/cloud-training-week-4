# Lab 1: Deploy a container instance in Azure using the Azure CLI

1. Create a resource group: To do this, i used a existing resource group named "tayo"
2. Create a container: This was done using docker, a Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application. to create a container, i ran "az acr create -n <Tayor> -g DockerRG --sku Standard --admin-enabled true"
3. Pull the container logs: This is done in order to troubeshoot. i ran the "az container logs --Tayo --Tayor" command
4. Attach output streams: to attach the local standard out and standard error streams to that of the container, i ran,
5. Clean up resources: this is the process of removing containers once it has been used. to do this the following code was run "az container delete --tayo --Tayor"

### Notes:

Quickstart: Deploy a container instance in Azure using the Azure CLI
* https://docs.microsoft.com/en-us/azure/container-instances/container-instances-quickstart