
# Exfoliation Energy and Band Gap Predictor

## Project Overview
This project aims to predict exfoliation energy and band gap properties of 2D topological materials using machine learning models.
Given a dataset with relevant material attributes, we will train a model to accurately predict these properties.

## Project Objectives
1. **General purpose model development**
2. **Specific purpose model development for 2D Topological Materials **
3. **Model Validation and Hypothetical Materials Testing/Screening**

## ML Objectives
1. **Predict Exfoliation Energy**
2. **Predict Band Gap**

## Data Description
The dataset is downloaded from 2DMatpedia and stored in `db.csv` and includes the following attributes:

- **Attributes**: Relevant features contributing to material properties (e.g., elemental composition, atomic properties, etc.)
- **Target Variables**: 
  - **Exfoliation Energy**
  - **Band Gap**

## Project Structure
- `data/`: Folder containing the dataset file.
- `notebooks/`: Jupyter notebooks for data analysis and model training.
- `models/`: Trained models and serialized files.
- `README.md`: Project documentation.

## Installation
Ensure the following libraries are installed:
```bash
pip install pandas numpy scikit-learn matplotlib
```

## Step-by-Step Workflow

### Step 1: Data Loading
1. Load the dataset and inspect the data for any missing values.
2. Identify relevant features (predictor variables) and target variables (exfoliation energy, band gap).

### Step 2: Preprocessing
1. Handle missing values, if any.
2. Scale or normalize features, especially if there is a significant range difference.

### Step 3: Feature Selection
1. Select relevant attributes based on initial analysis and domain knowledge.

### Step 4: Model Training
1. Choose a machine learning model (e.g., Linear Regression, Random Forest, or a simple Neural Network).
2. Train the model separately for:
   - Exfoliation Energy prediction
   - Band Gap prediction

### Step 5: Evaluation
1. Evaluate model performance using metrics like RMSE or MAE.
2. Adjust the model or hyperparameters as needed.

### Step 6: Save and Deploy
1. Save the trained model for future predictions.
2. Document and save any additional transformations for input preprocessing.

---

