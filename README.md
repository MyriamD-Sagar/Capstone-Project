# Capstone-Project
## Context/Problem Statement 
At Sunrise Bank, we have earned a well-deserved reputation in the banking industry. For more than 30 years, we have been delivering outstanding customer services and unlimited dedication to the financial well-being of our communities.
However, data analytics have shown that our customer attrition rate has climbed from 4.2% to almost 7% over the last year.
While not yet alarming, this rate reflects that our loyal customer base is evolving, and its expectations are changing. Our company must take proactive actions to retain its valued clientele and safeguard its revenue streams.


The proposed project consists of designing, developing, implementing, and maintaining a stand-alone program that can predict customer attrition. It will offer an intuitive dashboard, utilizing informative tools to visualize customers’ data like graphs, tables, and matrices.
More importantly, the application will feature an interactive user interface for employees to input customers’ information to predict whether the customer will stay or leave Sunrise Bank.
This prediction will rely on an integrated machine-learning classification algorithm to achieve the highest possible accuracy rate.


Implementing a stand-alone, intuitive, and interactive program that can predict customer attrition with an accuracy rate equal to or exceeding 95% will reduce customer attrition while maintaining our company’s profits.
Furthermore, by enabling a way to predict customer attrition, our business can focus on keeping high-value customers by adjusting our offers to their needs.
Additionally, this tool will allow our employees to make data-driven decisions promptly and quickly and proactively engage with at-risk customers to prevent them from leaving.


## Application Description 
The data product delivered at the end of this proposed project will be a stand-alone application developed using a Python programming environment. 
The first part of this program consists of exploring and preprocessing the data through a dashboard, including visualization tools such as tables, graphs, and matrices.
These descriptive methods allow users to visualize and understand the relations and correlations between customers’ features. It will also feature the data preprocessing steps like handling missing values and categorical variables, splitting the data into training and test sets, and balancing the dataset.
Next, the dashboard will present the steps to develop and improve the prediction model utilizing a robust machine learning (ML) classification algorithm to generate predictions on customer attrition.
The subsequent portion of the application’s console will consist of an analysis of the accuracy of the model presented using visualization tools.


The last section is the user interface.
It will display labeled text boxes where employees can input a customer’s information.
Then, the user will have to click on the button “Predict” to produce an output label indicating whether the customer will stay or leave the bank.
This prediction will be possible because the developed model mentioned above has been integrated into the user interface. The classification algorithm


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
