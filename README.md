AWS + Snowflake + Power BI Project

📌 Project Overview

    This project demonstrates an end-to-end data pipeline that integrates cloud storage, cloud data warehousing, and business intelligence. Using Amazon S3, Snowflake, and Power BI, we ingest raw data, transform it using SQL, and visualize insights through a structured Power BI report. The use case focuses on rainfall data analysis, providing practical exposure to data engineering and reporting workflows.

⸻

🛠 Tech Stack

	    	Cloud Storage: Amazon S3
	     
	    	Data Warehouse: Snowflake
	     
	    	Data Transformation: Snowflake SQL
	     
	    	Business Intelligence: Microsoft Power BI
	     
	    	Programming Language: SQL
	     
	    	Integration Protocols: IAM Role-Based Access, External Stage in Snowflake

⸻

🎯 Project Objectives

    		Set up an S3 bucket to store rainfall data files.
     
    		Load and stage this data into Snowflake.
     
    		Perform SQL-based data transformation and cleansing.
     
    		Design and publish a Power BI report that analyzes rainfall patterns.
     
		Demonstrate cloud-based analytics with a full workflow from raw data to insights.

⸻

📂 Project Workflow

1. Cloud Setup and Data Ingestion
   
		Creating Amazon S3 Bucket & Loading Data into it (3 min)

Created a bucket and uploaded the rainfall dataset.

		Creating the IAM Role (2 min)
 
A role with policies was created to grant Snowflake access to S3 securely.

		Creating the Integration Object & Updating the Trust Policy (5 min)
 
Configured external integration in Snowflake and updated the AWS trust policy to allow Snowflake access.

		Loading Data into Snowflake (3 min)
 
Used Snowflake’s COPY INTO command from an external stage to load data.

⸻

2. Data Understanding and Transformation
   
		Understanding the Data (9 min)

Explored dataset structure including columns, datatypes, and missing values.

		Data Transformation using Snowflake SQL (13 min)
 
Cleaned and transformed the data with Snowflake SQL. Tasks included:

    		Handling missing values
     
    		Renaming columns
     
    		Formatting date fields
     
    		Creating analytical columns
     
    		Adding Rainfall Groups Column (8 min)
     
Introduced a derived column to classify rainfall into categories like Light, Moderate, Heavy, etc., based on thresholds.

⸻

3. Reporting in Power BI
   
		Importing Data into Power BI from Snowflake (4 min)

Connected Power BI to Snowflake using built-in connectors and imported the cleaned table.

		Adding Rainfall Analysis Page in the Power BI Report (13 min)
 
Built charts and visuals for:
    		Monthly/Yearly rainfall trends
     
    		Rainfall category distribution
     
    		Regional rainfall comparison
     
    		Adding Other Pages to the Power BI Report (9 min)
     
Enhanced the report with additional visualizations like:

    		Filters and slicers for drill-down
     
    		Maps showing geospatial data (if applicable)
     
    		KPI cards and summary metrics
     
    		Publishing the Report to Power BI Service (1 min)
     
Published the report to Power BI Service for sharing and dashboard embedding.

⸻

📊 Sample Visuals

    		Bar and Line Charts for Rainfall Over Time
     
    		Pie Charts for Rainfall Group Distribution
     
    		Map Visuals for Regional Rainfall (if location data present)
     
    		KPI Cards showing max, min, and average rainfall

⸻

✅ Key Learnings

    		How to securely integrate AWS and Snowflake
     
    		Efficiently load and transform large datasets using SQL
     
    		Data modeling for BI tools
     
    		Report building in Power BI for cloud-hosted data sources
     
    		Creating interactive dashboards for stakeholders
