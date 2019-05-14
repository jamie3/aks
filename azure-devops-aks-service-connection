These are the steps to run when setting up a new AKS service connection in Azure Dev Ops.

```
az account set --subscription 72912757-e834-436b-866c-b5d62eb3dc54

az aks get-credentials --resource-group alpha-aks-nonprod-rg --name alpha-aks-nonprod-cluster

kubectl get serviceaccounts

kubectl get serviceaccounts default -o yaml

kubectl get secret default-token-9vd7r -o yaml	
```

Get API endpoint from portal. (eg. https://aksname.hcp.westus2.azmk8s.io)

Copy the token and secret into the Azure DevOps AKS service principal connection window, including the API endpoint.
