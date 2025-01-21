# Deep Learning HW1: Logistic Regression using Feed Forward Networks

## Overview
This assignment explores logistic regression through the lens of deep learning, using a feedforward neural network to implement binary and multi-class classification. The goal is to leverage neural networks to enhance logistic regression, enabling more complex decision boundaries.

## Part 1: Binary Classification
### Task
Predict whether an individual's yearly income exceeds $50,000 using a feedforward neural network.

### Dataset
- **Features:** 15 personal attributes (e.g., age, gender, nationality).
- **Files:** Training and testing CSV files.

### Steps
1. **Data Loading:** Load the dataset onto Google Drive and mount it on the notebook.
2. **Data Exploration:** Print samples and the distribution of yearly income.
3. **Preprocessing:** Prepare the data for training.
4. **Model Definition:** Define the model using PyTorch libraries.
5. **Training:** Train the model and plot loss, training accuracy, and validation accuracy over epochs.
6. **Benchmarking:** Aim to outperform logistic regression (79.7%) and SVM (79.8%).

### Requirements
- Use only PyTorch libraries.
- Choose appropriate regularization techniques, optimizer, and loss function.

## Part 2: Multi-Class Classification
### Task
Predict clothing categories using the FashionMNIST dataset.

### Dataset
- **Images:** 70,000 grayscale images (28x28 pixels) representing 10 categories.

### Networks
1. **Network 1:** 2-layer network for the first 4 categories (parameters ≤ 50k).
2. **Network 2:** 4-layer network for all categories (parameters ≤ 60k).

### Steps
1. **Model Definition:** Define two feedforward networks.
2. **Training:** Train both networks and plot loss, training accuracy, and validation accuracy over epochs.
3. **Analysis:** Compare the performance of the two networks and explain the results.

### Requirements
- Use only PyTorch libraries.
- Choose appropriate regularization techniques, optimizer, and loss function.

## Submission
- **File:** HW1_ID1_ID2.ipynb (IDs of submitters).
- **Content:** Notebook with all code cells run, documentation, plots, and explanations.
- **Format:** Tidy and readable, with student names at the head of the notebook.
- **Model Details:** Print each model with its number of parameters.

## Notes
- Only PyTorch can be used for model definition.
- Other libraries can be used for data manipulation and preprocessing.

---

I hope this helps! If you need any further details or assistance, feel free to ask.
