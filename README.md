# Diabetes Predictor
This repository contains a Diabetes Predictor built using the Pima Indians Diabetes Dataset. The predictor is designed for early diagnosis of diabetes by analyzing the given features.

## Dataset
The Pima Indians Diabetes Dataset is a widely-used dataset for predicting diabetes. It consists of several medical features of female patients of Pima Indian heritage, including age, number of pregnancies, BMI, blood pressure, insulin level, and glucose concentration, among others. These features are used to predict whether a patient has diabetes or not.

## Model Architecture
The Diabetes Predictor utilizes an adapted Decision Tree Classifier for training and testing the model. The Decision Tree algorithm is a popular choice for classification tasks as it constructs a tree-like model of decisions based on the features. By analyzing the features in the dataset, the model makes predictions about the presence or absence of diabetes.

## Training and Testing
The model is trained using the Pima Indians Diabetes Dataset, where the features serve as inputs and the corresponding diabetes status serves as the target variable. During training, the model learns the patterns and relationships within the dataset to make accurate predictions.

The accuracy of the model is evaluated using both training and testing datasets. The training accuracy of 87% indicates how well the model fits the training data, while the testing accuracy of 70% provides an estimate of the model's performance on unseen data. It is worth noting that these accuracy values are specific to the dataset used and may vary when applied to different datasets.

## Usage
To use the Diabetes Predictor, you can provide the necessary input features for a patient, such as age, number of pregnancies, BMI, blood pressure, insulin level, glucose concentration, etc. The model will analyze the input and provide a prediction on whether the patient is likely to have diabetes or not.

Please refer to the code provided in this repository for detailed instructions on setting up the environment, training the model, and using it for diabetes prediction.

## Acknowledgments
This project utilizes the Pima Indians Diabetes Dataset, which has been made available by the original contributors. We would like to express our gratitude for providing this valuable dataset, enabling us to develop the Diabetes Predictor.