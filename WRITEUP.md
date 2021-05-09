### Cost

|                            Azure VM                            |                     Azure App Service
| -------------------------------------------------------------- |:---------------------------------------------------------------:| 
| Running a Linux VM on Standard Tier for a month costs US$85.46 | Running a Linux based App Service for a month costs US$13.14    | 
| An Azure VM has a pay as you go compute option                 | An Azure App Service doesn't have a pay as you go compute option| 

### Scalability
|                            Azure VM                            |                     Azure App Service
| -------------------------------------------------------------- |:---------------------------------------------------------------:| 
| You can scale out to as many as 30 instances, depending on your|  Scale sets support up to 1,000 VM instances. If you create and | 
| pricing tier. App Service Environments in Isolated tier        | upload your own custom VM images, the limit is 600 VM instances.| 
| further increases your scale-out count to 100 instances.  

### Availabilty
|                            Azure VM                            |                     Azure App Service
| -------------------------------------------------------------- |:-----------------------------------------------------------------:| 
| For all Virtual Machines that have two or more instances       |  Apps running in a customer subscription will be available 99.95% | 
| deployed across two or more Availability Zones in the same     |  of the time. No SLA is provided for Apps under either the Free or| 
| Azure region, It is guarantee you will have Virtual Machine    |  Shared tiers.
| Connectivity to at least one instance at least 99.99% of       |
| the time.														 |


### Workflow
|                            Azure VM                            |                     Azure App Service
| -------------------------------------------------------------- |:-----------------------------------------------------------------:| 
| Creating a workflow from for an Azure VM is long and not       |  You literally don't have todo anything when setting up your      | 
| really easy to do.                                             |  workflow, it's easy and fast                                     | 


### Choice
My choice for the CMS app is deploying the app with Azure App Service because of lesser costs and managerial efforts.

### App changes that would change your decision
If in the future I want to scale my app for a larger audience, I will consider redeploying my app with Azure VM, or if I want to support certain languages that are not supported on Azure App service, but is supported on Azure VM, I will definitely re-deploy with Azure VM. 

