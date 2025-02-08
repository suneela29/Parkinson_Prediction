# 🧠 Parkinson’s Disease Prediction

This project aims to predict Parkinson’s Disease progression using **clinical, peptide, and protein data**. We leverage **machine learning techniques** to preprocess data, engineer features, and train predictive models.

## 📌 Steps Followed

### 📂 Data Loading
- Loaded datasets: `train_peptides.csv`, `train_proteins.csv`, and `train_clinical_data.csv`.
- Performed **Exploratory Data Analysis (EDA)** to understand dataset structures.

### 🔍 Feature Engineering
- Aggregated **peptide and protein data** by `visit_id` and `UniProt` to calculate mean values.
- Merged the aggregated datasets with **clinical data** for comprehensive analysis.

### 🛠 Data Preprocessing
- Applied `StandardScaler` to **normalize features**.
- Split the dataset into **training** and **testing** sets.

### 🤖 Model Training
- Implemented a **RandomForestRegressor** for prediction.
- Used a **Pipeline** to streamline preprocessing and modeling.

### 📊 Evaluation
- Measured model performance using **Mean Squared Error (MSE)**.
- Visualized results with **Matplotlib** and **Seaborn**.

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/suneela29/Parkinson_Prediction.git
