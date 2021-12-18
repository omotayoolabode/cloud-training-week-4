# Lab 2: Build and store container images with Azure Container Registry

1. Deploy Azure Container Registry: to create a new registry i ran the following code. "az acr create --resource-group Tayo --name Tayor--sku Premium". i used an existing resource group named Tayo 
2. Build container images with Azure Container Registry Tasks
3. Deploy images from Azure Container Registry: to do this i obtained the i.p address of the container by running "az container show --resource-group  tayo --name tayor --query ipAddress.ip --output table ". i then signed in using the i.p address
4. Replicate a container image to different Azure regions

### Notes:

Build and store container images with Azure Container Registry
* https://docs.microsoft.com/en-us/learn/modules/build-and-store-container-images/
