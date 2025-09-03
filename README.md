# Firmable-Data-Assignment
Data qulity assurance of New event Dataset

Repository Overview

This repository contains code, scripts, and analysis for data ingestion, exploration, and visualization. Below are the key files and their purposes:
	•	db_ingestion__code.ipynb – Converts raw JSONL data into structured rows and columns, and ingests it into target tables.
	•	eda_Assignment (1).ipynb – Main EDA assignment notebook containing all analysis steps.
	•	DDL Scripts – SQL scripts to define database schemas and tables for data storage.
	•	DQL Scripts – SQL scripts for querying data for various analysis purposes.

⸻

Setup and Running Instructions

1. Environment Setup
	•	The analysis was performed in Google Colab; no local installation is required.
	•	Ensure you are signed in with a Google account to access Colab.

⸻

2. Required Files
	•	A Service Account JSON key file is required to connect to Google BigQuery.
	•	The JSON key file (e.g., my_project_key.json) can be downloaded from the following link:
[Download JSON Key](https://drive.google.com/file/d/1NctPzZNYBJ2Yh4VrN2XBD5wA8sOk_3p4/view?usp=drive_link )
(Unable to upload this file directly to GitHub due to security reasons.)
	•	Upload this JSON file to your Colab session (or your Google Drive) before running the code.

⸻

3. Required Libraries

All necessary libraries are pre-installed in Google Colab; no additional installation is required.

⸻

4. Steps to Reproduce
	1.	Open Google Colab Notebook
	•	Upload or open the provided .ipynb notebooks in Google Colab.
	2.	Upload the JSON Key File
	•	Upload the downloaded key file to your Colab session or mount it from Google Drive.
	3.	Update the JSON Key Path
	•	Modify the code to point to the uploaded key file path.
	4.	Run Code Cells
	•	Execute the notebook cells sequentially to load data, run analysis, and generate outputs.

⸻

Dashboard Access

[You can view the dashboard here](https://lookerstudio.google.com/u/2/reporting/a79dc567-8837-4844-9237-700e113c8006/page/xUgWF)

The dashboard contains:
	1.	Data Quality Metrics
	2.	Data Error Reports
