# Deploy an Azure Kubernetes Service (AKS) cluster using an ARM template

## 1. Before you begin
* To create an AKS cluster using an ARM template, you   provide an SSH public key

 * From Azure CLI >>> az login
 * Create an SSH key pair:
### Create an SSH key pair using Azure CLI
>>> az sshkey create --name "mySSHKey" --resource-group "myResourceGroup"

### &

### Create an SSH key pair using ssh-keygen
>>> ssh-keygen -t rsa -b 4096

## 2. Create deployment file-template (json)

## 3. Deploy from azure portal custom deployment agent.


Ref:
https://learn.microsoft.com/en-us/azure/aks/learn/quick-kubernetes-deploy-rm-template?tabs=azure-cli 