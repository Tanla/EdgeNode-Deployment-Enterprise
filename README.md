# ARM Template - Enterprise Edge Node

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FTanla%2FEdgeNode-Deployment-Enterprise%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="https://aka.ms/deploytoazurebutton"/>
</a>

This sample template creates following Azure components and its dependencies.

1. Azure AKS Instance.
2. Virtual network, Subnet, Network Security Group.
3. Event Hub
4. Log Analytics workspace

Create a resource group with below command

PS> New-AzureRmResourceGroup -Name <Resource-Group-Name> -Location <Azure-Region>
    
E.g. New-AzureRmResourceGroup -Name Prod-Entrp-SI-RG-AKS-XYZ-01 -Location "South India"

The purpose of this template is to deploy AKS cluster with all of dependent resources.
