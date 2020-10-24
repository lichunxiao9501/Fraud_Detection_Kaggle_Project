# Fraud Detection Kaggle Project
This repository demonstrates a practice project in the fraud detection field using data from Kaggle competition - IEEE-CIS Fraud Detection.

### File Documentation

This project consists of 2 major parts: the fraud detection analysis notebook and the dash app. 

[`dash`](https://github.com/lichunxiao9501/Fraud_Detection_Kaggle_Project/tree/main/dash) folder: this folder contains the python scripts and assets for the dash app.

[`notebooks`](https://github.com/lichunxiao9501/Fraud_Detection_Kaggle_Project/tree/main/notebooks) folder: this folder contains two notebooks [`EDA.ipynb`](https://github.com/lichunxiao9501/Fraud_Detection_Kaggle_Project/blob/main/notebooks/EDA.ipynb) and [`Fraud_Detection.ipynb`](https://github.com/lichunxiao9501/Fraud_Detection_Kaggle_Project/blob/main/notebooks/Fraud%20Detection.ipynb) and the [`Fraud_Detection.ipynb`](https://github.com/lichunxiao9501/Fraud_Detection_Kaggle_Project/blob/main/notebooks/Fraud%20Detection.ipynb) notebook contains the end to end fraud detection analysis.

### Fraud Detection Analysis

The fraud detection analysis contains 4 sections: 
* Data Cleaning; 
* Feature Engineering;
  - Missing values analysis
  - Dimensionality Reduction 
      1. for categorical variables, merge small levels 
      2. for numerical variables, PCA
* Fraud Detection Modelling
  - lightGBM;
  - XGBoost;
  - Hyperparameter fine-tuning + cross validation
* Feature Mmportance Analysis. 

### Dash App Screenshot

The dash app is coded in python and two screenshots are shown as follows.

![Screen Shot 1](/images/dash_screen_shot1.png)
![Screen Shot 2](/images/dash_screen_shot2.png)
