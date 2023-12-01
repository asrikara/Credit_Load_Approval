# Credit_Load_Approval

Overview
This project focuses on building a credit scoring model using data from two CSV files: application_record.csv and credit_record.csv. The goal is to predict the credit status of individuals based on various features from their application records and credit history.

Project Structure
The project is organized into the following sections:

Importing Libraries and Data:

The necessary Python libraries, including Pandas, NumPy, Seaborn, Matplotlib, and scikit-learn, are imported.
Two datasets, application_record.csv and credit_record.csv, are read into Pandas DataFrames.
Data Preprocessing:

Label encoding is applied to categorical columns in the application_record DataFrame.
The STATUS column in the credit_record DataFrame is mapped to binary values.
The two DataFrames are merged on the 'ID' column.
Exploratory Data Analysis (EDA):

Histograms, correlation matrices, and pair plots are generated to explore the distribution of features and relationships between variables.
Model Development:

The dataset is split into training and testing sets.
A Decision Tree Classifier is trained on the data.
Hyperparameter tuning is performed using GridSearchCV to optimize the model.
Model Evaluation:

The accuracy score, classification report, and confusion matrix are used to evaluate the model's performance.
Feature importances are visualized.
Decision Tree Visualization:

The Decision Tree is visualized using the plot_tree function.
Pruned Decision Tree:

A pruned version of the Decision Tree with limited depth is visualized.
Feature Importance:

Feature importances are visualized to highlight the most influential variables.
