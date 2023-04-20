# Financial-Payment-Fraud-Detection
Financial Payment Fraud Detection System implemented using a Deep Neural Network (DNN).

The system is trained on a dataset that contains information about financial transactions, including the type of transaction, the amount, and the balance before and after the transaction, among other features. The goal of the system is to predict whether a given transaction is fraudulent or not.


Dataset - https://www.kaggle.com/datasets/arunavakrchakraborty/financial-payment-services-fraud-data

API Command - kaggle datasets download -d arunavakrchakraborty/financial-payment-services-fraud-data

![image](https://user-images.githubusercontent.com/58546519/233363477-b9254137-b23f-4818-8f95-843dfbb65f80.png)



The implementation involves loading the dataset and preprocessing it by dropping unnecessary columns, converting categorical variables to numerical variables, and normalizing the data. The preprocessed data is then split into training and testing sets, and a DNN model is trained on the training set using the Keras API with TensorFlow as the backend.


The trained model is evaluated on the testing set and the accuracy is reported. A confusion matrix is also created to visualize the performance of the model in terms of true positives, true negatives, false positives, and false negatives.
