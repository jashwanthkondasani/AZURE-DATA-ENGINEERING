 # Introduction to Microsoft Azure

## Definition

Microsoft Azure is a cloud computing platform that provides services like compute, storage, databases, networking, analytics, AI, and security.

## Azure Global Infrastructure

Azure infrastructure consists of:

- Data Centers
- Regions
- Availability Zones
- Region Pairs
- Edge Locations


## Azure Region

A geographical location containing one or more data centers.

Benefits:
- Low latency
- Data compliance
- Disaster recovery


## Availability Zone

Separate data centers inside a region.

Benefits:
- High availability
- Fault tolerance


## Region Pair

Two Azure regions connected for disaster recovery.


## Azure Hierarchy

Tenant
 |
Management Groups
 |
Subscriptions
 |
Resource Groups
 |
Resources


## Resource Group

Container used to organize Azure resources.


## Data Engineering Architecture

Data Sources
↓
Azure Data Factory
↓
Azure Data Lake Storage Gen2
↓
Azure Databricks
↓
Azure Synapse Analytics
↓
Power BI


# Azure Global Infrastructure

## Components

1. Data Centers
2. Regions
3. Availability Zones
4. Region Pairs
5. Edge Locations


## Data Center

Physical facility containing servers, storage and networking equipment.


## Region

Geographical location containing Azure data centers.

Purpose:
- Low latency
- Compliance
- Cost optimization


## Availability Zone

Separate data centers inside a region.

Purpose:
- High availability
- Fault tolerance


## Region Pair

Two Azure regions connected for disaster recovery.


## Edge Location

Locations closer to users for faster content delivery.


## Data Engineering Example

Data Sources
      |
Azure Data Factory
      |
ADLS Gen2
      |
Databricks
      |
Synapse
      |
Power BI