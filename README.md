# SC1015-Mini-Project

## Overview

This repository contains the project files for SC1015 Mini-Project.

Students normally experience a huge jump when transitioning from tertiary education to university. Hence, our machine learning aims to predict how well students can cope in university based on their various backgrounds so that students and teachers both know what to expect, to enable targeted interventions that can help reduce dropout rates and enhance student performance.

Here is a brief overview of our source code:
1. Reclassificaion & Dataset Cleaning
2. Exploratory Data Analysis / Visualization
3. Implementing Machine Learning Models
4. Conclusion

## Contriibutors
@jangasd - Data Visualization, Classification Tree, Dataset Cleaning

@carwynyeo- Linear Regression, Random Forest Regressor, Gradient Boosting, Dataset Cleaning

@dinitrophenol- Data Visualization, Classification Tree, Dataset Cleaning

## Problem Definition
Dropout Prediction: Can we classify students into those likely to drop out vs. those who will continue their education?

Academic Success Prediction: Can we predict the GPA, graduation likelihood, or other academic success indicators at the end of their course or semester?

## Models Tested
1. Linear Regression
2. Random Forest Regression
3. Gradient Boosting on Random Forest Regression
4. Classification Tree

## Conclusion
Our Project concludes with the following insights:

First, our linear regression model to predict students' grades in the first year of university was relatively successful, comparing the three models we used, achieving a low MSE of estimatedly 1.57. We could use our model to predict the academic performance of students entering their freshman year of university.

Second, our classification models using the students' backgrounds and acdemic grades separately acheiving varying results, has allowed us to conclude that using students'current academic performance in university is more effective in predicting whether a student will drop out or not as compared to their background.

Hence, using the results we have gathered from our models, we can predict a student's performance in the first year of university, which allows us to pinpoint students' who are likely to struggle in their freshmen year and we also can use our classfication model, to identify students who are most likely to drop out. This would allow the school to administer help to them earlier, (either academic/mental/etc) so that they will do better and become less likely to drop out. Which would help reduce number of university students who drop out. Resolving our problem definition.

## What did we learn?
* Reclassification of data
* Random Forest Regression
* Gradient Boosting
* K-Fold Cross Validation for evaluating models
* Collaborating on GitHub
* F1 Score, Precision, Recall

## References
https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success

https://educationdata.org/college-dropout-rates#:~:text=College%20dropout%20rates%20indicate%20that,up%20to%2040%25%20drop%20out

https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html

https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html

https://www.mdpi.com/2306-5729/7/11/146





