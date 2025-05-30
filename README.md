# Day-4

Performing Logistic Regression on Breast Cancer Detection.

Steps:-
1. Imported the data and preprocessed it.
2. Encoded the output variable diagnosis. Benign - 0 and Malignant - 1.
3. Split the data into training, validation and test data to hypertune the parameters like C,threshold and max_iterations by using validation data.
4. Chose the best model based on recall score as False Negatives must be reduced => Recall must be high.
5. Calculated the evaluation metrics using the values predicted by the best model on the test data and plotted the ROC Curve.

The Sigmoid activation function is used to map to a class based on its probability.
It is equal to 1/1+e^-z where z=wTx+w0 where w's are the weights parameters.
