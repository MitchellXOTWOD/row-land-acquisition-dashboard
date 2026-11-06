# Right-of-Way Land Acquisition & Title Analytics Dashboard

An executive-level operational dashboard designed to track land acquisition lifecycles, parcel statuses, linear Right-of-Way (ROW) footage, and agent productivity. Built to solve real-world land management bottlenecks by bridging the gap between raw data ingestion and executive reporting.

## Key Features & Architectural Highlights

- **Star Schema Data Model:** Built upon a clean relational star schema separating core entities (Parcels, Projects, Clients, Agents), ensuring high query performance and accurate measure evaluation.
- **Dual-Metric Scope Tracking:** Simultaneously tracks discrete operational units (Parcel Counts) alongside linear infrastructure footprints (ROW Length in Feet).
- **Streamlined UI/UX Design:** Features header-less aesthetics, custom conditional color-coding for status hierarchies (Acquired, Contacted, Verbal, In Progress), and dynamic metadata sidebars.
- **Automated Data Pipelines:** Backed by automated ingestion scripts (utilizing AWS Lambda, Amazon S3, and REST APIs) to maintain real-time synchronization between field databases and executive reporting.

## Dashboard Preview

*(Insert screenshots or exported PDF exports of your main dashboard pages here)*

## Tech Stack & Skills Demonstrated

- **BI & Visualization:** Power BI Desktop, Custom Formatting, Interactive Filtering
- **Data Modeling:** Relational Star Schema, Dimensional Modeling, Relationship Optimization
- **Cloud & Automation:** AWS Lambda, Amazon S3, REST API Integration, Windows Task Scheduler
- **Domain Tools:** ArcGIS Integration, Smartsheet Data Management, SQL Server Management Studio (SSMS)

## Core Business Metrics Tracked

1. **Parcel Acquisition Status:** Breakdown of parcels by active status (Contacted, Verbal, Acquired, Not Contacted).
2. **Title Clearance Milestones:** Monitoring title status workflows independently from acquisition status.
3. **Linear Infrastructure Scope:** Tracking total Right-of-Way length (ft) relative to project progress.
4. **Agent Performance & Productivity:** Granular tracking of individual acquisition and title agent metrics relative to total project volume.

Author
Mitchell Nielsen
