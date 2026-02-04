# SQL-Data-Engineering-Chicago-Schools Analysis
DATASET_DATABASE - USING SQL & PYTHON

OBJECTIVE(S)
- Understanding the dataset and data type.
- Store the dataset in SQLite database 
- Retrive data about tables & columns
- Query data from mixed case columns

This jupyter note involved architecting a relational database from a large-scale CSV dataset containing Chicago Public School data. The objective was to perform complex SQL querying to extract institutional insights, such as school distribution and safety performance.

Technical Challenges & Resolution: Data Integration Obstacle: Initial attempts to establish a remote connection via Google Drive and external URLs resulted in connectivity bottlenecks and authentication errors.

Optimization Solution: Resolved the integration issue by transitioning to a Local Directory Alignment. By co-locating the .ipynb notebook and the raw dataset within the same root directory, eliminating pathing conflicts and successfully initialised the SQLite database engine. Note: By solving the "File Not Found" error through local pathing, demonstrated an understanding of environment management, which is a critical skill for any data engineer working in collaborative or containerized environments.
