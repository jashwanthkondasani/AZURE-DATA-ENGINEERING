# Cloud Computing Fundamentals - Quick Revision Notes

## 1. What is Cloud Computing?

Cloud Computing is the delivery of computing services over the internet.

It provides:

- Compute
- Storage
- Databases
- Networking
- Security
- Analytics
- AI Services

Examples:
- Microsoft Azure
- AWS
- Google Cloud Platform


---

# 2. Traditional Data Center vs Cloud

## Traditional Data Center

Company manages:

- Physical servers
- Hardware
- Networking
- Maintenance
- Security

Problems:

- High cost
- Limited scalability
- Hardware management


## Cloud Computing

Cloud provider manages:

- Infrastructure
- Hardware
- Maintenance
- Data centers

Benefits:

- Pay as you use
- Easy scaling
- Fast deployment
- Global availability


---

# 3. Benefits of Cloud Computing

## Cost Efficiency

- No upfront hardware investment
- Pay only for used resources


## Scalability

Ability to increase or decrease resources based on demand.


Example:

Normal traffic:
10 servers

Peak traffic:
100 servers


## Availability

Ensures applications remain available using multiple data centers.


## Reliability

Provides:

- Backup
- Replication
- Disaster recovery


## Global Access

Resources can be accessed from anywhere through internet.


---

# 4. Cloud Deployment Models

## Public Cloud

Infrastructure owned by cloud providers.

Examples:

- Azure
- AWS
- Google Cloud

Features:

- Shared resources
- Low cost
- Highly scalable


## Private Cloud

Cloud infrastructure dedicated to one organization.

Used by:

- Banks
- Government organizations

Features:

- High security
- More control


## Hybrid Cloud

Combination of public and private cloud.

Example:

Sensitive data → Private Cloud

Applications → Public Cloud


---

# 5. Cloud Service Models

## IaaS (Infrastructure as a Service)

Provides basic infrastructure.

User manages:

- Applications
- Data
- Operating System


Examples:

- Azure Virtual Machines
- AWS EC2


Use:

Creating and managing servers.


---

## PaaS (Platform as a Service)

Provides a ready platform for application development.

Cloud manages:

- Hardware
- OS
- Runtime


Examples:

- Azure App Service
- Azure Functions


Use:

Develop applications without managing servers.


---

## SaaS (Software as a Service)

Complete software delivered through internet.

Examples:

- Gmail
- Microsoft 365
- Salesforce


Use:

Directly use applications.


---

# 6. IaaS vs PaaS vs SaaS


IaaS:

Infrastructure + User manages software


PaaS:

Platform + Developer manages application


SaaS:

Complete software + User only uses application



---

# 7. Cloud Characteristics

## On-Demand Self Service

Users can create resources whenever required.


## Broad Network Access

Services are available through internet.


## Resource Pooling

Cloud providers share resources among customers.


## Rapid Elasticity

Resources automatically scale based on demand.


## Measured Service

Users pay according to usage.


---

# 8. Virtualization

Virtualization creates multiple virtual machines from one physical server.


Example:


Physical Server

        |
        |
----------------
VM 1  VM 2  VM 3
Linux Windows Linux


Benefits:

- Better resource utilization
- Cost reduction
- Easy management


---

# 9. Region and Availability Zone


## Region

A geographical location containing cloud data centers.


Examples:

- East US
- Central India
- West Europe


## Availability Zone

Independent data centers inside a region.


Purpose:

- High availability
- Fault tolerance


Example:


Region

 |
 |--- AZ 1
 |
 |--- AZ 2
 |
 |--- AZ 3


---

# 10. Scalability vs Elasticity


## Scalability

Increasing or decreasing resources manually.


Example:

Increase database capacity.


## Elasticity

Automatically adjusting resources based on demand.


Example:

Website automatically adds servers during high traffic.


---

# 11. Cloud Security


## Shared Responsibility Model


Cloud Provider Responsible:

- Physical infrastructure
- Hardware
- Data centers
- Network


Customer Responsible:

- User access
- Data protection
- Passwords
- Applications


---

# 12. Networking Basics


## IP Address

Unique address used to identify devices.


## Virtual Network

Private network inside cloud.

Azure:
Virtual Network (VNet)


## Firewall

Controls network traffic.


## Load Balancer

Distributes traffic across multiple servers.


Example:


Users

 |

Load Balancer

 |

Servers


---

# 13. Storage Concepts


## Object Storage

Stores files and objects.

Examples:

- Azure Blob Storage
- AWS S3


Used for:

- Images
- Videos
- Logs
- Data Lake


## File Storage

Shared file system.


## Block Storage

Storage attached to virtual machines.


---

# 14. Disaster Recovery

Process of recovering systems after failures.


Methods:

- Backup
- Replication
- Multiple regions
- Availability zones


---

# 15. Cloud in Data Engineering


Modern Data Engineering uses cloud services:


Data Sources

        |

Azure Data Factory

        |

Azure Data Lake Storage Gen2

        |

Azure Databricks

        |

Azure Synapse Analytics

        |

Power BI


---

# Important Azure Services


Compute:
- Virtual Machines


Storage:
- Azure Blob Storage
- Azure Data Lake Storage Gen2


Database:
- Azure SQL Database


ETL:
- Azure Data Factory


Big Data:
- Azure Databricks


Data Warehouse:
- Azure Synapse Analytics


Security:
- Microsoft Entra ID


Monitoring:
- Azure Monitor


---

# Quick Interview Revision


Q: What is Cloud Computing?

A:
Cloud computing provides computing resources over the internet on demand.


Q: What are cloud deployment models?

A:
Public, Private, Hybrid Cloud.


Q: What are cloud service models?

A:
IaaS, PaaS, SaaS.


Q: Difference between scalability and elasticity?

A:
Scalability increases resources, elasticity automatically adjusts resources.


Q: What is an Availability Zone?

A:
Independent data center inside a region used for high availability.


Q: What is virtualization?

A:
Technology that creates multiple virtual machines on one physical server.


---

# Final Summary

Cloud Computing =

Internet-based computing resources

        |

Deployment Models

Public | Private | Hybrid

        |

Service Models

IaaS | PaaS | SaaS

        |

Core Concepts

Scalability
Availability
Security
Virtualization
Storage

        |

Azure Data Engineering

ADF
ADLS Gen2
Databricks
Synapse
Power BI