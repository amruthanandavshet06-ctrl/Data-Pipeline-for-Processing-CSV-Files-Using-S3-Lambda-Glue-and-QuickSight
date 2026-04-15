# Data Pipeline for Processing CSV Files Using S3 Lambda Glue and QuickSight
  
# Project Overview

1.You upload CSV files to an S3 bucket (raw data).

2.This upload automatically triggers a Lambda function.

3.Lambda cleans and prepares the data, then saves it in another bucket (processed data).

4.Next, AWS Glue further processes (ETL) the data.

5.The final cleaned data is stored in a final bucket.

6.Finally, QuickSight is used to create dashboards and reports to view the data.


# SERVICES USED

Amazon S3 → Stores your files (raw and processed data)

AWS Lambda → Automatically runs code when a file is uploaded (cleans data)

AWS Glue → Further processes and organizes the data (ETL)

Amazon QuickSight → Shows data in dashboards and charts

IAM Roles & Policies → Controls who can access what (security)


# ARCHITECTURE DIAGRAM 
<img width="757" height="353" alt="image" src="https://github.com/user-attachments/assets/aff201bb-aa9c-4a00-a313-26b1623756a4" />
