# Enterprise Bridge Data Pipelines
Enterprise bridge data automation suite using FME, Python, SQL, and ArcGIS to support infrastructure reporting, web publishing, and statewide planning.


# Bridge Division FME Automation Suite

## Overview

This repository contains FME workspaces, automation workflows, documentation, and supporting resources used to support Bridge Division data integration, GIS publishing, reporting, and compliance processes.

The projects in this repository automate the movement and transformation of bridge inspection, inventory, follow-up action, and SNBI-related data between AssetWise, enterprise databases, ArcGIS Enterprise, ArcGIS Portal, and reporting applications.

## Objectives

- Reduce manual data processing
- Improve data consistency across systems
- Support GIS publishing and visualization
- Automate recurring bridge business processes
- Improve reporting and compliance tracking
- Provide maintainable workflows and documentation

## Technologies

- FME Workbench
- FME Flow
- ArcGIS Enterprise
- ArcGIS Portal
- SQL Server
- Python
- AssetWise
- Enterprise Geodatabases
- Tableau

## Featured Projects

### Follow-Up Actions (FUA)

Publishes Bridge Division Follow-Up Action (FUA) records from AssetWise to ArcGIS Enterprise and Portal datasets.

- Categorizes actions by status and urgency
- Identifies overdue actions
- Creates GIS-ready features
- Supports dashboard reporting and mapping

➡️ [View Project](https://github.com/eckoecho/Infrastructure-Asset-Management-ytics-Suite/tree/main/Follow%20Up%20Actions/readme.md)

---

### BRG_DIV_FUA_SNBI_TO_PORTAL

Publishes SNBI and related bridge information for GIS visualization and reporting.

- Extracts bridge inventory data
- Standardizes attributes
- Generates GIS layers
- Supports Portal and dashboard applications

➡️ [View Project](BRG_TXDOT_BRIDGES_SNBI_UPDATE)

---

### GIS Publishing Workflows

Automated processes that publish and synchronize Bridge Division GIS datasets for enterprise consumption.

Key capabilities include:

- Data extraction
- Attribute transformation
- Schema standardization
- Spatial processing
- Feature service updates
- Portal publishing
