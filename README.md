---

# UEFA 2020 Football Data Dashboard

This project showcases a Power BI dashboard created using UEFA 2020 football data. The process involved data cleaning, transformation, and modeling across SQL Server Management Studio (SSMS), SQL Server Analysis Services (SSAS), and a Data Vault 2.0 schema, which culminated in an interactive dashboard in Power BI.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Cleaning and Transformation](#data-cleaning-and-transformation)
- [Data Vault 2.0 Design](#data-vault-20-design)
- [Data Mart Creation](#data-mart-creation)
- [Power BI Dashboard](#power-bi-dashboard)
- [Getting Started](#getting-started)
- [Files and Documentation](#files-and-documentation)

## Project Overview

This project uses UEFA 2020 football data to build a business intelligence (BI) solution. The process involved:
1. **Data Cleaning**: SQL scripts in SSMS.
2. **Data Modeling**: Data Vault 2.0 schema in SSMS and Power BI.
3. **Dashboarding**: Interactive visualizations in Power BI.

## Data Cleaning and Transformation

The data received in an Excel format was cleaned and transformed in SQL using SSMS:
- **Loading Procedures**: Initial data loading procedures created in SSMS.
- **Data Cleansing**: Removed inconsistencies and formatted data for uniformity.

## Data Vault 2.0 Design

The data is structured according to the Data Vault 2.0 methodology, which includes:
- **Hubs**: Storing unique business keys.
- **Satellites**: Storing descriptive data.
- **Links**: Creating relationships between hubs.

Visual representations of the Data Vault schema are available in the PowerPoint presentation in this repository.

## Data Mart Creation

A data mart was created to aggregate and organize the cleaned data for visualization. Then the data from the mart, was taken into Power Bi, by connecting to the server locally. 

## Power BI Dashboard

The Power BI dashboard provides:
- **Insights** into UEFA 2020 data.
- **Custom Measures**: Created for in-depth analysis.
- **Visualization Features**: Interactive charts and filters for user exploration.

## Files and Documentation

- `SQL_Scripts/`: Contains SQL code for data cleaning and transformations.
- `DataVault_Schema.pptx`: PowerPoint file with schema design.
- `PowerBI_Dashboard.pbix`: Power BI file with dashboard visualizations.
---
