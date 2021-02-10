# Credit_Risk_Analysis

##### Overview of Analysis
In this challenge we will evaluate the performance of several machine learning models. We wiil then make a recommendation on whether they should be used to predict credit risk.

##### Results

* ##### Random OverSampler model
<p align="center">
  <img width="460" height="300" src="https://github.com/LManago/Credit_Risk_Analysis/blob/main/Images/oversampling%20model.PNG">
</p>
<p align="center">
  <img width="400" height="100" src="https://github.com/LManago/Credit_Risk_Analysis/blob/main/Images/oversampling%20model%20classification.PNG">
</p>
The balanced accuracy score is 63%.
The high risk precision is about 1% only with 59% sensitivity which makes a F1 of 2% only.
Due to the high number of the low risk population, its precision is almost 100% with a sensitivity of 68%.

* ##### SMOTE model
<p align="center">
  <img width="460" height="300" src="https://github.com/LManago/Credit_Risk_Analysis/blob/main/Images/Smote%20Model.PNG">
</p>
The balanced accuracy score is 64%.
The high risk precision is about 1% only with 67% sensitivity which makes a F1 of 2% only.
Due to the high number of the low risk population, its precision is 100% with a sensitivity of 63%.

* ##### ClusterCentroids model
<p align="center">
  <img width="460" height="300" src="https://github.com/LManago/Credit_Risk_Analysis/blob/main/Images/cluster%20model.PNG">
</p>
Here the balanced accuracy score is down to about 52%.
The high risk precision is still 1% only with 62% sensitivity which makes a F1 of 1%.
Due to the high number of false positives, the low risk sensitivity is only 42%.

* ##### SMOTEEN model
<p align="center">
  <img width="460" height="300" src="https://github.com/LManago/Credit_Risk_Analysis/blob/main/Images/smoteenn%20model.PNG">
</p>
The balanced accuracy score is about 62%.
The high_risk precision is still 1% only with 67% sensitivity which makes a F1 of only 2%.
Due to the high number of false positives, the low risk sensitivity is 57%.

* ##### Balanced Random Forest Classifier model
<p align="center">
  <img width="400" height="100" src="https://github.com/LManago/Credit_Risk_Analysis/blob/main/Images/balancedrandomcalcbalscore.PNG">
</p>
<p align="center">
  <img width="400" height="100" src="https://github.com/LManago/Credit_Risk_Analysis/blob/main/Images/balancedrandomclassrepo.PNG">
</p>
The balanced accuracy score improved to about 79%.
The high risk precision is still low at 4% only with 67% sensitivity which makes a F1 of only 7%.
Due to a lower number of false positives, the low risk sensitivity is now 91% with 100% presicion.

* ##### Easy Ensemble Classifier model
<p align="center">
  <img width="400" height="100" src="https://github.com/LManago/Credit_Risk_Analysis/blob/main/Images/ensembledcalcbalancedaccscore.PNG">
</p>
<p align="center">
  <img width="400" height="100" src="https://github.com/LManago/Credit_Risk_Analysis/blob/main/Images/ensembleimbalancedreport.PNG">
</p>
Now, the balanced accuracy score is high to about 93%.
The high risk precision is still low at 7% only with 91% sensitivity which makes a F1 of only 14%.
Due to a lower number of false positives, the low risk sensitivity is now 94% with 100% presicion.

##### Summary
I would not recommend the bank to use any of these models to predict credit risk because the models used to perform the credit risk analysis show weak precision in determining if a credit risk is high. 


