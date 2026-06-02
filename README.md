# glp1-analysis

Pharma Adverse Reaction Data Analysis
This repository contains the data analysis workflow for exploring and combining adverse drug reaction datasets from Kaggle and Canadian Government Open Data.
Project Overview
This project performs an exploratory data analysis on pharma safety data. It automates the ingestion of large, disparate datasets into a centralized Google Cloud Storage (GCS) "Data Lake" and processes them using Python and Pandas.
Data Sources
	1.	Kaggle: GLP-1 weight loss drugs master dataset (2017-2026).
	2.	Canada Open Data: Canada Vigilance Adverse Reaction Online Database.
Architecture
•	Ingestion: Google Colab
•	Storage: Google Cloud Storage (GCS)
•	Processing: Python (Pandas)
Setup Instructions
To run this analysis:
	1.	Ensure you have the necessary Google Cloud credentials configured for your GCS bucket.
	2.	The data is currently stored in a GCS bucket named my-pharma-data-project.
	3.	Use the provided Jupyter notebook to load and clean the datasets from the bucket.
Repository Contents
•	analysis.ipynb: The primary notebook containing data cleaning, merging, and exploratory analysis.
