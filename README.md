📊 Data Redundancy Removal System using Python (CodeAlpha Task-01)

🚀 This project was developed as part of my CodeAlpha Data Science Internship (Task-01) titled “Data Redundancy Removal System using Python”. The objective of this project is to detect and remove duplicate records from a dataset and improve data quality using data preprocessing techniques along with visualization.

📊 Project Objective

The main objective of this project is to identify duplicate records in a dataset and remove redundancy to ensure clean, accurate, and optimized data for further analysis and machine learning applications.

📁 Dataset Description

The dataset used in this project is marketing_campaign.csv, which contains customer and marketing-related data.

It includes:

Customer demographics
Campaign response details
Behavioral and transaction data
Duplicate records (to be cleaned)
⚙️ Workflow
🔹 1. Data Loading

The dataset is loaded using Pandas for initial exploration and inspection.

🔹 2. Duplicate Detection

Duplicate records are identified using:

df.duplicated() function
🔹 3. Data Cleaning

All duplicate records are removed using:

drop_duplicates() method

The cleaned dataset is saved as:

cleaned_marketing_campaign.csv
🔹 4. Data Analysis

The system calculates:

Total records before cleaning
Total records after cleaning
Number of duplicate records removed
🔹 5. Data Visualization

Graphs are used to visualize the impact of cleaning:

📊 Bar Chart → Before vs After Cleaning
🥧 Pie Chart → Duplicate vs Unique Records

🔹 6. Output Generation

A cleaned dataset is generated and downloaded for further use.

🛠️ Technologies Used
Python 🐍
Pandas 📦
Matplotlib 📊
Seaborn 📈
Google Colab / Jupyter Notebook
🔑 Key Features
Detects duplicate records in dataset
Removes redundant data efficiently
Improves dataset quality
Visualizes cleaning results using graphs
Generates cleaned dataset for analysis
📈 Outcome

This project demonstrates how data redundancy affects dataset quality and how it can be efficiently removed using Python. It also provides visual comparison between original and cleaned datasets.
