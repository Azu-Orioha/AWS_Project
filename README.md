# AWS_Project
An End to End AWS Project using AWS (S3, Glue, Athena, and Quicksight)

# Project Diagram
https://app.eraser.io/workspace/hWoT4RgrgiAfvBROhekI


# Location of CSV file 
The CSV file imported into the S3 Bucket is located in <\DESKTOP\DATA ENGINEER\AWS\ATHENA\Superstore.csv>

# S3 Bucket Name "my-s3-storages"

Instructions
Create an Iam user <Test_user01> , using the <Root> User
Grant the user AdministorAccess
Log the <Root> user out
Login using the <Test_user01>
Create an S3 Bucket 
  - a cloud storage where all data is stored
Once the S3 bucket is created
  - create the following folder structure within S3 bucket
  -   <orders>
  -     <snapshot_day=2017-01-10>      
upload the orders.csv file

using the GLUE SERVICES

# Create a Database 
Database name is  "db_superstore_02"

# Create a Crawler
Crawler name is  "orders_project_03"

# Create a Table
Database name is  "db_superstore_01"


Now create a catalogue using the AWS crawler
Create a crawler
choose a data source 
assign a role an IAM role 
select the database create in (18)
create crawler
