# Credit Card Fraud Detection

This repository contains a Jupyter Notebook for detecting fraudulent credit card transactions using machine learning techniques. The notebook provides a complete workflow from data loading and preprocessing to model training and evaluation.

## Table of Contents

1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Dependencies](#dependencies)
4. [Notebook Structure](#notebook-structure)
5. [Usage](#usage)
6. [Results](#results)

---

## Overview

Credit card fraud detection is a critical application of machine learning, aiming to identify fraudulent transactions in financial datasets. This notebook demonstrates a comprehensive pipeline for:

- Exploratory data analysis (EDA)
- Feature engineering
- Model training and evaluation

---

## Dataset

The notebook uses a dataset containing credit card transaction records with labels indicating whether a transaction is fraudulent. The dataset includes:

- **Training Data**: `fraudTrain.csv`
- **Testing Data**: `fraudTest.csv`

The data is loaded from a Google Drive directory, as configured in the notebook. The dataset is originally sourced from Kaggle and can be accessed [here](https://www.kaggle.com/datasets/kartik2112/fraud-detection).

---

## Dependencies

The following libraries are required to run the notebook:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Ensure these dependencies are installed in your Python environment.

---

## Notebook Structure

1. **Imports and Setup**: Importing necessary libraries and configuring display settings.
2. **Data Loading**: Reading the training and testing datasets from Google Drive.
3. **Exploratory Data Analysis (EDA)**: Inspecting the dataset structure and distributions.
4. **Feature Engineering**: Applying transformations and creating new features.
5. **Model Training**: Implementing machine learning models for fraud detection.
6. **Evaluation**: Assessing model performance using metrics such as accuracy, precision, recall, and F1-score.

---

## Usage

1. Clone this repository and navigate to the notebook directory.
2. Ensure the datasets (`fraudTrain.csv` and `fraudTest.csv`) are accessible via the specified paths in the notebook.
3. Open the notebook in Jupyter or Google Colab.
4. Run the cells sequentially to reproduce the results.

---

## Results

The notebook provides a detailed analysis of model performance and insights into the factors contributing to fraudulent transactions. Results are visualized using plots and evaluation metrics.

---

Feel free to contribute to this project or raise issues if you encounter any problems!

