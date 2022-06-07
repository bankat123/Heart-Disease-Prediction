# Heart-Disease-Prediction


Heart Disease Prediction using Data Mining Algorithms and Checking the Efficiency of Different Algorithms



### Dataset

We have used the dataset from the UCI repository from this website link This dataset gives several variables along with a target condition of having or not having heart disease. It contains 76 attributes, but all published experiments refer to using a subset of 14 of them.

#### Data Contains:


 age - age in years

sex - (1 = male; 0 = female)

cp - chest pain type

trestbps - resting blood pressure (in mm Hg on admission to the hospital)

chol - serum cholestoral in mg/dl

fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

restecg - resting electrocardiographic results

thalach - maximum heart rate achieved

exang - exercise induced angina (1 = yes; 0 = no)

oldpeak - ST depression induced by exercise relative to rest

slope - the slope of the peak exercise ST segment

ca - number of major vessels (0-3) colored by flourosopy

thal - 3 = normal; 6 = fixed defect; 7 = reversable defect

target - have disease or not (1=yes, 0=no)

### Table of Contents


1.Data Exploration and Visualizations

2.Data Preprocessing

3.Preparing ML models

4.Models evaluation

5.Ensembling

6.Conclusion

### ML models


Here I take different machine learning algorithms and try to find algorithms that predict accurately.

1. Logistic Regression

2. Naive Bayes

3. Random Forest Classifier

4. Extreme Gradient Boost

5. K-Nearest Neighbour

6. Decision Tree

7. Support Vector Machine

### Conclusion

We started with the data exploration where we got a feeling for the dataset, checked about missing data and learned which features are important. During this process, we used Plotly, seaborn and matplotlib to do the visualizations. During the data preprocessing part, we converted features into numeric ones, grouped values into categories and created a few new features. Afterwards, we started training machine learning models and applied cross-validation to them. Of course, there is still room for improvement, like doing a more extensive feature engineering, by comparing and plotting the features against each other and identifying and removing the noisy features. To increase the accuracy of the model we use ensembling. Here we use the stacking technique.. Lastly, we looked at its confusion matrix and computed the models precision.


```python

```
