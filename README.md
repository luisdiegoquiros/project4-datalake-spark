# Song Play Analysis

## Context

The purpose of this database is to help the startup Sparkify. 
The goal is to create a data lake to help them with their analytical goals, because their user and song database has grown. 
Their data resides in S3, formatted as JSON.
They want to process their events and songs information. 

# Used Tools

The data is loaded data from S3, processed into analytics tables using Spark, and then loaded back into S3. 
This process was deployed using a Spark process on a cluster using AWS EMR and taking advantage of their notebooks. .

# File in the repository


* *Data_lake_project.ipynb:* contains all the necessary processed and code to complete the objective. It shows the Spark code using pyspark used to accomplish the given objectives.

* *data_lake_project.html:*  contains the notebook with all the cells executed.


# Run scripts

It is better to upload the notebook to the AWS EMR service and connect it to a cluster. Doing this will facilitate getting a Spark Context up and running. The notebook can be used as usual and execute the cells from top to bottom to generate the files.