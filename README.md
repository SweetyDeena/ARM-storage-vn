Using this template, storage account and virtual network can be deployed.

->To deploy a template, sign in to either the Azure CLI or Azure PowerShell

     az login
     
->Create a resource group

     az group create --name resourceGroupName --location "North Europe"
     
->Deploy template

     az deployment group create --name DeployLocalTemplate --resource-group $resourceGroupName --template-file <PATH-TO-storage-vnetwork.JSON> --parameters <PATH-TO-storage-vnetwork.PARAMETERS.JSON> 
  
