# Breast Cancer Cell Line Classification Using Electrical Properties

This project focuses on the classification of breast cancer cell lines based on their electrical properties using deep learning. The objective is to develop a predictive model that accurately distinguishes between different cell lines by analyzing measurable bioelectrical features.

This project was part of a Summer Undergraduate Research Experiences (SURE) program from the United Arab Emirates university in 2023. Initially, preliminary supervised machine learning techniques using Scikit-Learn were used during the project. The results were decent with an average accuracy of 72%.

In this repository, more sophistacted deep learning techniques will be used, to compare with the initial results.

## Overview

Electrical properties of cells such as impedance, capacitances, conductivity, 
permeability, and resistibility are emerging as non-invasive biomarkers for cancer detection and classification. This projects leverages such features to classifiy four distinct breast cancer cell lines using neural network implemented in PyTorch. These cell lines are: HS578t, MCF7, MDA-MB-231, and T47D.

## Objectives

- Aggregate and preprocess electrical property data from multiple Excel sheets per cell line.
- Train a deep learning model capable of accurately classifying cell lines.
- Evaluate model performance and visualize results using scientific metrics.

## Dataset

The dataset consists of four breast cancer cell lines. Each cell line is represented by a separate Excel file containing multiple sheets. Each sheet corresponds to different experimental conditions or measurement sessions.

Note: Due to privacy or publication constraints, the dataset is not publicly included in this repository.

## Methodology

1. Data Aggregation: Consolidate multi-sheet Excel files into labeled dataframes per cell line.

2. Preprocessing: Normalize features, encode labels, and split data into training and testing sets.

3. Model Architecture: A feedforward neural network implemented in PyTorch, tailored to handle the dimensionality of the input features.

4. Training & Evaluation: Use cross-entropy loss and an Adam optimizer. Evaluation metrics include accuracy, confusion matrix, and classification report.

## Results

Model performance will be documented here upon completion of training and evaluation. Future iterations may include hyperparameter tuning and additional architectures.

## Future Work

- Expand dataset with more cell lines or conditions.

- Explore feature selection techniques to identify the most predictive electrical markers.

- Deploy model for real-time classification in experimental setups.

