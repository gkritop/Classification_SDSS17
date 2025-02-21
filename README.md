## Overview
This is a machine learning project aimed at classifying celestial objects—**stars, galaxies, and quasars**—from the **Sloan Digital Sky Survey (SDSS17) Stellar Classification Dataset**. Using **unsupervised clustering** and **supervised learning**, this project develops a robust classification model to enhance astrophysical data analysis. This project was destined for a specific class ("Machine Learning 1") of the University of Crete.

## Features
- **Data Preprocessing**: Handling missing values, feature encoding, and outlier detection.
- **Unsupervised Learning**: Using **K-Means clustering** to uncover intrinsic patterns.
- **Supervised Learning**: Implementing and comparing multiple models:
  - Logistic Regression
  - Decision Trees
  - K-Nearest Neighbors (KNN)
  - Support Vector Machines (SVM)
  - **Random Forest (Best Performer)**
- **Feature Engineering**: Evaluating the impact of **redshift** on classification accuracy.
- **Model Evaluation**: Metrics include **accuracy, precision, recall, F1-score, and ROC-AUC**.

## Installation
Clone this repository and install the required dependencies:
```bash
git clone https://github.com/yourusername/Ghostbusters.git
cd Ghostbusters
pip install -r requirements.txt
