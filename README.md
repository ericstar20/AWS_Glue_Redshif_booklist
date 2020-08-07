# Data Warehouse and ETL implemented by AWS Glue and Redshift

__Motivation:__\
To brush up my ETL memory and also practice AWS redshift (data warehouse) and AWS glue (ETL tool), I stored a 'book.csv' file in to S3. Then, used glue to transform all the data into redshift.

# The project's flow chart
<img src = "ETL_flowchart.jpg" width='900' heigh='600'>

__Step 1. Store books.csv file into S3__
The easiest part in this project. Just upload the file into S3.

__Step 2. Glue - Crawlers__
A crawler connects to a data store, progresses through a prioritized list of classifiers to determine the schema for your data, and then creates metadata tables in your data catalog.\
This function can help you creating Table schema effortless.
<img src = "ETL_flowchart.jpg" width='900' heigh='600'>

# Summary


# References
[Data](https://www.kaggle.com/jealousleopard/goodreadsbooks?select=books.csv)\
[Tutorial Link 1](https://www.youtube.com/playlist?list=PL3GCZkoyKK4fEUDH2UMMj0eumx2NqPP1J)\
[Tutorial link 2](https://www.youtube.com/watch?v=8t5pNcSnebQ&t=11s)\
[Handling the error when connected glue to redshift.](https://stackoverflow.com/questions/46531522/glue-job-for-redshift-connection-unable-to-find-suitable-security-group)\
[Handling S3 endpoint error](https://stackoverflow.com/questions/55972886/could-not-find-s3-endpoint-or-nat-gateway-for-subnetid)
[setting up redshift connecting to s3](https://docs.aws.amazon.com/glue/latest/dg/setup-vpc-for-glue-access.html)
[How to find S3 prefix id](https://docs.aws.amazon.com/vpc/latest/userguide/managed-prefix-lists.html)
