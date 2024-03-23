Multi-Class-Prediction-of-Obesity-Risk Model

Description
This dataset contains various factors that can be used to predict the risk of obesity in individuals, which is closely related to cardiovascular disease. 
The goal of this project is to develop machine learning models that can accurately predict obesity levels based on demographic information, lifestyle factors, and medical history.

Dataset
The dataset includes the following columns:

id: Unique identifier for each individual.
Gender: Gender of the individual (Male/Female).
Age: Age of the individual in years.
Height: Height of the individual in centimeters.
Weight: Weight of the individual in kilograms.
family_history_with_overweight: Whether the individual has a family history of overweight (Yes/No).
FAVC: Frequent consumption of high-caloric food (Yes/No).
FCVC: Frequency of consumption of vegetables (times per week).
NCP: Number of main meals per day.
CAEC: Consumption of food between meals (Always/Frequently/Sometimes/No).
SMOKE: Smoking habit of the individual (Yes/No).
CH2O: Daily water consumption in liters.
SCC: Calories consumption monitoring (Yes/No).
FAF: Physical activity frequency (times per week).
TUE: Time using technology devices (hours per day).
CALC: Consumption of alcohol (Always/Frequently/Sometimes/No).
MTRANS: Mode of transportation (Automobile/Bike/Motorbike/Public_Transportation/Walking).
NObeyesdad: Obesity level (Target variable: Insufficient_Weight/Normal_Weight/Overweight_Level_I/Overweight_Level_II/Obesity_Type_I/Obesity_Type_II/Obesity_Type_III).

Usage
Exploratory Data Analysis (EDA):

Explore the dataset to understand the distribution of features and identify any patterns or correlations.
Visualize relationships between variables using plots and charts.
Data Preprocessing:

Handle missing values, outliers, and anomalies in the dataset.
Encode categorical variables using one-hot encoding or label encoding.
Split the dataset into training and testing sets.
Model Development:

Choose appropriate machine learning algorithms for classification tasks.
Train predictive models using the training dataset.
Evaluate model performance using relevant metrics such as accuracy, precision, recall, and F1-score.
Model Deployment:

Deploy the trained model in a production environment for making predictions on new data.
Monitor model performance and update as necessary.

Evaluation Metric
The performance of predictive models will be evaluated based on their ability to accurately classify obesity levels.
