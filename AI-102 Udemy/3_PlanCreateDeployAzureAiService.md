# Plan, create and deploy an Azure AI service

## Responsible AI principles

## Create an Azure AI resource

We have the option between multi-service accounts and individual service accounts.

If we just want one resource, just choose the single resource.

![alt text](image-23.png)

![alt text](image-26.png)

![alt text](image-24.png)

![alt text](image-25.png)

![alt text](image-27.png)

![alt text](image-28.png)

## Default endpoint for an Azure AI service

![alt text](image-29.png)

![alt text](image-30.png)

We also need to pass the Secret Keys with the endpoint. The idea of having two keys if in case of compromising one of them, regenerate it and meanwhile use the other.

![alt text](image-31.png)

## Azure AI CI/CD

![alt text](image-32.png)

![alt text](image-33.png)

![alt text](image-34.png)

If the new model does not improve on the old error rate, stop. If it does, deploy and replace the old one!

## Azure AI Services container deployment

You may not want to operate in the cloud for compliance, security or performance concerns.

![alt text](image-35.png)

**We can deploy SOME services On-Prem with containers. Also, some containers support offline use.**You need to ask permission to Microsoft for this.

![alt text](image-36.png)

![alt text](image-37.png)

![alt text](image-38.png)

![alt text](image-39.png)

![alt text](image-40.png)
