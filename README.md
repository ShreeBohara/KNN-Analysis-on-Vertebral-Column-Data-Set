# KNN-Analysis-on-Vertebral-Column-Data-Set

# KNN Analysis on Vertebral Column Data (Jupyter Notebook)

This repository contains a comprehensive Jupyter Notebook that implements a K-Nearest Neighbors (KNN) classification analysis on the Vertebral Column Data Set. The project was developed as part of the Homework 1 assignment for DSCI 552 under the instruction of Mohammad Reza Rajati.

## Project Overview

The main objectives of this project are to:
- Perform exploratory data analysis (EDA) on the Vertebral Column Data Set
- Implement KNN classification using various distance metrics:
  - Euclidean
  - Manhattan (via Minkowski with p=1)
  - Minkowski (with varying p values)
  - Chebyshev
  - Mahalanobis
- Evaluate model performance using:
  - Confusion Matrix
  - True Positive Rate (Sensitivity)
  - True Negative Rate (Specificity)
  - Precision
  - F1-score
- Generate learning curves and analyze weighted voting strategies

## Dataset

The Vertebral Column Data Set, originally compiled by Dr. Henrique da Mota during a medical residency in Lyon, France, contains six biomechanical attributes:
- pelvic incidence
- pelvic tilt
- lumbar lordosis angle
- sacral slope
- pelvic radius
- grade of spondylolisthesis

For this project, a binary classification task is performed where:
- Normal (NO) is mapped to 0
- Abnormal (AB) is mapped to 1

The dataset is available at the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Vertebral+Column).

## Project Structure

- **notebook.ipynb**  
  The main Jupyter Notebook containing the full analysis: data preprocessing, visualization, KNN implementation with different metrics, and evaluation.

- **data/**  
  A folder to store the dataset file(s). Make sure the dataset is placed here if not reading directly from a URL.

- **README.md**  
  This file, which provides an overview of the project and instructions.

## Requirements

To run the notebook, you will need:
- Python 3.12.8
- Jupyter Notebook
- The following Python libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - scipy


