# AWS_Portfolio-Rabin

Descriptive Analysis

Project Description: Descriptive Analysis of Awarded Bids in Vancouver

Project Title: Understanding Bidding Trends and Awarded Contracts in the City of Vancouver

Objective:
The goal of this project is to analyze bidding and awarded contract data for the City of Vancouver to identify trends, track financial distribution, and evaluate procurement patterns. Through descriptive statistics and SQL-based querying in AWS Athena, the city can gain insights into bid amounts, award rates, and procurement trends.

Dataset:

The dataset consists of awarded contract data and contains the following key attributes:
•	Bid Number: Unique identifier for each bid
•	Bid Amount: Proposed price for each bid
•	Award Status: Whether the bid was accepted or rejected
•	Year: Year in which the bid was placed
•	Vendor: Name of the awarded vendor
•	Contract Amount: Total awarded contract value

Methodology:

1.	Data Ingestion:
o	Raw data was collected from CSV files.
o	The data was uploaded to an AWS S3 bucket for storage and further processing.

3.	Data Analysis:
o	Used AWS Athena SQL queries to extract relevant data.
o	Computed the average bid amount per year.
o	Calculated the total awarded bid value per year.

4.	Data Summarization & Reporting:
o	Filtered and cleaned data for accurate analysis.
o	Extracted key insights regarding financial distribution and bid patterns.


Data Wrangling

Project Description: Data Wrangling for Improved Bidding Analytics in Vancouver

Project Title: Cleaning and Structuring Bidding Data for Effective Analysis

Objective:
To clean and transform raw bidding data stored in AWS S3 to ensure accuracy, consistency, and completeness for meaningful analysis.

Methodology:

1.	Data Ingestion:
o	Created an AWS S3 bucket for structured data storage.
o	Uploaded raw CSV data to a structured folder system.

3.	Data Profiling:
o	Used AWS Glue DataBrew to detect missing values and inconsistencies.
o	Identified 3% missing values in the dataset.

5.	Data Cleaning:
o	Used AWS Glue to remove missing values and standardize data.
o	Ensured bid amount data types were consistent.

7.	Data Cataloging:
o	Created an AWS Glue Crawler to scan and organize data.
o	Automated table creation for easy querying.

9.	Data Storage:
o	Stored cleaned and processed data in a curated AWS S3 bucket.
o	Ensured accessibility for further analysis in AWS Athena.


Data Quality Control

Project Description: Ensuring High-Quality Bidding Data for Analysis

Project Title: Data Quality Control for City of Vancouver’s Procurement System

Objective:
To implement security, governance, and monitoring mechanisms for improving data integrity and reliability.

Methodology:
1.	Data Security:
o	Created an AWS Key Management Service (KMS) encryption key.
o	Applied encryption to all AWS S3 storage buckets.
o	Enabled bucket versioning for data backup and recovery.

3.	Data Governance:
o	Used AWS Glue visual ETL for quality checks.
o	Ensured awarded column completeness was >99%.
o	Verified uniqueness of bid numbers >80%.
o	Ensured bid data freshness was <1500 days.
o	Stored failed quality check data separately from approved data.

5.	Data Monitoring:
o	Used AWS CloudWatch to monitor S3 bucket size and Glue job performance.
o	Set alerts for threshold breaches to optimize storage.

Tools and Technologies:
•	Storage & Processing: AWS S3, AWS Glue, AWS Athena
•	Security: AWS Key Management Service (KMS), S3 encryption, bucket versioning
•	Data Governance: AWS Glue DataBrew, AWS Glue visual ETL
•	Monitoring: AWS CloudWatch
•	Data Analysis & Querying: SQL, AWS Athena


Deliverables:
•	A descriptive analysis report of awarded bids.
•	A cleaned and structured dataset for querying and reporting.
•	A data quality control framework to ensure high data integrity and accuracy, like schema validation, data completedness, uniqueness check, etc.
•	Visual metric to monitor and analyze procurement trends.
•	A presentation summarizing findings and recommendations.

Conclusion:
By implementing a structured Data Analytics Platform, the City of Vancouver can enhance decision-making, ensure transparency in procurement, and improve financial oversight. This comprehensive approach integrates descriptive analysis, data wrangling, and data quality control to provide a robust foundation for data-driven governance.

