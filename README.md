# ODI Cricket Data Engineering Project Using Snowflake

This project provides a comprehensive end-to-end data engineering solution for One Day International (ODI) cricket data using Snowflake. It covers initial design considerations, data flow, database layer architecture, and more.

## Table of Contents

- [Project Overview](#project-overview)
- [Design Considerations](#design-considerations)
- [Data Flow](#data-flow)
- [File and Script Descriptions](#file-and-script-descriptions)
- [Learning Outcomes](#Learning-Outcomes)



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

## Learning Outcomes

Upon completing this end-to-end real-time Snowflake-based data engineering project (ETL/ELT), you will gain proficiency in the following areas:

- **Data Loading**: 
  - Loading data from a local machine to Snowflake stage locations, handling both small JSON files and multiple files simultaneously.
  - Loading delta data sets from a local machine to internal stages.

- **Querying Stage Files**: 
  - Utilizing the `$ notation` to query stage files.

- **Data Transformation**: 
  - Executing the `COPY` command to load JSON files into tables.

- **Database Design**: 
  - Designing different layers and fact/dimension tables to support robust data models.

- **Automation**: 
  - Automating data flow using Snowflake's `TASK` and `TASK TREE` features.

- **Dashboard Creation**: 
  - Building quick and insightful dashboards using Snowsight.



