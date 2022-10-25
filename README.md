# django_aks_cluster

Exercise: Deploy containerized Django application through Azure Kubernetes Service (AKS)
- Kubernetes container orchestration 
- syntax practice 
- "kubectl, create deployment, expose, apply" commands


## Azure services Used 
- Resource group (django-apps)
- Kubernetes cluster (djangocluster)
- Azure container registry (fegdjangoregistry)
- Login server string (fegdjangoregistry.azurecr.io/)


# Topics
    - Built Docker image locally 
    - Pushed Docker image to Azure container registry 
    - Created Postgres server on Azure cloud 
    - Connected database server to AKS cluster 
    - Updated kubernetes yml file 
    - Deployed application to AKS cluster
    - Ran migrations
    - POST request sent to the database 
    - Made sure to Delete resource group and all resources from Azure Portal related to this project
