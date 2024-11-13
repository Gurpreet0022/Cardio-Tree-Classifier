
# Cardio Tree Classifier

This project, **Cardio Tree Classifier**, is designed to classify the likelihood of heart disease based on various health indicators. It uses a decision tree classifier to analyze a dataset of health information to make predictions on heart disease outcomes.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Evaluation](#evaluation)

## Project Overview
The **Cardio Tree Classifier** uses machine learning techniques to analyze factors associated with heart disease. This project applies data preprocessing techniques such as label encoding and one-hot encoding and builds a decision tree classifier model for prediction.

## Dataset
The dataset used for this project is `heartDisease_2020_sampling.csv`, which contains various health indicators. These include:
- Heart disease diagnosis
- General health status
- Smoking and drinking habits
- Physical activity level
- Age category
- Race and gender information

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Cardio-Tree-Classifier.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Cardio-Tree-Classifier
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Load and preprocess the dataset:
   The code reads `heartDisease_2020_sampling.csv` and preprocesses it by label encoding categorical columns and one-hot encoding race information.
2. Train and evaluate the model:
   - The decision tree classifier is trained on the processed data.
   - Run the script to view sample data and training results.
3. Run the main script:
   ```bash
   python main.py
   ```

## Model Training
The model is trained using a decision tree classifier, with the following steps:
- **Data Cleaning**: Label encoding and one-hot encoding of categorical variables.
- **Model Selection**: Decision Tree Classifier.
- **Training and Prediction**: The model is trained on the preprocessed dataset.

## Evaluation
The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1 score. 

