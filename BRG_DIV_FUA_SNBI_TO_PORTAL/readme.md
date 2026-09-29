<img width="1482" height="587" alt="image" src="https://github.com/user-attachments/assets/b1e71e1f-2c29-4329-93af-0f14bde2bdd3" />


# BRG DIV FUA SNBI TO PORTAL

## Overview

BRG_DIV_FUA_SNBI_TO_PORTAL is an FME workflow that [publishes Bridge Division Follow-Up Action (FUA) records from AssetWise to ArcGIS Enterprise and Portal datasets](https://github.com/eckoecho/Infrastructure-Asset-Management-Compliance-Analytics-Suite/tree/main/Follow%20Up%20Actions). The process transforms bridge follow-up action data into GIS-ready features that support operational tracking, reporting, and visualization across Bridge Division applications.

## Purpose

Publish Follow-Up Action (FUA) records from AssetWise to Bridge Division GIS and Portal datasets.

## Key Responsibilities

- Extract Follow-Up Action records from AssetWise
- Categorize actions by status and urgency
- Identify overdue follow-up actions requiring attention
- Identify approved plans and completed review workflows
- Join bridge inventory and structure information
- Generate spatial point features for mapping
- Project geometry into the required ArcGIS coordinate system
- Standardize and format output attributes for enterprise GIS consumption
- Publish authoritative GIS datasets for downstream applications

## Processing Workflow

1. Read Follow-Up Action (FUA) records from AssetWise
2. Categorize FUAs by status and urgency
3. Identify overdue actions
4. Identify approved plans
5. Join bridge inventory information
6. Create GIS point geometry
7. Project geometry into the ArcGIS coordinate system
8. Standardize output attributes
9. Publish results to Bridge Division GIS and Portal datasets

## Business Function

Provides the authoritative GIS layer used for:

- Follow-Up Action mapping
- Bridge Division dashboard reporting
- ArcGIS Portal visualization
- Operational tracking of bridge inspection recommendations
- Monitoring overdue corrective actions
- Enterprise GIS reporting and analysis

## Technologies

- SQL Queries
- FME Workbench
- ArcGIS Enterprise
- ArcGIS Portal
- AssetWise
- Enterprise Geodatabases
- Attribute joins and spatial transformations
- GIS data publishing workflows

## Outcomes

- Automated synchronization between AssetWise and GIS systems
- Consistent reporting of Follow-Up Action status
- Improved visibility into overdue actions
- Standardized enterprise GIS datasets
- Reduced manual data maintenance
