# Credit Risk Analysis
## Analysis Overview

The purpose of this analysis is to demonstrate skills in data preparation, statistical reasoning, and machine learning. In this project, we use Python to evaluate machine learning models to predict credit risk.

## Results
![](https://raw.githubusercontent.com/Daisyzhao21/Credit_Risk_Analysis/main/1.png)


- The high_risk precision is about 1% only with 63% sensitivity which makes a F1 of 2% only.
Due to the high number of the low_risk population, its precision is 99% with a sensitivity of 63%.


![](https://raw.githubusercontent.com/Daisyzhao21/Credit_Risk_Analysis/main/2.png)



- The results are pretty similar to the previous model.
With the high_risk precision is about 1% only with 69% sensitivity which makes a F1 of 1% only.
Due to the high number of the low_risk population, its precision is almost 99% with a sensitivity of 40%.

![](https://raw.githubusercontent.com/Daisyzhao21/Credit_Risk_Analysis/main/3.png)

- The high risk precision is about 1% with 72% sensitivity. The low risk precision is 99% with 58% sensitivity.

## Summary

In the report we have reviewed the results from sampling algorithms and ensemble algorithms to predict credit risk. The balanced random forest classifier algorithm has achieved the highest balanced accuracy score, and it also has a high precision rate of 0.06 for detecting high risk loans compared to a 0.01 for the sampling algorithms. The algorithm scored better in other metrics as well.

The balanced random forest classifier algorithm is recommended.
