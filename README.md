# ml-Py-used_cars
Building various classification Ensemble Models on used cars in the US to predict various nominal attributes

This repository includes the following projects:
1. Used_Car_Lab_1_DataVisualization
* Description: We wanted to build 3 different types of models on this dataset. First is Regression, second binary classification using Logistic Regression and third multiple classification using either K-nearest or K-means Random Forest depending on the best fit. We picked “Price” as the response feature for Regression model because it has numerical value and a pivotal point in the used car purchase. For Logistic Regression, we opted for “has_accidents” as the response variable because it has boolean values and an interesting point to observe whether we can effectively classify the used car with accidents. Finally, we used “body_type” as the target variable for multi-value classification. “Body_type” has 9 attributes which we believed a good candidate for multi-class classification.

2. Used_Car_Miniproject_SVM_LR_Classification
* Description: In this section we will continue using our used car dataset and be building out a classification model using Logistic Regression (LR), Support Vector Machines (SVM) and then optimizing these models using SGD (Stochastic Gradient Descent). In the following sections we have split up these areas into the following points:

3. Lab 2 - Group 2 - Used Cars Classification Models
* Description: In this exercise, we will be building on top of our Used_Car_Dataset we had analyized prior. The main goal we aim to address will be in modeling two of our nominal value attributes: 'Body_Type' and 'Has_Accidents'. We will use varying classification methods and techniques to evaluate if there are any significant differences in the models and ultimately decide on which model is best to use as a classifier.
