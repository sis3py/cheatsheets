# Azure Fundamentals (AZ900)

## What is Cloud Computing

Service delivery model over the internet (cloud):

- **compute power** meaning servers such as windows, linux, hosting environments, etc.
- **storage** like files and/or databases
- **networking **in azure but also outside when connecting to your company network
- **analytics** services for visualization and telemetry data

### Main concepts

- **scalability**: scale = allocate and deallocate resources at any time
- **elasticity**: scale dynamically
- **agility **: scale quickly
- **fault tolerance**: maintain system uptime while physical and service component failures happen
- **disaster recovery**: process and design principle which allows a system to recovers from natural or human induced disasters
- **high availability**: agreed level of operational uptime for the system.
availability = uptime/(uptime + downtime)

## Capital Expenditure (CapEx)  vs Operational Expenditure (OpEx)
Differences between Capital Expenditure and Operational Expenditure

|   |Capital Expenditure|Operational Expenditure |
| ------------ | ------------ | ------------ |
| Up front cost|Significant|None|
| Ongoing cost|Low | Based on usage |
| Tax Deduction| Over time | Same year |
| Early Termination| No| Anytime|
| Maintenance|Significant |Low |
| Value over time |Lowers  | No change|

## What is a consumption-based model?

Customers are only charged based on their resource usage.

-  **No associated** upfront cost
-  **No wasted resources**
- **Pay for what you need**
- **Stop paying when you dont use**

Consumption is the virtual metric used to calculate how much each resource (service) in Azure was used.

## IaaS vs PaaS vs SaaS

**As a service** = which party will manage the particular layer and all the layers below.

- **Software**: application code and data
- **Platform**:  supporting software + operating system required to host the application
- **Infrastructure**:  hardware the infrastructure and virtualization required to host the platform

|  Layer | Layer  |
| ------------ | ------------ |
| Application  | Software  |
|Data   |  Software |
| Runtime  |   Platform|
|  Middleware |  Platform |
|  Operating System |   Platform|
|  Virtualization |   Infrastructure|
|  Servers |   Infrastructure|
|  Networking |   Infrastructure|
|   Storage|  Infrastructure |

### Responsibility Matrix
|   Layer|  On-Premises |  IaaS |  PaaS | SaaS  |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| Application  |  You |  You |  You |  Cloud provider |
| Data  |  You |  You |   You|  Cloud provider |
|   Runtime|   You|  You | Cloud provider  |Cloud provider   |
|  Middleware |   You|   You| Cloud provider | Cloud provider  |
|  Operating System |  You |  You |  Cloud provider | Cloud provider  |
|  Virtualization |  You |  Cloud provider |   Cloud provider|  Cloud provider |
|  Servers | You  | Cloud provider  | Cloud provider  | Cloud provider  |
|  Networking | You  |  Cloud provider |   Cloud provider|   Cloud provider|
|   Storage|  You |  Cloud provider |   Cloud provider|  Cloud provider | 

## Cloud Deployment Model

|  Layer | Cloud Provider |  Own Datacenter | 
| ------------ | ------------ | ------------ |
| Public  | ✔  |   |
| Hybrid  | ✔  | ✔  |
| Private  |   | ✔  |

### Public Cloud

- Everything runs on cloud provider hardware
- No local hardware
- Some services share hardware with other customers

✔ No CapEx (No initial investment)
✔ High Availability
✔ Agility
✔ Pay as you Go (PAYG) pricing
✔ No hardware maintenance
✔ No deep technical skills required

× Not all security and compliance policies can be met
× No ownership over the physical infrastructure
× Rare specific scenarios can’t be done

### Private Cloud

- Everything runs on your own datacenter
- Self-service should be provided
- You maintain the hardware

✔ Can support any scenario
✔ Total control over security and infrastructure
✔ Can meet any security and compliance policy

× Initial investment is required (CapEx)
× Limited agility constrained by server capacity and team skills
× Very dependent on IT skills & expertise

### Hybrid Cloud

Combines both Public & Private cloud

✔ Great flexibility
✔  You can run any legacy apps in private cloud
✔  Can utilize existing infrastructure
✔  Meet any security& compliance requirements
✔ Can take advantage of all public cloud benefits

× Can be more expensive
× Complicated to manage due to larger landscape
× Most dependent on IT skills & expertise from all three models

## Data Center

### Region
- Geographical area on the planet
- Datacenter(s) connected with low-latency network (<2 milliseconds)
- Location for your services
- Some **services are available only **in certain regions
- Some **services are global services** ( not assigned/deployed in specific region)
- **50**+ regions available
- Special government regions (US DoD Central, US Gov Virginia, etc.)
- Special partnered regions (China East, China North)

### Availability Zone
- **Regional** feature
- **Grouping** of physically separate facilities
- Designed to **protect from data center failures**
- If zone goes down **others continue working**
- 2 service categories
	- **Zonal** services (Virtual Machines, Disks, etc.)
	- **Zone-redundant** services (SQL, Storage, etc.)
- **Not all regions** are supported
- Supported region has** 3 or more zones**
- A **zone is 1** or more data centers

### Region Pair

- Each **region is paired** with another region making it a region pair
- **Region pairs are static and cannot be chosen**
- Each pair resides **within the same geography** (exception is Brazil South)
- **Physical isolation** with at least 300 miles distance (when possible)
- Some services have **platform-provided replication**
- **Planned updates** across the pairs
-** Data residency** maintained for disaster recovery
- ex: East US vs West US, North Europe (Ireland) vs West Europe (Netherlands), ...

### Geographies
- Discrete market
- Typically contains** 2 or more regions**
- Ensures **data residency, sovereignty, resiliency, and compliance requirements** are met
- **Fault tolerant** to protect from region wide failures
- Broken up into **areas**
	- Americas
	- Europe
	- Asia Pacific
	- Middle East and Africa
- Each region belongs** only to one Geography**

## Resources

### Azure resources

- Object used to **manage services** in Azure
- Represents **service lifecycle**
- Saved as **JSON** definition

###  Resource Groups
- **Grouping** of resources
- Holds **logically** related resources
- Typically organizing by
	- **Type**
	- **Lifecycle** (app, environment)
	- **Department**
	- **Billing**,
	- **Location**
	- combination of those

### Resource Manager
- **Management Layer **for all resources and resource groups
- **Unified language**
- **Controls** access and resources

### Main concepts

- 1 resource must be in **one, and only one** resource group
- Resource groups have their **own location **assigned
- Resources in the resource groups can reside** in a different locations**
- Resources **can be moved between** the resource groups
- Resource groups **cannot be nested**
- Organize based on your organization (billing, security and access management, application lifecycle, ...)


## Azure Compute services

#### Virtual Machines (IaaS)
Custom software, custom requirements, very specialized, high degree of control

#### VM Scale Sets (IaaS) 
Auto-scaled workloads for VMs

#### Container Instances (PaaS)
Simple container hosting, easy to start

#### Kubernetes Service (PaaS)
Highly scalable and customizable container hosting platform

#### App Services (PaaS)
Web applications, a lot of enterprise web  hosting features, easy to start

#### Functions (PaaS) (Function as a Service) (Serverless) 
Micro/nano-services, excellent consumption-based pricing, easy to start

## Azure Networking Services

### Azure Networking
- Connect cloud and on-premises
- On-premise networking functionality

### Azure Virtual Network
- Logically isolated networking components
- Segmented into one or more subnets
- Subnets are discrete sections
- Enable communication of resources with each-other, internet and on-premises
- Scoped to a single region
- VNet peering allow cross region communication
- Isolation, Segmentation, Communication, Filtering, Routing

### Azure Load Balancer
- Even traffic distribution
- Supports both inbound and outbound scenarios
- High-availability scenarios
- Both TCP (transmission control protocol) and UDP (user datagram protocol) applications
- Internal and External traffic
- Port Forwarding
- High scale with up to millions of flows

### VPN Gateway
- Specific type of virtual network gateway for on-premises to azure traffic over the public internet

### Application Gateway
- Web traffic load balancer
- Web application firewall
- Redirection
- Session affinity
- URL Routing
- SSL termination

### Content Delivery Network
- Define content
- Minimize latency
- POP (points of presence) with many locations

## Azure Storage Services

### Data Types
- **Structured** - Data that can be represented using tables with very strict schema. Each row must follow defined schema. Some tables have defined relationships between them. Typically used in relational databases.
- **Semi-structured** - Data that can be represented using tables but without strict defined schema. Rows must only have unique key identifier.
- **Unstructured **- Any files in any format. Like binary files, application files, images, movies, etc.

### Storage Account
- Group of services which include
	- blob storage,
	- queue storage,
	- table storage, and
	- file storage
- Used to store
	- files,
	- messages
	- semi-structured data
- Highly scalable (up to petabytes of data)
- Highly durable (99.999999999% - 11 nines, up to 16 nines)
- Cheapest per GB storage

### Blob Storage

- BLOB – binary large object – file
- Designed for storage of files of any kind
- 3 storage tiers
	- Hot – frequently accessed data
	- Cool – infrequently accessed data (lower availability, high durability)
	- Archive – rarely (if-ever) accessed data

### Queue Storage
- Storage for small pieces of data (messages)
- Designed for scalable asynchronous processing

### Table Storage
- Storage for semi-structured data (NoSQL)
- No need for foreign joins, foreign keys, relationships or strict schema
- Designed for fast access
- Many programming interfaces and SDKs

### File Storage
- Storage for files accessed via shared drive protocols
- Designed to extend on-premise file shares or implement lift-and-shift scenarios

### Disk Storage
- Disk emulation in the cloud
- Persistent storage for Virtual Machines
- Different sizes, types (SSD, HDD), performance tiers
- Disk can be unmanaged or managed

## Azure Database Services

### Cosmos DB
- Globally distributed NoSQL (semi-structured data) Database service
- Schema-less
- Multiple APIs (SQL, MongoDB, Cassandra, Gremlin, Table Storage)
- Designed for Highly responsive (real time) applications with super low latency responses <10ms or Multi-regional applications

### SQL Database
- Relational database service in the cloud (PaaS) (DBaaS - Database as a Service)
- Structured data service defined using schema and relationships
- Rich Query Capabilities (SQL)
- High-performance, reliable, fully managed and secure database for building - applications

### Azure SQL product family
**Azure SQL Database** – Reliable relational database based on SQL Server
**Azure Database for MySQL** – Azure SQL version for MySQL database engine
**Azure Database for PostgreSQL **– Azure SQL version for PostgreSQL database engine
**Azure SQL Managed Instance **– Fully fledged SQL Server managed by cloud provider
**Azure SQL on VM **– Fully fledged SQL Server on IaaS
**Azure SQL DW (Synapse)** – Massively Parallel Processing (MPP) version of SQL Server

## Azure Marketplace
- "Azure Shop" where you purchase services and solutions for the Azure platform
- Each product is a template which contains one or multiple services
- Products are delivered by first and third-party vendors
- Solutions can leverage all service categories like IaaS, PaaS and SaaS

## Azure Internet of Things

Internet of Things (IoT) is a network of internet connected devices (IoT Devices) embedded in everyday objects enabling sending and receiving data such as settings and telemetry.

### Azure Iot Hub
- Managed service for bi-directional communication
- Platform as a Service (PaaS)
- Highly secure, scalable and reliable
- Integrates with a lot of Azure Services
- Programmable SDKs for popular languages (C, C#, Java, Python, Node.js)
- Multiple protocols (HTTPS, AMQP, MQTT)

### Azure IoT Central
- IoT App Platform - Software as a Service (SaaS)
- Industry specific app templates
- No deep technical knowledge required
- Service for connecting, management and monitoring IoT devices
- Highly secure, scalable and reliable
- Built on top of the IoT Hub service and 30+ other services

### Azure Sphere
- Secure end-2-end IoT Solutions
- Azure Sphere certified chips (microcontroller units - MCUs)
- Azure Sphere OS based on Linux
- Azure Security Service trusted device-to-cloud communication

## Azure Big Data Services

Big Data is a field of technology that helps with the extraction, processing and analysis of information that is too large or complex to be dealt with by traditional software.

### The 3Vs rule
Big data typically has one of the following characteristics:

- **Velocity **- how fast the data is coming in or how fast we are processing it
	- Batch
	- Periodic
	- Near Real Time
	- Real Time
	- **Volume** - how much data we are processing
	- Megabytes
	- Gigabyte
	- Terabytes
	- Petabytes
- **Variety** - how structured/complex the data is
- Tables
- Databases
- Photo, Audio
- Video, Social Media

### Azure Synapse Analytics
- Big data analytics platform (PaaS)
- Multiple components
	- Spark
	- Synapse SQL
	- SQL pools (dedicated – pay for provisioned performance)
	- SQL on-demand (ad-hoc – pay for TB processed)
	- Synapse Pipelines (Data Factory – ETL)
	- Studio (unified experience)

### Azure HDInsight
- Flexible multi-purpose big data platform (PaaS)
- Multiple technologies supported (Hadoop, Spark, Kafka, HBase, Hive, Storm, Machine Learning)

### Azure Databricks
- Big data collaboration platform (PaaS)
- Unified workspace for notebook, cluster, data, access management and collaboration
- Based on Apache Spark
- Integrates very well with common Azure data services

## Azure Machine Learning
- Cloud-based platform for creating, managing and publishing machine learning models
- Platform as a Service (PaaS)
- Machine Learning Workspace – top level resource
- Machine Learning Studio – web portal for end-2-end development
- Features
	- Notebooks – using Python and R
	- Automated ML – run multiple algorithms/parameters combinations, choose the best model
	- Designer – graphical interface for no-code development
	- Data & Compute – management of storage and compute resources
	- Pipelines – orchestrate model training, deployment and management tasks

## Azure Serverless Computing

Serverless computing is cloud-hosted execution environment that allows customers to run their applications in the cloud while completely abstracting underlying infrastructure.

### Azure Functions
- Serverless coding platform (Functions as a Service, FaaS)
- Designed for nano-service architectures and event-based applications
- Scales up and down very quickly
- Highly scalable
- Supports popular languages and frameworks (.NET & .NET Core, Java, Node.js, Python, PowerShell, etc.)

### Azure Logic Apps
- Serverless enterprise integration service (PaaS)
- 200+ connectors for popular services
- Designed for orchestration of business processes, integration workflows for applications, data, systems and services
- No-code solution

### Azure Event Grid
- Fully managed serverless event routing service
- Uses publish-subscribe model
- Designed for event-based and near-real time applications
- Supports dozen of built-in events from most common Azure services

## Azure DevOps

DevOps aims to shorten the development life cycle by providing continuous integration and delivery (CI/CD) capabilities while ensuring high quality of deliverables.

- Collection of services for building solutions using DevOps practices
- Services included
	- **Boards** – tracking work
	- **Pipelines** – building CI/CD workflows (build, test and deploy apps)
	- **Repos** – code collaboration and versioning with Git
	-** Test Plans** – manual and exploratory testing
	- **Artifacts** – manage project deliverables
- Extensible with Marketplace – over 1000 of available apps
- Evolved from TFS (Team Foundation Server), through VSTS (Visual Studio Team Services)

### Azure DevTest Labs
- Service for creation of sandbox environments for developers/testers (PaaS)
- Quick setup of self-managed virtual machines
- Preconfigured templates for VMs
- Plenty of additional artifacts (tools, apps, custom actions)
- Lab policies (quotas, sizes, auto-shutdowns)
- Share and automate labs via custom images
- Premade plugins/API/tools for CI/CD pipeline automation

## Azure Management Tools

### Azure Portal
- Public web-based interface for management of Azure platform
- Designed for self-service
- Customizable
- Simple tasks

### Azure PowerShell
- PowerShell and module
- Designed for automation
- Multi-platform with PowerShell Core
- Simple to use
	- Connect-AzAccount – log into Azure
	- Get-AzResourceGroup – list resource groups
	- New-AzResourceGroup – create new resource group
	- New-AzVm – create virtual machine

### Azure CLI
- Command Line Interface for Azure
- Designed for automation
- Multi-platform (Python)
- Simple to use
	- az login – log into Azure
	- az group list – list resource groups
	- az group create – create new resource group
	- az vm create – create virtual machine
- Native OS terminal scripting

### Azure Cloud Shell
- Cloud-based scripting environment
- Completely free
- Supports both Azure PowerShell and Azure CLI
- Dozen of additional tools
- Multiple client interfaces
	- Azure Portal integration (portal.azure.com)
	- Shell Portal (shell.azure.com)
	- Visual Studio Code Extension
	- Windows Terminal
	- Azure Mobile App
	- Microsoft Docs integration

## Azure Advisor

- Personalized consultant service
- Designed to provide recommendations and best practices for
	- Cost (SKU sizes, idle services, reserved instances, etc.)
	- Security (MFA settings, vulnerability settings, agent installations, etc.)
	- Reliability (redundancy settings, soft delete on blobs, etc.)
	- Performance (SKU sizes, SDK versions, IO throttling, etc.)
	- Operational Excellence (service health, subscription limits, etc.)
- Actionable recommendations
- Free
