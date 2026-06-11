# Cybersecurity Attack and Defence Dataset Analysis

This repository contains an analysis of the Cybersecurity Attack and Defence Dataset, which includes various types of cyber attacks and their corresponding defense mechanisms. The dataset is sourced from Kaggle and provides valuable insights into the patterns and trends in cybersecurity incidents.

## Objectives

- To perform data analysis by following a structured approach covering every step from data collection to gathering insights.
- To identify key trends and patterns in cybersecurity attacks and defenses.
- To provide actionable insights that can help in improving cybersecurity measures.
- To determine possible use of this dataset, and if it can be used for training a machine learning model.


## Tech Stack
- Ollama and bge-m3:q4_k_m model for embeddings
- Python ver. 3.11
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn

## Analysis Steps

### Ask 
There are three goals to this project: 
1) Help security teams identify common attack patterns and prepare better defences. Help them answer questions such as - 
>"Which part of a critical system needs priority in protection?" 

2) Train a model to detect threats or predict vulnerabilities.
3) Train a model tailored for training purposes, aiding students to practice responding to cyber incidents.

The first goal is purely analytical and focuses on preparing, processing and gaining valuable insights from the given dataset.
The second and third goal take place after the share phase of the data analytics process, where the control is now in the hands of data scientists to use the processed data for machine learning purposes.

**Key Stakeholders**: 
- Cybersecurity students/freshers.
- Security team professionals.
- Businesses that own given 'critical systems'.
- Data science team.

*Identified Type of Problem*: Making predictions, Identifying Trends, Finding Patterns.


### Prepare
1) Dataset: Second/Third party dataset obtained from Kaggle.
    - Dataset link: https://www.kaggle.com/datasets/tannubarot/cybersecurity-attack-and-defence-dataset
2) Data Format: The given dataset contains `Structured, Wide Data` and mostly descriptive values of the data type `string`, with the exception of the `id` column.
3) The dataset is likely AI-generated, providing reliable, comprehensive synthetic data, which was last updated at 2025.

### Process
1) *Data Cleaning*: Handled missing values, checked for duplicates and cleaned data to remove inconsistencies.
2) *Data Transformation*: Used Ollama to embed data for categorical values in order to group similar values together, and assign them an appropriate "umbrella category" in a different column. This will aid in visualizations and analysis, since each categorical column had ~8000 unique values. For instance, Attack Type column originally had over 8800 unique values after cleaning and formatting the data. This was due to values of similar nature as wireless attacks (basic), wireless attacks (intermediate) and wireless attacks (advanced).
3) 

### Analyze

### Share