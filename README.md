# BreastCancerDetection_VariousMLAIgorithm
ML Python Project

# Prediction
![](https://github.com/developer-venish/BreastCancerDetection_VariousMLAIgorithm/blob/main/prediction.png)

# Comparison
![](https://github.com/developer-venish/BreastCancerDetection_VariousMLAIgorithm/blob/main/comparison.png)

---------------------------------------------------------------------------------------

Note :- All the code in this project has been tested and run successfully in Google Colab. I encourage you to try running it in Colab for the best experience and to ensure smooth execution. Happy coding!

---------------------------------------------------------------------------------------

This code performs the following tasks:

1. It imports the required libraries: `pandas`, `numpy`, `pyplot` from `matplotlib`, and `files` from `google.colab`.
2. It uploads a CSV file named 'data.csv' using the `files.upload()` function.
3. It reads the CSV file into a Pandas DataFrame named `dataset`.
4. It performs some initial data exploration by printing the shape of the dataset and the first five rows.
5. It maps the values in the 'diagnosis' column from 'B' and 'M' to integers 0 and 1, respectively, and converts the column to the integer data type.
6. It separates the feature columns (X) and the target column (Y) from the dataset.
7. It splits the data into training and testing sets using the `train_test_split` function.
8. It performs feature scaling on the training and testing data using `StandardScaler`.
9. It defines a list of classification models to be evaluated: Logistic Regression, Linear Discriminant Analysis, K-Nearest Neighbors, Decision Tree, Gaussian Naive Bayes, and Support Vector Machine.
10. It performs k-fold cross-validation on each model and calculates the mean accuracy score.
11. It visualizes the performance of the models using a bar plot.
12. It creates a Logistic Regression model and fits it to the training data.
13. It predicts the target variable for a given input.
14. It prints the predicted values for the test set along with the actual values.
15. It creates another Logistic Regression model, fits it to the training data, and predicts the target variable for the test set.

Note: The code assumes that the dataset file 'data.csv' is available and contains the required columns for the analysis.
