# Relational Database Design & Power BI Advanced Analytics Pipeline

## Project Overview
This project delivers an end-to-end data platform prototype, spanning from conceptual data modeling to advanced server-side data engineering and interactive Business Intelligence (BI) reporting. The system simulates a real-world enterprise infrastructure designed to capture operational transactions, enforce strict business constraints, and serve analytical insights for decision-makers.

The architecture combines a highly optimized relational backend (SQL Server) with a dynamic executive analytics layer (Power BI).

---

## Technical Architecture & Core Modules

### 1. Relational Database Design & Optimization (SQL Server)
* **Data Modeling & 3NF Compliance:** Designed a comprehensive Entity-Relationship Diagram (ERD) and mapped it into a normalized relational schema satisfying Third Normal Form (3NF) constraints to reduce redundancy and eliminate anomalies.
* **Advanced Server-Side Logic:** Programmed production-ready **Stored Procedures** to execute automated data transactions and parameterized actions efficiently within server memory.
* **Automated Business Rules:** Implemented complex **Database Triggers** that monitor write/update operations to execute continuous status updates and cascade computations dynamically.
* **Analytical Queries:** Crafted optimization scripts utilizing nested **Common Table Expressions (CTEs)** and advanced analytic **Window Functions** to conduct deep performance mapping and bottleneck tracking.

### 2. Business Intelligence & Reporting Layer (Power BI)
* **Data Ingestion & ETL:** Extracted operational data rows directly from the relational database server tables into Power BI.
* **Semantic Data Modeling:** Configured optimal star-schema relationships between dimension and fact data objects to support fast analytical processing.
* **Interactive Executive Dashboards:** Developed functional visualizations and dynamic corporate reports to display operational trends, distribution metrics, and strategic performance indicators.

---

## Repository Structure
* **`SQL`**: The full database compilation script containing table structures (DDL), primary/foreign key mappings, stored procedures, triggers, and verification scripts.
* **`POWER BI`**: The standalone Power BI Desktop analytics module housing the complete layout of semantic data relationships and dashboards.
* **`README.md`**: Corporate technical brief and operational guide.

---

## How to Review & Run
1. **Database Layer:** Open and execute the `SQL` script layout inside an empty Microsoft SQL Server Management Studio (SSMS) context to instantly construct the synchronized table infrastructure and deploy server objects.
2. **Analytics Layer:** Download and open the `POWER BI` file using *Power BI Desktop* to explore the underlying star-schema mapping and interact with the executive data charts.
