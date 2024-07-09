# Earthquake Magnitude Prediction

## Overview
This repository contains code for predicting earthquake magnitudes using machine learning algorithms: Linear Regression (LR), Support Vector Regression (SVR), and Random Forest Regression (RFR). The project focuses on exploring and comparing these algorithms to determine the most effective approach for earthquake magnitude prediction.

## Dataset
The prediction models are trained and evaluated on the **Earthquake Data.csv** dataset, which includes historical earthquake data with features such as location, depth, and other seismic attributes. The dataset is preprocessed to handle missing values and ensure compatibility with the machine learning models.

## Code Files
- **model_comparision.ipynb**: This Jupyter Notebook file contains the Python code used for loading the dataset, implementing the machine learning models, and comparing their performance for earthquake magnitude prediction.

## Usage
1. Clone the repository:
   ```
   git clone <repository_url>
   ```
   
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
   
3. Open and run **model_comparision.ipynb** in Jupyter Notebook or Jupyter Lab to explore the code, train the models, and analyze the results.

## Results
Random Forest Regression (RFR) was found to be the most effective algorithm for predicting earthquake magnitudes based on the comparative analysis performed in this project. Detailed performance metrics and visualizations can be found within the Jupyter Notebook.
