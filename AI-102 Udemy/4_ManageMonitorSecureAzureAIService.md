# Manage, monitor, and secure an Azure AI Service

## Configure diagnostic logging

![alt text](image-41.png)

![alt text](image-42.png)

![alt text](image-43.png)

## Monitor an Azure AI resource

![alt text](image-44.png)

![alt text](image-45.png)

![alt text](image-46.png)

![alt text](image-47.png)

KQL -> Kusto Query Language is the language used for queries on the logs.

![alt text](image-48.png)

![alt text](image-49.png)

## Manage costs for Azure AI services

![alt text](image-50.png)

![alt text](image-51.png)

![alt text](image-52.png)

![alt text](image-53.png)

![alt text](image-54.png)

## Manage account keys

![alt text](image-56.png)

![alt text](image-57.png)

## Protect account keys by using Azure Key Vault

![alt text](image-58.png)

The code could get leaked!

![alt text](image-59.png)

![alt text](image-60.png)

![alt text](image-61.png)

![alt text](image-62.png)

## Retrieve secret from Azure Key Vault

![alt text](image-63.png)

To use the Azure Key Vault:

![alt text](image-64.png)

## Manage private communications

![alt text](image-65.png)

![alt text](image-66.png)

![alt text](image-67.png)

![alt text](image-68.png)

**We would expose the service to only that virtaul network. We can also allow ourselves from the internet, IP ranges outside of the dafult for access.**

![alt text](image-69.png)

We can also disable it:

![alt text](image-70.png)

With private endpoints, we can connect to the vnet with authorization instead of depending on the key where anyone can access. The endpoint needs approval.

![alt text](image-71.png)
