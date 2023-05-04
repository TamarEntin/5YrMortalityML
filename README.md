# Mortality Prediction Using Machine Learning

This project aims to predict whether a person will die in the next 5 years based on various medical parameters using machine learning. The data used in this project is a dataset of medical parameters of people that was provided.

## Data Preprocessing

Before building the machine learning model, the data was cleaned and preprocessed. This involved handling missing values and outliers, encoding categorical variables, and normalizing the numerical features. The data was then split into training and testing sets to evaluate the performance of the model.

## Model Building

The data was found to be imbalanced, where the number of people who died within the next 5 years was much smaller than those who did not. To overcome this issue, we used oversampling methods such as SMOTE (Synthetic Minority Over-sampling Technique) and ADASYN (Adaptive Synthetic Sampling) to balance the data.

Several machine learning algorithms were tested for this project, including logistic regression, random forest, and support vector machines (SVM). After careful consideration and analysis, we found that the Balanced Bagging Classifier was the optimal choice, delivering the best results when applied to clean and normalized data. This model was trained on the training data and evaluated on the testing data using various metrics such as accuracy, precision, and recall.
