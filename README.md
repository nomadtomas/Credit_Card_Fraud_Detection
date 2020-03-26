# Credit Card Fraud Detection
<p align="center">
  <img src="../images/cc_fraud.jpg">
</p>

## Table of Contents

* [General Information](#general-information)
    * [Data](#data)
    * [EDA](#eda)
* [Technologies](#technologies)
    * [Python](#python)
    * [Visualization](#visualization)
* [Future Improvements](#future-improvements)


## General Information
As we move more and more towards a cashless society, fraud detection will become increasingly important.  According to Shift Processing it is estimated that approximately $24.26 Billion dollars was lost due to payment card fraud worldwide.  It is a definite problem that needs to be addressed.  Luckily, there is such a thing as machine learning that can create a strong defense against such crimes.  I have taken a Kaggle dataset and utilized a random forest classification model to take on this problem.     

### Data:
<p align="center">
  <img src="images/realtylogos.png">
</p>

Data used for this analysis was gathered from kaggle. https://www.kaggle.com/mlg-ulb/creditcardfraud.

The datasets contains transactions made by credit cards in September 2013 by european cardholders. 
These transactions occurred in two days, where we have 492 frauds out of 284,807 transactions.  This is undoubtedly a highly imbalanced dataset. Due to confidentiality issues, the file contains only numerical input variables which are the result of a PCA transformation. 

### EDA:



## Technologies
<p align="center">
  <img src="../images/ml.jpg">
</p>

###### Python:
Data Analysis: Python 3, Numpy, Pandas, Scikit-Learn, Scipy<br>

###### Visualization:
Data Visualization: Matplotlib, Seaborn

## Future Improvements
• Implement a more robust feature selection method, perhaps backwards elimination<br>
• Try Gridsearch to find optimal hyperparameters.<br>
• Incorporate other models, like logistic regression and/or XGBoost<br>

