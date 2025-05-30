# Day-4

Performing Logistic Regression on Breast Cancer Detection.

Steps:-
1. Imported the data and preprocessed it.
2. Encoded the output variable diagnosis. Benign - 0 and Malignant - 1.
3. Split the data into training, validation and test data to hypertune the parameters like C,threshold and max_iterations by using validation data.
4. Chose the best model based on recall score as False Negatives must be reduced => Recall must be high.
5. Performed the evaluation metrics using the values predicted by the best model on the test data.
