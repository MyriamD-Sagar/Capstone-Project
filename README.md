# WGU Capstone-Project

## Bank Customer Attrition Prediction Application 
Stand-alone application developed using a Python programming environment for WGU Capstone project.  
The first part of this program consists of exploring and preprocessing the data through a dashboard, including visualization tools such as tables, graphs, and matrices.
These descriptive methods allow users to visualize and understand the relations and correlations between customers’ features. It also features the data preprocessing steps like handling missing values and categorical variables, splitting the data into training and test sets, and balancing the dataset.
Next, the dashboard presents the steps to develop and improve the prediction model utilizing a robust machine learning (ML) classification algorithm to generate predictions on customer attrition.
The subsequent portion of the application’s console consists of an analysis of the accuracy of the model presented using visualization tools.


The last section is the user interface.
It displays labeled text boxes where employees can input a customer’s information.
Then, the user has to click on the button “Predict” to produce an output label indicating whether the customer will stay or leave the bank.
This prediction is be possible because the developed model mentioned above has been integrated into the user interface. The classification algorithm is trained with the processed data, allowing it to generate a prediction using the user’s inputs.


## Application Files
The following provides a hierarchical list of the folders and files of the .zip file attached to the project’s submission.
* data – datasets folder
  * cleaned_data.csv
  * data_after_anomalies.csv
  * raw_data.csv
* figures – folder of the images loaded from the code file to display in the application file
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
* Application_Code.ipynb – Jupyter Notebook file (Data Product Code)
  * This file details the logic flow behind creating the “Bank_Attrition_Prediction_App.ipynb” file.
* Bank_Attrition_Prediction_App.ipynb – Jupyter Notebook file (Data Product)
  * This file contains the application for the users (bank employees), including visualizations and user interface.
* final_model.pkl – machine learning model loaded with pickle
* environment.yml – dependencies including libraries needed to recreate the environment


## User Guide 
This section provides well-defined steps to install and use the data product from a Windows 10 machine.
1. Extract the .zip file (capstone_project) attached to the project’s submission and note the directory’s path.
2. Download and install Miniconda for Windows (Python version 3.10) at this URL: https://docs.conda.io/projects/miniconda/en/latest/miniconda-other-installer-links.html#windows-installers
3. Open your Anaconda Prompt (Miniconda3)
4. Navigate to the directory noted in step 1.
5. Create your environment with environment.yml
To do so, type the following in your command prompt:
>conda env create --prefix ./env -f environment.yml
** Note: This may take several minutes depending on your machine.
6. Activate the environment you just created.
To do so, type the following in your command prompt:
>conda activate {path to your environment}
7. Open Jupyter Notebook by typing the following in your command prompt:
>jupyter notebook
8. Open the file named Bank_Attrition_Prediction_App.ipynb.
9. Read the Table of Contents to gain insights into the content of this notebook.
10. Run each cell of the notebook.
11. To make a prediction on customer attrition, navigate to “User Interface”.

