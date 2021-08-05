<p align="center">
  <img src="./readme_files/ibm_logo.png"  width="500" height="200">
</p>

# IBM HR Analytics Employee Attrition
## Project Summary
With the rise of Data Science over the past few years, companies are finding more ways to apply machine learning methods internally. One such way is People Analytics. People Analytics is a data driven way for companies to better understand and manage their employees. It comes as no surprise that IBM is one company that focuses on People Analytics. The focus of this project was on figuring out what causes IBM employees to feel attrited and to create a predictive model that classifies attrited employees. 

## [Data](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset)
The dataset used for this project comes from Kaggle, but originally provided by IBM.

## [Data Wrangling/Cleaning](https://github.com/isabelanyc/Springboard/blob/main/IBM_Employee_Attrition/notebooks/data_wrangling.ipynb)
Luckily, the data was very friendly as-is. There were no missing values or duplicates. However, there was a mix of numerical and categorical features, which was later dealt with in the preprocessing phase. 

## [EDA](https://github.com/isabelanyc/Springboard/blob/main/IBM_Employee_Attrition/notebooks/eda.ipynb)

## [Preprocessing](https://github.com/isabelanyc/Springboard/blob/main/IBM_Employee_Attrition/notebooks/preprocessing.ipynb)

## [Modelling](https://github.com/isabelanyc/Springboard/blob/main/IBM_Employee_Attrition/notebooks/modelling.ipynb)
In the modelling portion of this project, 5 models differnt were compared, using `RandomizedSearchCV` and 5-fold cross validation.
* K Nearest Neighbor
* Decision Tree
* Random Forest
* Gradient Boosting
* Logistic Regression

## Results
