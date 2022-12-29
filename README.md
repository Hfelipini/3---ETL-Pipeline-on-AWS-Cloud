*Data Engineering Project on COVID-19 DataLake by AWS*

Performing data modeling, data wrangling, and extract-load-transform (ETL) tasks using Python on the COVID-19 Data Lake available in the AWS Open Data Registry. This includes utilizing various AWS tools such as Boto3, Glue, S3, Athena, and Redshift.

Tools and Usages:

- Amazon S3 is used for storing the data.
- Crawlers are used to extract the schema and information directly from S3.
- Amazon Athena is used for running ad hoc SQL queries on the data in S3.
- AWS Glue is used for data transformation.
- Amazon Redshift is used for storing the transformed dimensional model in a data warehouse.
- Boto3 is the AWS Python SDK used for creating, configuring, and managing AWS services.

Data Set: https://registry.opendata.aws/aws-covid19-lake/

How to get the data?

- You can download and upload the data to an S3 bucket;
- You can use the AWS CLI copy command: aws s3 cp s3://mybucket/test.txt s3://mybucket/test2.txt; or,
- You can retrieve the data in code using Boto3.

STEPS:

- Run Crawlers on the data uploaded to S3.
- Analyze the data using the AWS Athena query editor.
- Build an Entity-Relationship (ER) data model.
- Perform ETL jobs in Python.
- Save the results in S3.
- Build a Dimensional Model.
- Build a dimensional schema in Redshift.
- Store the dimensional model in Redshift.
