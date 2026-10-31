# Genetic Disorder Risk Prioritization Platform

## About the Project

The Genetic Disorder Risk Prioritization Platform is a machine learning project. It is designed to study patient details and identify people who may have a higher risk of genetic disorders.

This project uses the XGBoost algorithm to study patient data and predict risk levels. It also helps to arrange patient records based on their risk.

The main aim of this project is to use machine learning to support healthcare data analysis.

## Project Objectives

- To study patient data using machine learning.
- To identify patients who may have a higher risk.
- To clean and prepare the data.
- To handle missing values in the dataset.
- To improve the prediction process.
- To help in patient risk prioritization.

## Technologies Used

- Python
- Machine Learning
- XGBoost
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Joblib

## How the Project Works

1. Collect patient data.
2. Check and clean the data.
3. Fill in missing values.
4. Convert text values into numbers.
5. Train the machine learning model.
6. Test different prediction thresholds.
7. Predict the risk level.
8. Arrange patient records based on risk.

## Data Preprocessing

Data preprocessing is done to prepare the dataset for the model.

The following methods are used:

1. Identifier Removal

   Unnecessary details such as Patient ID are removed from the dataset.

2. Missing Value Handling

   Missing category values are filled using the mode. Missing number values are filled using the median.

3. Label Encoding

   Text values are changed into numbers so that the machine learning model can process them.

## Machine Learning Algorithm

This project uses the XGBoost algorithm.

XGBoost is a machine learning algorithm used for classification. It helps the system study patient details and predict possible risk levels.

## Model Performance

Different probability thresholds are tested to find a suitable result.

| Threshold | Result |
|-----------|--------|
| 0.3 | Highest Recall with 47% detection rate |
| 0.4 to 0.5 | Balanced result |
| 0.7 | Highest Precision |

The default threshold is selected between 0.4 and 0.5. It provides a balance between finding possible risk cases and reducing false alerts.

## Main Features

- Predicts possible genetic disorder risk.
- Uses machine learning to study patient data.
- Handles missing values.
- Cleans unnecessary data.
- Finds high-risk patient records.
- Uses different thresholds to improve results.

## Future Improvements

- Improve prediction results.
- Add more patient data.
- Create better dashboards.
- Add more machine learning algorithms.
- Show clear reasons for predictions.
- Generate patient risk reports.

## Applications

- Healthcare data analysis.
- Genetic disorder research.
- Patient record analysis.
- Patient risk prioritization.

## Disclaimer

This project is developed for educational purposes only. The results are not medical diagnoses. They should not replace advice from doctors or medical tests.

## Project Details

Project Name: Genetic Disorder Risk Prioritization Platform

Domain: Artificial Intelligence and Machine Learning

Programming Language: Python

Algorithm: XGBoost

Project Type: Machine Learning Project

## Conclusion

This project shows how machine learning can be used in healthcare data analysis. It studies patient information and helps identify records that may need more attention.

The project aims to make patient risk analysis easier with the help of machine learning.
