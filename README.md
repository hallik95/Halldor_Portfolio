# Halldór Portfolio
Examples from data science projects

# Machine Learning - Regression
## Project 1: Predicting CO2 emission with multiple linear regression & polynomial regression
* Dependent variable: CO2 Emission
* Independent variables: Engine size, Cylinders, Fuel Consumption (L/100 km)
![](/images/3DScatter_MR_CO2.png)
![](/images/Regression_MR_CO2.png)
![](/images/Poly_MR_CO2.png)

## Project 2: Predicting house prices with multiple linear regression
* Dependent variable: House price
* Independent variables: 
  * CRIM per capita crime rate by town 
  * ZN proportion of residential land zoned for lots over 25,000 sq.ft.
  * INDUS proportion of non-retail business acres per town, CHAS Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
  * NOX nitric oxides concentration (parts per 10 million)
  * RM average number of rooms per dwelling
  * AGE proportion of owner-occupied units built prior to 1940
  * DIS weighted distances to five Boston employment centres
  * RAD index of accessibility to radial highways
  * TAX full-value property-tax rate per $10,000
  * PTRATIO pupil-teacher ratio by town 
  * LSTAT % lower status of the population
  * MEDV Median value of owner-occupied homes in $1000's

![](/images/Heatmap_MR_Houseprice.png)
![](/images/Hex_MR_Houseprice.png)
![](/images/Regression_MR_Houseprice.png)

## Project 3: Predicting GDP with non-linear regression

![](/images/Non_MR_GDP.png)


# Machine Learning - Clasisfication
## Project 1: Classifying orthopedic patients through biomechanical features using KNN
* Dependent variable: 
   * Class
* Independent variables: 
   *  Pelvic incident
   *  Pelvic tilt numeric
   *  Lumber lordosis angle
   *  Sacral Slope
   *  Pelvic radius
   *  Degree spondylolisthesis

Implementation on research and data by Hasan, Islam, Samio, Chakrabarty (2018)
https://ieeexplore.ieee.org/document/8641042/

![](/images/Pairplot_KNN_Biomechanical.png)
![](/images/Accuracy_KNN_Biomechanical.png)
![](/images/Heatmap_KNN_Biomechanical.png)

## Project 2: Determining what drug should be taken using decision tree
* Dependent variable: 
   * Drug - Drug type choice
* Independent variables: 
   *  Age
   *  Sex
   *  BP - Blood pressure leveles
   *  Cholesterol
   *  Na_to_K - Sodium to potassium Ration in Blood

![](/images/Tree_DT_Drug.png)

## Project 3: Classifying bening and malignant tumors using Support Vector Machines (SVM)
* Dependent variable: 
   * Class	- Benign or malignant
* Independent variables: 
   *  Clump thickness
   *  Uniformity of cell size
   *  Uniformity of cell shape
   *  Marginal adhesion
   *  Single epithelial cell size
   *  Bare nuclei
   *  Bland chromatin
   *  Normal nucleoli
   *  Mitoses

![](/images/Class_SVM_Tumor.png)
![](/images/CM_SVM_Tumor.png)

## Project 4: Predicting customer churn with logistic regression


