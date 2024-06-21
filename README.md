# ODI Cricket Data Engineering Project Using Snowflake

Welcome to the comprehensive end-to-end data engineering solution for One Day International (ODI) cricket data using Snowflake. This project covers everything from initial design considerations to the intricacies of data flow, database layer architecture, and more.

## Table of Contents

- [Project Overview](#project-overview)
- [Design Considerations](#design-considerations)
- [Data Flow](#data-flow)
- [File and Script Descriptions](#file-and-script-descriptions)
- [Getting Started](#getting-started)
- [Sample Data and SQL Scripts](#sample-data-and-sql-scripts)
- [Database Architecture](#database-architecture)
- [Automation and Dashboard](#automation-and-dashboard)
- [Additional Resources](#additional-resources)

## Project Overview

This project demonstrates a complete end-to-end data engineering pipeline using Snowflake, specifically focusing on ODI cricket data. It includes data loading, curation, transformation, and the design of database layers and tables.

## Design Considerations

Key decisions made during this project include:

- **Data Modeling**: Designing efficient and scalable data models.
- **Project Architecture**: Ensuring a robust and maintainable architecture.
- **Data Quality and Integrity**: Implementing mechanisms to ensure the accuracy and reliability of the data.
- **Performance Optimization**: Leveraging Snowflake's features to enhance processing efficiency.

## Data Flow

- **Data Loading**: Loading data from a local machine to Snowflake stage locations, handling both small JSON files and multiple files simultaneously.
- **Data Transformation**: Using Snowflake's features to transform raw data into meaningful insights.
- **Data Quality**: Ensuring data quality and integrity throughout the process.
- **Data Enhancement**: Utilizing Snowflake to enhance data processing efficiency.

## File and Script Descriptions

This section provides an overview of the files and scripts included in this repository, explaining their purpose within the project.

### Latest Commit

- **README.md**: The latest update to the project's documentation.

### Schema and Table Scripts

- **Creating Database & Schema**: Script to create the necessary databases and schemas.
- **Raw Layer Schema SQL Scripts**: Scripts to define the raw layer schema, where raw data is initially loaded.
- **Clean Layer Constraints SQL Scripts**: Scripts to set up constraints for tables in the clean layer.

### Dimension Tables

- **Date & Referee Dimension**: Script to create and update the Date and Referee dimension tables.
- **Team & Player Dimension**: Script to create the Team and Player dimension tables.
- **Venue & Match Dimension**: Script to create the Venue and Match dimension tables.

### Fact Tables

- **Delivery Fact Table Scripts**: Scripts to create the Delivery fact table, which stores detailed delivery-level data.
- **Match Fact Table DDL Scripts**: Scripts to create the Match fact table, storing high-level match data.

### Data Population Scripts

- **Date Dim Data Population Script**: Script to populate data into the Date dimension table.
- **Fact Table Data Population Script**: Script to populate data into the fact tables.

### Clean Tables

- **Delivery Clean Table**: Script to create the clean version of the Delivery table.
- **Match Clean Table**: Script to create the clean version of the Match table.
- **Player Clean Table**: Script to create the clean version of the Player table.

### Stage and File Format

- **Stage & File Format SQL Scripts**: Scripts to define stages and file formats for data loading.

### Data File

- **ODI.json**: Sample JSON data file containing ODI cricket data.

## Getting Started

To get started with this project, you will need:

- A Snowflake account.
- Basic knowledge of SQL and data engineering principles.
- The sample JSON data file and SQL scripts provided in this repository.

### Steps:

1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/your-repository/odi-cricket-snowflake.git
