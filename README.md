# Pre-Task
# Dependencies
The following libraries and packages are required to run the code: <br>

1.pandas <br>
2.numpy <br>
3.scikit-learn <br>
4.seaborn <br>
5.matplotlib <br>

# Approach

1.Import the required libraries and modules. <br>
2.Read the training and test data from CSV files. <br>
3.Perform exploratory data analysis by inspecting the data and visualizing the target variable distribution. <br>
4.Preprocess the data by handling missing values using SimpleImputer, encoding categorical features using LabelEncoder and One-Hot Encoding, and aligning the <br> 
  features. <br>
5.Split the preprocessed data into training and validation sets using train_test_split. <br>
6.Visualize the encoded training data using t-SNE. <br>
7.Train a Random Forest Classifier model on the training set and evaluate its performance on the validation set. <br>
8.Make predictions on the test set using the trained Random Forest Classifier model and save the results to a CSV file. <br>
9.Perform cross-validation on the Random Forest Classifier model and print the scores. <br>
10.Train the Random Forest Classifier model on the entire training set. <br>
11.Make predictions on the test set using the trained Random Forest Classifier model and save the results to a separate CSV file. <br>
12.Train and evaluate K-Nearest Neighbors (KNN) classification models with different values of k. <br>
13.Choose the best k based on validation performance and make predictions on the test data using the selected k. <br>
14.Create a prediction dataframe and save the results to a CSV file. <br>

# Commands to Run the Project
To run the project, you can follow these steps: <br>

Ensure that the required libraries are installed. <br>
Place the train.csv and test.csv files in the same directory as the script.py file. <br>
Run the script.py file using a Python interpreter. <br>
The script will generate prediction files (test_predictions1.csv, test_predictions2.csv, test_predictions3.csv) and display output on the console. <br>
