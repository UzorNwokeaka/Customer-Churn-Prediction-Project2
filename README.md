## Customer-Churn-Prediction-Project2

A customer churn machine learning prediction model which will help reduce customer attrition, enhance customer loyalty and ensure Connecttel maintains a solid edge in the highly dynamic & competitive telecommunication industry (updated).

In this project, I analyzed, classified and predicted churn customers for a telecoms company using various algorithms under supervised machine learning. 

## Resources 

•	Data Source: Data of a global telecommunications company containing 7,043 records and 21 features. 

•	Python version: 3.11.4

•	Libraries: numpy, pandas, matplotlib, seaborn, sklearn.

## Data Cleaning

•	Converted irregularities (‘ & ‘ ‘) to NaN

•	Converted NaN values to mean values under the TotalCharges feature

•	Converted TotalCharges feature from object to int.

## Feature Engineering 

•	Performed feature extraction by dropping-off unwanted features – CustomerID, Churn, SeniorCitizens_Group, Tenure_Group

•	Performed feature construction by creating a new numeric feature – Churn_Type

•	Performed feature selection by selecting and converting all categorical features to numeric with exception of the five features above 

•	Performed feature scaling using the labelEncoder function as well as normalization by employing the MinMaxScaler function.


## Class Imbalance 

•	Employed the SOMTE technique to address class imbalance & balance distribution within the minority class


## Modeling 

•	Built eight (8) models and selected the top performing four (3) models.

•	In line with project outcome, I selected the best performing model out of the top three because of the required metrics for the business – Precision & Recall scores. 


## Hyperparameter Tuning 

•	Hyperparameter tuning was also performed on the selected model (Random Forest Classifier) to optimize the model's performance metrics and also make it suitable to be applicable to real-world business cases with class imbalance. 


## Some Insights from the EDA


![output_94_0](https://github.com/UzorNwokeaka/Customer-Churn-Prediction-Project2/assets/128752357/82f6f206-01e6-481f-b905-85e0d879a004)


![output_98_0](https://github.com/UzorNwokeaka/Customer-Churn-Prediction-Project2/assets/128752357/1d4c9908-70a7-4fd4-9eae-5ca564cfcb4f)


![output_52_1](https://github.com/UzorNwokeaka/Customer-Churn-Prediction-Project2/assets/128752357/b97f8fa1-d721-4986-b5a5-19e203b582a5)


![output_115_0](https://github.com/UzorNwokeaka/Customer-Churn-Prediction-Project2/assets/128752357/081cd377-f6fb-46ac-b175-6967220ebd19)


![output_153_0](https://github.com/UzorNwokeaka/Customer-Churn-Prediction-Project2/assets/128752357/963c0aea-e5bc-479b-8e3d-2fd083cfb8c2)




