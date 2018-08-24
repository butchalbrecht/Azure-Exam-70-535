# Azure-Exam-70-535
## Design Compute Infrastructure (20-25%)
### Design solutions using virtual machines (VMs)
- Design VM deployments by leveraging availability sets, fault domains, and update domains in Azure
- Use [Web App for Containers](WebAppForContainers.md)
- design VM Scale Sets
- design for compute-intensive tasks using [Azure Batch](Batch.md) and Azure Batch AI
- define a migration strategy from cloud services
- determine when to use reserved instances
- design for VMs in a DevTest Lab environment (including formulas, images, artifacts, claiming and un-claiming VMs)
- determine when to use Accelerated Networking
- recommend use of Azure Backup and Azure Site Recovery including support for Linux in Azure Backup and integrating Azure Backup in the VM creation process
- recommend when to use availability zones
### Design solutions for serverless computing
- Use Azure Functions to implement event-driven actions
- design data storage solutions for serverless computing
- design for serverless computing using Azure Container Instances
- design application solutions by using Azure Logic Apps, Azure Functions, or both
- determine when to use API management service
- design event routing solutions using Azure Event Grid
- design solutions that integrate stream processing and bot messaging
### Design microservices-based solutions 

### Design web applications

### Create compute-intensive applications

## Design Data Implementation (15-20%)
### Design for Azure Storage solutions
Determine when to use:
- Azure Blob Storage
- blob tiers (hot, cool, archive)
- Azure Files
- disks
- Azure Data Box
- Azure Storage Service Encryption
- Azure StorSimple
### Design for Azure Data Services
### Design for relational database storage
- Determine when to use Azure SQL Database and SQL Server Stretch Database
- design for scalability and features
- determine when to use Azure Database for MySQL and Azure Database for PostgreSQL
- design for HA/DR, geo-replication
- design a backup and recovery strategy
- design optimization strategies for Azure SQL Data Warehouse columnar storage
### Design for NoSQL storage
### Design for CosmosDB storage
## Design Networking Implementation (15-20%)
### Design Azure virtual networks
- Design solutions that use Azure networking services: design for load balancing using Azure Load Balancer and Azure Traffic Manager; - define DNS, DHCP, and IP strategies; 
- determine when to use Azure Application Gateway; 
- determine when to use virtual network (VNet) service endpoints; 
- determine when to use multi-node application gateways, Traffic Manager and load balancers
### Design external connectivity for Azure Virtual Networks
Determine when to use Azure VPN, Azure ExpressRoute and Virtual Network Peering architecture and design; determine when to use User Defined Routes (UDRs); determine when to use VPN gateway site-to-site failover for ExpressRoute; determine when to use the Container Networking Interface (CNI) plugin; design solutions that use Global VNet Peering
### Design security strategies
Determine when to use network virtual appliances; design a perimeter network (DMZ); determine when to use a Web Application Firewall (WAF), Network Security Group (NSG), and virtual network service tunneling; organize resources by designing solutions that use service tags
### Design connectivity for hybrid applications
Design connectivity to on-premises data from Azure applications using Azure Relay Service, Azure Data Management Gateway for Data Factory, Azure On-Premises Data Gateway, Hybrid Connections, or Azure Web App’s virtual private network (VPN) capability; identify constraints for connectivity with VPN; identify options for joining VMs to domains
## Design Security and Identity Solutions (20-25%)
### Design an identity solution
Design AD Connect synchronization; design federated identities using Active Directory Federation Services (AD FS); design solutions for Multi-Factor Authentication (MFA); design an architecture using Active Directory on-premises and Azure Active Directory (AAD); determine when to use Azure AD Domain Services; design security for Mobile Apps using AAD
### Secure resources by using identity providers
Design solutions that use external or consumer identity providers such as Microsoft account, Facebook, Google, and Yahoo; determine when to use Azure AD B2C and Azure AD B2B; design mobile apps using AAD B2C or AAD B2B
### Design a data security solution
Design data security solutions for Azure services; determine when to use Azure Storage encryption, Azure Disk Encryption, Azure SQL Database security capabilities, and Azure Key Vault; design for protecting secrets in ARM templates using Azure Key Vault; design for protecting application secrets using Azure Key Vault; design a solution for managing certificates using Azure Key Vault; design solutions that use Azure AD Managed Service Identity
### Design a mechanism of governance and policies for administering Azure resources
Determine when to use Azure RBAC standard roles and custom roles; define an Azure RBAC strategy; determine when to use Azure resource policies; determine when to use Azure AD Privileged Identity Management; design solutions that use Azure AD Managed Service Identity; determine when to use HSM-backed keys
### Manage security risks by using an appropriate security solution
Identify, assess, and mitigate security risks by using Azure Security Center, Operations Management Suite Security and Audit solutions, and other services; determine when to use Azure AD Identity Protection; determine when to use Advanced Threat Detection; determine an appropriate endpoint protection strategy
## Design Solutions by using Platform Services (10-15%)
## Design for Operations (10-15%)
