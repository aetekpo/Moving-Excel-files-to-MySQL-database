# Transactional Database Modeling
## Overview
This repository contains documentation on how to populate a MySQL database with data from an Excel file containing multiple sheets. The dataset includes information about credit card fraud transactions from the period of January 1, 2019, to December 31, 2020, obtained from Kaggle.
## Files
-	**Database_Creation.sql**: Contains SQL queries used to create the Entity-relationship diagram (ERD).
-	**Data_Model_ERD.png**: Entity-relationship diagram (ERD) illustrating the data and relationships between tables.
- **Data_Dictionary.xlsx**: Documentation describing the structure and contents of each table in the database.
- **README.md**: This file provides an overview of the repository and instructions for accessing and using the Python scripts
- Click 👉 [here](https://drive.google.com/drive/u/0/folders/1OYTUOxKMUpeaB76EdTwb0U0IuRRBBwn5)👈 to see the files
## Steps followed in the project
- **Step 1**: The original dataset was downsampled from 555,718 rows to 10,000 rows containing 70% of is_fraud data called subfraudtest.
- **Step 2**: The subfraudtest was split into different Excel sheets corresponding to different tables in MySQL database.
- **Step 3**: The tables in the database were populated with data coming from corresponding Excel sheets using python scripts.
## Data Source
The dataset is obtained from Kaggle and contained legitimate and fraud transactions from the duration of 1st Jan 2019 - 31st Dec 2020. It covers credit cards of 1000 customers doing transactions with a pool of 800 merchants.
- To download the main dataset Click 👉 [here](https://www.kaggle.com/datasets/kartik2112/fraud-detection)
## Author
[Asserewou Etekpo](https://www.linkedin.com/in/asserewou-etekpo-1450821a2/)



