Parkinson’s Disease Prediction
This project focuses on predicting Parkinson’s Disease progression using clinical, peptide, and protein data. The approach includes data preprocessing, feature engineering, and model training using machine learning techniques.
Steps Followed:
Data Loading:
	•	Loaded datasets: train_peptides.csv, train_proteins.csv, and train_clinical_data.csv.
	•	Exploratory Data Analysis (EDA):
	•	Displayed the first few rows of each dataset to understand their structure.
Feature Engineering:
	•	Aggregated peptide and protein data by visit_id and UniProt to calculate mean values.
	•	Merged these aggregated datasets with clinical data.
Data Preprocessing:
	•	Applied StandardScaler to normalize features.
	•	Split the dataset into training and testing sets.
Model Training:
	•	Implemented a RandomForestRegressor model for prediction.
	•	Utilized Pipeline for preprocessing and modeling.
Evaluation:
	•	Measured model performance using Mean Squared Error (MSE).
	•	Visualized results using Matplotlib and Seaborn.
