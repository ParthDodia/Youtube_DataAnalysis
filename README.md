# Youtube_DataAnalysis
This project comprised of end-to-end data pipelining i.e., from collecting raw data to building a dashboard.
 
The data which I used is YouTube video statistics data from Kaggle.
https://lnkd.in/epSNygcg
 
I utilized Amazon Web Services (AWS) for storing, cleaning, and processing the data.
 
## Services used in a nutshell:

S3 - It can be used to store any type of data and is highly scalable and durable offering features such as object versioning and encryption.

IAM - It allows you to create and manage different roles and policies that grant specific permissions to users and applications.

Glue – It is a fully managed data integration service which can be used to create and run ETL jobs that extract data from various sources, transform it into a desired format, and load it into a target data store such as S3.

Lambda – It is a serverless compute service that allows you to run code. Can also be used to automate data ingestion and data processing using triggers.

Athena – It is a serverless interactive query service that makes it easy to analyze data stored in S3 using standard SQL.

QuickSight – It is a cloud-native business intelligence service that makes it easy to create interactive dashboards and reports.

Process:
-       Uploaded raw data on S3 bucket using shell.
-       Created roles for the services and assigned policies thorough IAM.
-       Coded a function to transform .json files to parquet using Lambda.
-       Automated processing using triggers through Glue crawler.
-       Utilized Athena to query the generated database to get insights.
-       Generated dashboard to visualize the data using QuickSight.

This was an intermediate level project, and it was a great experience to get hands on practice with the current tools and technologies being used in data engineering.

Stay tuned for more projects!
