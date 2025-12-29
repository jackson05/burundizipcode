# Burundi Administrative Divisions (SQL Dataset)

## Overview
The repository offers an SQL dataset of the administrative areas of Burundi, which is kept in one table for the purpose of simplicity and easy integration.

The full admin hierarchy Provincia, Commune, Zone, and Hill (Colline) is included in the dataset and meant for developers, researchers, and data analysts who require structured location data for Burundi without the hassle of complex table relationships.

## ZIP / Postal Codes
Burundi does not use ZIP or postal codes. Instead, all addressing is reliant on administrative divisions, with which this dataset strictly aligns.

## Administrative Coverage
Each row in the table represents a complete administrative path and contains:

- Province  
- Commune  
- Zone  
- Hill (Colline)

This flat structure makes the data easy to query, filter, and use in real-world applications.

## Database Compatibility
The SQL file is compatible with:

- MySQL  
- MariaDB  

It can be imported directly without modification.

## Table Structure
The dataset is stored in a single table containing all administrative levels.

### Example Columns
- province  
- commune  
- zone  
- hill  

All related location information is stored in one record.

## Getting Started

### Requirements
- MySQL or MariaDB
- Any SQL client (MySQL Workbench, phpMyAdmin, DBeaver, etc.) for UI

### Import Instructions using the CLI
Create a database:
```sql
CREATE DATABASE yourDatabaseName;
USE yourDatabaseName;
```

Import the SQL file:
```bash
SOURCE burundizipcode.sql
```
## Frequent Application Scenarios

-Forms for address and location selection

-Validation and normalization of data

-Analysis by geography or demographics

-Projects in education and research

-Applications that need Burundi governmental data

## Data Accuracy

The data reflects officially recognized administrative divisions of Burundi.
