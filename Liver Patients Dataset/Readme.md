# Predicting Liver Disease

Predicting Liver Disease:
The given dataset is related to Indian patients who have been tested for a liver disease. Based on chemical compounds (bilrubin,albumin,protiens,alkaline phosphatase) present in human body and tests like SGOT, SGPT the outcome mentioned is whether person is a patient i.e, whether he needs to be diagnosed further or not.

Objective:
Perform data cleansing, and required transformations and build a predictive model which will be able to predict most of the cases accurately.

Attributes:
Following are the feature names for the given data: Age, Gender, Total_Bilirubin, Direct_Bilirubin, Alkaline_Phosphotase, Alamine_Aminotransferase, Aspartate_Aminotransferase, Total_Protiens, Albumin, Albumin_and_Globulin_Ratio, Class

Some og the methods involved - 
1. Treating outliers
2. Checking Correlation or multi-collinearity among numeric columns
3. Scaling the data
4. Checking type 2 error and type 1 error to decide the cut-off

Concluding that type 2 error is more fatal as it tells that one has a disease and predicted as doesnt have the disease. Deciding the cut-off based on this is very important

Models applied were - Logistic, SVC, Random Forest
