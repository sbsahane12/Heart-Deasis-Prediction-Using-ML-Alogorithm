# Heart-Deasis-Prediction-Using-ML-Alogorithm
# [Project  8: Heart Deasis Prediction Using ML Alogorithm](https://github.com/sbsahane12/Machine-Learning-Projects-for-2023.git) 
## Problem Statement
We have a data which classified if patients have heart disease or not according to features in it. We will try to use this data to create a model which tries predict if a patient has this disease or not. We will use logistic regression (classification) algorithm.
## Steps :
- Data Inspection – Missing Values if any, EDA
- Outlier Analysis
- Data Pre-processing
- Finding Optimal number of Clusters
- Modelling
- 
Data contains:
* age - age in years 
* sex - (1 = male; 0 = female)
* cp - chest pain type
* trestbps - resting blood pressure (in mm Hg on admission to the hospital) 
* chol - serum cholestoral in mg/dl
* fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false) 
* restecg - resting electrocardiographic results
* thalach - maximum heart rate achieved
* exang - exercise induced angina (1 = yes; 0 = no) 
* oldpeak - ST depression induced by exercise relative to rest
* slope - the slope of the peak exercise ST segment 
* ca - number of major vessels (0-3) colored by flourosopy
* thal - 3 = normal; 6 = fixed defect; 7 = reversable defect  
* target - have disease or not (1=yes, 0=no)
* 
## Install
This project requires Python 3.6 and the following libraries installed:
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/)
## Conclusion : 
- Our models work fine but best of them are KNN and Random Forest with 88.52% of accuracy. Let's look their confusion matrixes.
