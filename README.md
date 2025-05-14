# Breast Cancer Prediction with Machine Learning

This project focuses on building a machine learning model to classify breast cancer tumors as **malignant** or **benign** using the **Breast Cancer Wisconsin (Diagnostic) Dataset**. The goal is to apply data preprocessing, train a model, and evaluate its performance using classification metrics.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Modeling](#modeling)
- [Results](#results)
- [Usage](#usage)
- [License](#license)

## Overview

Breast cancer is one of the most common types of cancer among women. Early and accurate diagnosis is crucial for effective treatment. In this notebook, we:

- Load and explore the dataset
- Perform preprocessing and visualization
- Train a classification model
- Evaluate it using accuracy and confusion matrix

## Dataset

The dataset used is the **Breast Cancer Wisconsin (Diagnostic)** dataset, which is available in the `sklearn.datasets` module. It contains 30 features computed from digitized images of fine needle aspirates (FNA) of breast masses, along with the target label:

- **Target classes**:  
  - 0 = Malignant  
  - 1 = Benign

- **Number of instances**: 569  
- **Number of features**: 30 numerical features

## Technologies Used

- Python 3  
- scikit-learn  
- pandas  
- NumPy  
- Matplotlib / Seaborn  

## Installation

1. Clone the repository:

```bash
git clone https://github.com/bakituncher/breast_cancer.git
cd breast_cancer
