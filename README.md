# BFSI Conversational Risk Assistant — Data Preprocessing & EDA

## Project Overview

This project focuses on developing a data preprocessing and exploratory data analysis pipeline for consumer complaints in the Banking, Financial Services and Insurance (BFSI) domain.

Customer complaints often contain unstructured text, inconsistent labels and data quality issues. This project transforms the source dataset into a structured format that can support further analysis and future conversational risk-assistance applications.

## Objectives

- Inspect and assess the quality of the raw dataset.
- Handle missing values and remove unnecessary columns.
- Standardize financial product labels.
- Clean complaint narratives using Python regular expressions.
- Implement basic masking of email addresses and phone numbers.
- Engineer complaint-length and keyword-based risk-category features.
- Encode categorical variables and normalize numerical features.
- Perform exploratory data analysis to examine complaint patterns.

## Dataset

**Source:** [Consumer Complaints Dataset on Kaggle](https://www.kaggle.com/datasets/shashwatwork/consume-complaints-dataset-fo-nlp)

The source dataset contains consumer complaint narratives and associated financial product labels.

The dataset used in the project initially contained 162,421 rows and three columns, including an unnecessary index column.

## Tools and Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Regular expressions
- Jupyter Notebook

## Methodology

1. Data ingestion and initial inspection
2. Missing-value and duplicate checks
3. Product-label standardization
4. Text preprocessing and sensitive-information masking
5. Feature engineering
6. Categorical encoding and numerical normalization
7. Exploratory data analysis
8. Export of the processed dataset

## Exploratory Data Analysis

The notebook examines:

- Complaint counts across financial products
- Distribution of keyword-based risk categories
- Average complaint length across risk categories

Add the final charts and verified findings here after rerunning and validating the notebook.

## Key Learning Outcomes

- Working with a large text-based dataset using Pandas
- Designing a sequential data preprocessing workflow
- Applying regular expressions for text cleaning
- Creating features from unstructured complaint narratives
- Using Scikit-learn for encoding and scaling
- Communicating data patterns through visualizations

## Project Scope and Limitations

This is a data preprocessing and exploratory analysis project. It does not implement a trained machine learning model or a deployed conversational AI assistant.

The risk categories are assigned using predefined keywords and should not be interpreted as validated financial risk assessments.

## Academic Context

Apex Project 1 — Trimester 3  
B.S. Data Science and Artificial Intelligence  
BITS Pilani Digital

## Project Files

- **Project Notebook:** [View Jupyter Notebook](BITS_PILANI_Advance_apex_project_1.ipynb)
- **Project Report:** [View Project Report](BITS_PILANI_Apex_Project_Report.docx)

## Contact

Connect with me on [LinkedIn](https://www.linkedin.com/in/kushal07mehta/).
