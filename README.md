# Breast Cancer Detection

This project implements a machine learning-based approach to detect breast cancer using the Wisconsin Diagnostic Breast Cancer (WDBC) dataset. The goal is to classify tumors as malignant or benign based on several features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.

# Table of Contents

1. Project Overview
2. Dataset
3. Installation
4. Usage
5. Model
6. Results
7. Contributing
8. License

# Project Overview
Breast cancer is one of the most common cancers affecting women worldwide. Early and accurate diagnosis is crucial for better prognosis and treatment. This project applies machine learning techniques to assist in diagnosing breast cancer by analyzing tumor cell features.

The primary objective of this project is to build a classification model that predicts whether a tumor is malignant (cancerous) or benign (non-cancerous) using the WDBC dataset.

# Dataset
The dataset used in this project is the Wisconsin Diagnostic Breast Cancer Dataset (WDBC), which consists of the following:

Number of Instances: 569
Number of Features: 30 real-valued features computed from digitized images of breast masses (e.g., radius, texture, smoothness, etc.)
Target Variable: Binary (malignant or benign)
The dataset is publicly available at the UCI Machine Learning Repository.

# Installation
To set up this project locally, follow these steps:

## Clone the repository:

git clone https://github.com/your-username/breast-cancer-detection.git

cd breast-cancer-detection

## Create a virtual environment and activate it:

python -m venv venv

source venv/bin/activate  # On Windows, use: venv\Scripts\activate

## Install the required dependencies:

pip install -r requirements.txt

# Usage
To run the project and perform breast cancer prediction:

Ensure the dataset is in the data/ folder.
Execute the main Python script:
python main.py
This will train the machine learning model on the dataset, evaluate its performance, and display the results.

## Jupyter Notebook
Alternatively, you can explore the project and experiment with the data using the Jupyter notebook provided:

jupyter notebook breast_cancer_detection.ipynb

# Model
Several machine learning models have been implemented and evaluated for this project, including:

*Logistic Regression
*Random Forest Classifier
*Support Vector Machine (SVM)
*k-Nearest Neighbors (k-NN)

The models are compared based on their accuracy, precision, recall, and F1-score.

# Results
The best-performing model achieved the following metrics on the test dataset:

*Accuracy: 98.5%
*Precision: 98.2%
*Recall: 98.7%
*F1-Score: 98.4%

The results indicate that the model is highly effective at distinguishing between malignant and benign tumors.

# Contributing
Contributions are welcome! If you'd like to contribute to this project:

1. Fork the repository.
2. Create a new feature branch (git checkout -b feature/new-feature).
3. Commit your changes (git commit -m 'Add new feature').
4. Push the branch (git push origin feature/new-feature).
5.Open a Pull Request.

# License
This project is licensed under the MIT License. See the LICENSE file for details.






