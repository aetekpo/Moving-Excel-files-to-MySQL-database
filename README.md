# Transactional Database Modeling
## Overview
This repository contains documentation on how to populate a MySQL database with data from an Excel file containing multiple sheets. The dataset includes information about credit card fraud transactions from the period of January 1, 2019, to December 31, 2020, obtained from Kaggle.
## Data Source
The original dataset is obtained from Kaggle and contained legitimate and fraud transactions from the duration of 1st Jan 2019 - 31st Dec 2020. It covers credit cards of 1000 customers doing transactions with a pool of 800 merchants.
- To download the main dataset Click 👉 [here](https://www.kaggle.com/datasets/kartik2112/fraud-detection)
## Steps followed in the project
- **Step 1**: The original dataset was downsampled from 555,718 rows to 10,000 rows containing 70% of is_fraud and 30% of is_not_fraud data called subfraudtest.
- **Step 2**: The subfraudtest was split into different Excel sheets using Python which corresponds to different tables in MySQL database.
- **Step 3**: The tables in the database were populated with data coming from corresponding Excel sheets using python scripts.
## Architecture to build the database
- **Conceptual Model to build the database** This shows the relationship between the entities.
  
  ![image alt](https://github.com/aetekpo/OLTP-Data-Modeling/blob/9e933f16ed0d51f0dda7a6325f6d59f9d9c660f3/Conceptual%20Model%20for%20the%20dataset.png)
  
- **Logical Model to build the database** This defines the entities, the relationships, key attributes, and the normalization
  
  ![image alt](https://github.com/aetekpo/OLTP-Data-Modeling/blob/264f381690c3a1ce91f127d2255fd7225849524d/Logical%20Model%20for%20the%20dataset.png)
  
- **Physical Model to build the database** This implements the SQL script which creates tables, columns, indexes, constraints in relational database.

  ![image alt](https://github.com/aetekpo/OLTP-Data-Modeling/blob/ba7d59ee22ae712c1d5db12743006847375d0a9e/Physical%20Model%20for%20the%20dataset.png)
  
- **Data Model ERD** This shows the full relationship between tables in the database after the script was run

 ![image alt](https://github.com/aetekpo/OLTP-Data-Modeling/blob/master/Data_Model_ERD.png?raw=true)
  
## Author
[Asserewou Etekpo](https://www.linkedin.com/in/asserewou-etekpo-1450821a2/)



