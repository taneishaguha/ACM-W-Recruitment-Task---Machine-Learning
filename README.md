# TanACM-W

¬¬¬¬¬¬
# Logistic Regression and KNN for IRIS Dataset

This project applies Logistic Regression and K-Nearest Neighbour methods to solve the IRIS dataset using NumPy.
## Dataset
IRIS is a dataset in machine learning and contains measurements of four features of 3 species of Iris flowers. With the help of this project, we can preduct the species of an Iris based on its features.

## Software Components

Python | Numpy | scikit-learn
## Installation

Install the required libraries using pip commmand on Microsoft Powershell.

![image](https://github.com/taneishaguha/TanACM-W/assets/135737131/8fb4044e-6df2-45ba-bffd-2910f291278f)

## Usage

Import numpy and required datasets from sklearn

![image](https://github.com/taneishaguha/TanACM-W/assets/135737131/f4bfb3b3-972f-48be-80e7-46e71934233d)

Split the dataset into training and testing (20% testing and 80% training)

![image](https://github.com/taneishaguha/TanACM-W/assets/135737131/acb7544c-6067-4e5c-b803-0cebbd507a65)

For Logistic Regression:
An instance of the logistic regression model is created using the function LogisticRegression() from scikit-learn. The logistic regression model is then fitted to the training data using the fit() function, which learns the relationship between the features X_train and the target labels y_train. The logistic regression model is used to make predictions on the test data (X_test) using the predict() method. The predicted labels are stored in the logistic_predictions array. he accuracy score of the logistic regression model is printed to the console.

![image](https://github.com/taneishaguha/TanACM-W/assets/135737131/4cd2d9ea-1564-44f3-a92d-cdd2daabe92a)

For KNN:
An instance of the KNN classifier is created using KNeighborsClassifier() from scikit-learn. The KNN classifier is then fitted to the training data using the fit() method, which learns the patterns and relationships between the features X_train and the target labels y_train. he KNN classifier is used to make predictions on the test data (X_test) using the predict() method. The predicted labels are stored in the knn_predictions array. The accuracy score of the KNN classifier is printed to the console.

![image](https://github.com/taneishaguha/TanACM-W/assets/135737131/39b805c1-1d64-4f69-9f11-6cbaa6f3c0b1)

## Results
For Logistic Regression:
![image](https://github.com/taneishaguha/TanACM-W/assets/135737131/adfca7bc-5144-46ec-a366-b4c5afd1ff23)

For KNN:
![image](https://github.com/taneishaguha/TanACM-W/assets/135737131/9c225cca-6517-4732-84e7-5088b1605b43)

