# Data-Eng-LAB-6
Transform Data Using Spark in Synapse Analytics

Transform Data Using Spark in Synapse Analytics

This repository contains screenshots and related files from the "Transform data using Spark in
Synapse Analytics" lab exercise provided by Microsoft Learn.

Objective of the Lab

The goal of this lab is to demonstrate how data engineers can use Apache Spark within Azure
Synapse Analytics to perform large-scale data transformations using ETL (Extract, Transform, Load)
or ELT (Extract, Load, Transform) processes. The lab showcases how to transform semi-structured
data files into structured formats that are ready for analysis.
Lab Steps
1. Provisioning Azure Synapse Resources
- Using Azure Cloud Shell (PowerShell), the official DP-203 GitHub repository was cloned.
- The setup.ps1 script was executed to automatically deploy the required Azure resources, including
a Synapse workspace, Data Lake Storage account, and a Spark pool.
2. Exploring Synapse Studio
- Opened Synapse Studio and verified that all components were provisioned correctly.
- Navigated through the Data hub to locate the files container in the linked Data Lake Storage.
- Previewed the .csv files containing annual sales data under the data folder.
3. Working with Spark Notebook
- Downloaded the Spark Transform.ipynb notebook from the GitHub repository.
- Imported the notebook into Synapse Studio under the Develop section.
- Attached the notebook to the provisioned Spark pool and executed each cell.
- Used PySpark and Spark SQL to:
 - Load CSV files into DataFrames
 - Perform transformations
 - Clean and format the data
 - Run analytical queries
4. Clean Up Resources
- After completing the exercise, all created Azure resources were deleted through the Azure portal to
avoid incurring unnecessary charges.

Technologies Used

- Microsoft Azure Synapse Analytics
- Apache Spark & Spark SQL
- Azure Data Lake Storage Gen2
- Azure Cloud Shell (PowerShell)
- Jupyter Notebooks (.ipynb)
- 
Repository Contents

- screenshots/ - Screenshots taken throughout the lab
- Spark Transform.ipynb - The Spark notebook used during the lab
- README.md - This file
  
Duration

The lab takes approximately 30 to 40 minutes to complete. Initial resource provisioning and Spark
pool startup might take some time.

Resources

- Microsoft Learn - DP-203 GitHub Repository:
https://github.com/MicrosoftLearning/dp-203-azure-data-engineer
- Apache Spark in Synapse Analytics - Core Concepts:
https://learn.microsoft.com/azure/synapse-analytics/spark/apache-spark-concepts
