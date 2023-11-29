# Capstone-Project

## Bank Customer Attrition Prediction Application

This project was completed for the Computer Science Capstone - C964 course at WGU.

The goal of this project was to develop and implement a stand-alone, intuitive, and interactive program that can predict customer attrition with an accuracy rate equal to or exceeding 95%.


Application Version: 1.0

Date: 9/23/2023

## Dataset

https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers

## Description
1. Exploratory Data Analysis
   * Data Preprocessing
   * Data visualization and analysis   
3. Model Development
   * Choosing the model
   * Improving the model
   * Build the model     
4. Accuacy analysis
   * Classification report
   * Confusion matrix
   * ROC curve
   * Evaluation metrics scores
   * Cross-validation
   * Feature importance 
5. User Interface

## Application Files
The following provides a hierarchical list of the folders and files of the .zip file attached to the project’s submission.

**data – datasets folder**

  * cleaned_data.csv
  * data_after_anomalies.csv
  * raw_data.csv

**figures – folder of the images loaded from the code file to display in the application file**

  * age-distribution.png
  * card-bar.png
  * confusion-matrix.png
  * correlation-matric.png
  * cross-validated-graph.png
  * education-bar.png
  * feature-importance.png
  * gender-bar.png
  * income-bar.png
  * marital-bar.png
  * roc-curve-display.png
  * scatter1-transaction.png
  * scatter2-transaction.png
  * scatter3-avg-usage-ratio.png
   
 **Application_Code.ipynb – Jupyter Notebook file (Data Product Code)**
 
  * This file details the logic flow behind creating the “Bank_Attrition_Prediction_App.ipynb” file.
  
**Bank_Attrition_Prediction_App.ipynb – Jupyter Notebook file (Data Product)**

  * This file contains the application for the users (bank employees), including visualizations and user interface.
    
**final_model.pkl – machine learning model loaded with pickle**

**environment.yml – dependencies including libraries needed to recreate the environment**


## User Guide 
This section provides well-defined steps to install and use the data product from a Windows 10 machine.

1. Download this repo and note the directory's path.
2. Download and install Miniconda for Windows (Python version 3.10) at this URL: https://docs.conda.io/projects/miniconda/en/latest/miniconda-other-installer-links.html#windows-installers
3. Open your Anaconda Prompt (Miniconda3)
4. Navigate to the directory noted in step 1.
5. Create your environment with environment.yml
To do so, type the following in your command prompt:
>conda env create --prefix ./env -f environment.yml
*Note: This may take several minutes depending on your machine.*
6. Activate the environment you just created.
To do so, type the following in your command prompt:
>conda activate {path to your environment}
7. Open Jupyter Notebook by typing the following in your command prompt:
>jupyter notebook
8. Open the file named Bank_Attrition_Prediction_App.ipynb.
9. Read the Table of Contents to gain insights into the content of this notebook.
10. Run each cell of the notebook.
11. To make a prediction on customer attrition, navigate to “User Interface”.

