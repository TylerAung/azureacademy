Welcome to the Azure labs.

These are hands-on resources to help you learn Azure.

## Pre-reqs

 - Create an Azure account
 - [Set up the AZ command line, Git and Docker](./setup/README.md) 
 - Download your repo
    - Open a terminal (PowerShell on Windows; any shell on Linux/macOS) 
    - Run: `git clone https://github.com/courselabs/azure.git`
     - Open the folder: `cd azure`
- _Optional_
    - Install [Visual Studio Code](https://code.visualstudio.com) (free - Windows, macOS and Linux) to browse the repo and documentation

## Azure Quickstart

_Resource Groups and Virtual Machines_

- [Signing In](/labs/signin/README.md)
- [Regions and Resource Groups](/labs/resourcegroups/README.md)
- [Virtual Machines](/labs/vm/README.md)
- [VMs as Linux Web servers](/labs/vm-web/README.md)
- [VMs as Windows dev machines](/labs/vm-win/README.md)
- [Automating VM configuration](/labs/vm-config/README.md)

_SQL Databases and ARM_

- [SQL Server](/labs/sql/README.md)
- [SQL Server VMs](/labs/sql-vm/README.md)
- [Deploying database schemas](/labs/sql-schema/README.md)
- [Automation with ARM](/labs/arm/README.md)
- [Automation with Bicep](/labs/arm-bicep/README.md)

_App Deployment with IaaS_

- [IaaS app deployment](/labs/iaas-apps/README.md)
- [Automating IaaS app deployment](/labs/iaas-bicep/README.md)
- [Creating and using VM images](/labs/vm-image/README.md)
- [Scaling with VM Scale Sets](/labs/vmss-win/README.md)
- [Provisiong Scale Sets with cloud-init](/labs/vmss-linux/README.md)

_App Service_

- [App Service for web applications](/labs/appservice/README.md)
- [App Service for static web apps](/labs/appservice-static/README.md)
- [App Service for distributed apps](/labs/appservice-api/README.md)
- [App Service configuration and administration](/labs/appservice-config/README.md)
- [App Service CI/CD](/labs/appservice-cicd/README.md)

_Project_

- Project 1

## Storage and Communication

_Storage Accounts_

- New storage account, explore redundancy, security & performance
- Create and manage blob storage, use with simple consumer app
- Create and manage Azure files, use with SMB client
- Using storage for static web content
- Working with table storage

_Cosmos DB_

- New Cosmos DB, explore API types, throughput & redundancy
- Create and manage Cosmos SQL DB, use with Entity Framework consumer app
- Create and manage Mongo DB type, use with simple consumer app
- Indexes and performance for Mongo Cosmos DB
- Working with data using Data Explorer notebooks 

_KeyVault and Virtual Networks_

- [KeyVault](/labs/keyvault/README.md)
- [Networking](/labs/vnet/README.md)
- Create Keyvault in VNet, use to store credentials for SQL
- Understand options for accessing KeyVault
- Deploy app service app in VNet, using KeyVault to fetch SQL creds

_Events and Messages_

- New Service Bus, explore tiers & access
- Create Service Bus, use pub-sub with simple consumer apps
- New Event Hubs, explore throughput & access
- Create Event Hubs, publish and conume with partitions
- Using Redis - messaging and caching

_Project_

- Project 2_

## Compute and Containers

_Docker and Azure Container Instances_

- Containers, networking & compute environment
- Building images
- Running containers with ACI
- Multi-container apps with Compose
- Compose integration with ACI

_Kubernetes_

- Clusters, nodes & Kubectl
- YAML specs, Pods, Services and Deployments
- App configuration with ConfigMaps and Secrets
- Storage with PersistentVolumes
- Securing access with RBAC

Day 3:

- Routing traffic with Ingress
- Securing traffic with Cert-manager
- Monitoring with Prometheus & Grafana
- Logging with Elasticsearch, Fluentd and Kibana
- Multi-node clusters and app placement

_Azure Kubernetes Service_

- New AKS cluster, explore sizing, node pools & add-ons
- Create cluster with AppGW ingress & ACR integration
- Explore storage classes - Disk & Files
- Enable KeyVault add-on for sensitive config
- Scale & upgrade existing cluster

_Project_

- Project 3

- [ACR Images](/labs/acr/README.md)
- [Azure Container Instances](/labs/aci/README.md)
- [Azure Kubernetes Service](/labs/aks/README.md)
- [Storage and Configuration](/labs/storage/README.md)
- [Ingress and Application Gateway](/labs/ingress/README.md)

## Serverless and App Management

Day 1:

- New Funcion app, explore runtimes & plans, publish method
- Create Function running Docker container, with HTTP trigger
- Update Function with new image in ACR
- Create Function with code, using blob storage trigger
- Deploying from VS Code using Deployment Slots

Day 2:

- Exploring triggers - Cosmos DB, Service Bus, Event Grid
- Managing and deploying Functions with AZ CLI
- Exploring bindings - Cosmos DB, Blob Storage, Event Hubs
- Modelling stateful workflows with Durable Functions
- Long-running async tasks in Durable Functions


Day 3: 

- New APIM, explore tiers, identity and protocols
- Create APIM with AZ CLI, explore gateway & devloper portal
- APIGW functionality - SSL, authentication, caching, compression
- Using policies for control flow & data transform
- Using CDN & comparing with APIGW


Day 4: 

- Instrumentation in code with App Insights
- Using Azure Monitor with App Insights and Container Insights
- Distributed tracing & Application Map
- Centralized log collection & Log Analytics
- Configuring alerts and notifications

_Project_

- Project 4

#### Credits

Created by [@EltonStoneman](https://twitter.com/EltonStoneman) ([sixeyed](https://github.com/sixeyed)): Freelance Consultant and Trainer. Author of [Learn Docker in a Month of Lunches](https://www.manning.com/books/learn-docker-in-a-month-of-lunches), [Learn Kubernetes in a Month of Lunches](https://www.manning.com/books/learn-kubernetes-in-a-month-of-lunches) and [many Pluralsight courses](https://pluralsight.pxf.io/c/1197078/424552/7490?u=https%3A%2F%2Fwww.pluralsight.com%2Fauthors%2Felton-stoneman).


Photo by <a href="https://unsplash.com/@_bahador?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Bahador</a> on <a href="https://unsplash.com/s/photos/cloud?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  