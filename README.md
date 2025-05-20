## Purpose
This project demonstrates the creation and management of a data lake on AWS using AWS Athena, AWS Glue, and AWS Data Wrangler. The primary goal is to efficiently ingest, store, query, and analyze a large dataset of music reviews. The dataset contains detailed information about various tracks, including artists, album names, track popularity, audio features, and genres.

The project involves the following key steps:

 - Data Ingestion: Uploading a cleaned CSV dataset to Amazon S3.

 - Data Transformation: Converting the CSV format to Parquet for efficient querying.

 - Data Cataloging: Creating an AWS Glue database and registering the Parquet files as Athena tables.

 - Data Querying: Utilizing AWS Athena to perform complex SQL queries, including filtering, aggregation, and statistical analysis.

 - Analysis and Visualization: Extracting insights such as the most popular artists, genres with the highest average energy, and tracks by specific artists like "Bad Bunny".

Through this project, we explore how AWS services can be leveraged to build a scalable, cost-efficient data lake for analyzing large volumes of structured data. The integration of Athena with AWS Glue and S3 allows for robust and dynamic data management, while the use of Parquet format enhances query performance. The results showcase how data lakes facilitate efficient querying and data-driven decision-making.
