Logistic Regression machine learning model

Step1: Importing the depandancies
       import numpy - numpy contains a large number of various mathematical operaions, arithmetic operations,handling comlex numbers, etc
       import pandas - pandas is a library written for the python programming language for data manipulation and analysid.
       import train_test_split - It splits the data into training dataset and test dataset. 
       import LogisticRegression - Its a machine learning model used to predict a data value based on prior observations of a dataset
       import accuracy_score - it is used for evaluation of the model.

Step2: Data collection and analysis
       pd.read_csv-Load the candidate Evaluation dataset
       .head()-print the first 5 rows.
       .shape-check the number of rows and columns in the dataset.
       .describe()-Get the statistical measures of the data.
       .value_counts()-counts the different labels which are present in that column.
        Separate the data and labels.
        Print the data and labels.

Step3: Train-Test-Split
       Split the data into training data and test data.
       Take 10% data in test data
       Print the data and labels of training data.

Step4: Training the model
       Input the LogisticRegression model.
       Fit the training data

Step5: Model Evaluation
       Check the accuracy of the training data.
       Check the accuracy of the test data.

Step6: Making a prediction system