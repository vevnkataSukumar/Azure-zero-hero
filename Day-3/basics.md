
# Azure Resources

Azure resources are the building blocks of your cloud infrastructure in Microsoft Azure. These resources can be virtual machines, databases, storage accounts, or any other service offered by Azure. Each resource is a manageable item in Azure, and they are provisioned and managed individually.

## Resource Groups in Azure

A **Resource Group** in Azure is a logical container for resources that share the same lifecycle, permissions, and policies. It helps you organize and manage related Azure resources efficiently. Resources within a group can be deployed, updated, and deleted together as a single management unit.

### Key Points about Resource Groups:

- **Lifecycle Management:** Resources within a group can be managed collectively, making it easy to handle deployments, updates, and deletions.

- **Resource Organization:** Grouping resources based on projects, environments, or applications helps keep your Azure environment well-organized.

- **Role-Based Access Control (RBAC):** Permissions and access control are applied at the resource group level, allowing you to manage who can access and modify resources within a group.

## Azure Resource Manager (ARM) Overview

**Azure Resource Manager (ARM)** is the deployment and management service for Azure. It provides a consistent management layer that enables you to deploy resources with declarative templates. ARM templates describe the resources you need and their configurations, allowing you to deploy and update resources in a predictable manner.

### Key Features of Azure Resource Manager:

- **Template-Based Deployment:** ARM uses JSON templates to define the infrastructure and configuration of your Azure resources. This enables repeatable and consistent deployments.

- **Dependency Management:** ARM automatically handles dependencies between resources, ensuring they are deployed in the correct order.

- **Rollback and Roll-forward:** In case of deployment failures, ARM can automatically roll back changes to maintain the desired state, or roll forward to the last known good state.

- **Tagging and Categorization:** You can use tags to label and categorize resources, making it easier to manage and organize your Azure environment.

**Note:** Understanding Azure resources, resource groups, and Azure Resource Manager is fundamental to effectively utilize and manage your resources in the Azure cloud.

### Steps to create Virtual machine:

- Under Microsoft Service go to Virtual Machine Servie(VM)
- On the VM page Click Create to crete new VM
- On Click on Create will land on page where we need to fill the VM details
- Add resouce name and Resource group if already Created
- If not created Resouce Group Please floow steps to create new in Resource group creation Section
- Select the Specifications, Availability Zones, Size of the Machine etc
- Add names for SSH like name, Key etc.
- Please r3eview once feel Ok please click Review and Create
- Then Azure will review and validate and lands on review page
- this review page will have VM details and Costing etc
- The click on creat, this will take around 30 Sec based on network and etc
- After the successful creation Can be seen under VM service listing
- Can also be see under resources group
- Onclick on VM can see the details and files regaring VM, Key value pair, Virtual network, .nsg and IPetc.
- If you want to control access regarding the VM you can add control based in the role assigned to user

### Steps to create Resouce Group:

- In the side menu of Azure board you can see Resouce group
- Click on resource group and will land on resoiurces group page where you can see list of resource groups created if not it will be a balnk page
- In Order to create new Resouce Group. Click create 
- mention the Group name and nearest availability region.
- Click review and crete, after review automatically thr RG can be created and can be see under listing.
- That's it You have successfully created RG 

