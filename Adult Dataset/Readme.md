# Income Prediction

Click here to see full article - https://rpubs.com/Mr_President/income_prediction
The raw file is attached above

The main objective of the dataset is to classify people earning <=50k or >50k based on several explanatory factors affecting the income of a person like Age, Occupation, Education, etc. 

The methods we intend to use are: Binary Logistic Regression Decision Tree Random Forest. 

Data cleaning method used in this article is *kNN imputation using VIM library*

Visualizing to conclude that majority of the people make less than <50k a year and people earning >50k are in their mid career. We make this hypothesis based on the age.
We can conclude that people working in private sector earn significantly better than the ones in other classes

Using AUC-ROC curve to decide the threshold or cut-off for prediction
Also taking into account the significance of TPR and FPR
