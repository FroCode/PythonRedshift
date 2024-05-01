# Fintech Data Processing and Analysis

## Overview
This project involves extracting Fintech data, loading it into Amazon Redshift, and preparing for further analysis and visualization in Power BI. The data is processed using a Python script that uploads the data to an S3 bucket and then loads it into a Redshift database.
![image](https://github.com/FroCode/AWS-ETL/blob/main/bg_1.png)
## Project Structure
- `fintech_data_processing.py`: This script handles the connection to AWS services (S3 and Redshift), creates necessary database schema and tables, and performs data loading operations.
- `.env`: A dotenv file to store sensitive credentials like AWS access keys, Redshift database credentials, etc. (Note: This file should not be checked into version control).
- `README.md`: Provides project documentation.

## Setup Instructions
### AWS Services And Tools
- AWS CLI
- Boto3
- IAM
- VPC
- Amazon Redshift Cluster
- Amazon S3 Bucket
- Power BI for visualization (Upcoming)

### Environment Setup
1. Clone the repository to your local machine.
2. Ensure Python 3.x is installed.
3. Install required Python packages:
   ```bash
   pip install pandas boto3 psycopg2-binary python-dotenv

### Current Work
The data upload and initial processing are functioning correctly. However, there are still tasks under development:

1. Data Analysis: Detailed analysis of the data is in the planning stages.
2. Dashboard Development: A Power BI dashboard is currently under development to visualize and interact with the dataset.