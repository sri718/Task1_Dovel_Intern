# Task1

## 1. Data Aquisition:  
  1.1 Imported Kaggle and Os libraries, and using Kaggle API, downloaded the dataset if it is not already downloaded.  

## 2. Importing Necessary Libraries:
  ### 2.1 Imported Libraries are,
      1. pandas for Data Analysis and Manipulation.  
      2. numpy to find mean.  
      3. sklearn.lineat_model to import LinearRegression.  
      4. sklearn.svm to import SVC.  
      5. sklearn.tree to import DecisionTreeClassifier.  
      6. sklearn.ensemble to import RandomForestClassifier.  
      7. skleatn.model_selection to import train_test_split and cross_val_score.  
      8. sklearn.metrics to import mean_absolute_error, means_squared_error for Regression.  
      9. sklearn.metrics to import accuracy_score, precision_score, recall_score, f1_score, confusion_matrix, clasiification_report for Classifications.  
      10. matplotlib and seaborn to plot.  

## 3. Read CSV and Data Preprocessing:
3.1 Read CSV (Downloaded Dataset) using pandas(pd.read_csv()).  
3.2 Fill the missing values, here we used fillna() to do it.  
3.3 Normalize/Scale the numerical column if needed(not here).  
3.4 Transform the categorical column to numerical column if needed(not here).  

## 4. Model Development and Analytics:
### 4.1 Linear Regression:
4.1.1 Create an object of a class LinearRegression() (model - Object).  
4.1.2 Defined the Features and Target.  
4.1.3 Splited the Original data to Train and Test Data using train_test_split.  
4.1.4 Fit the Train data to the model.  
4.1.5 Predict with Test data.  
4.1.6 Calculate the MAE and MAE.  
4.1.7 Plot(Scatter) the result.  

## 4.2 Support Vector Classifier:
4.2.1 Create an object of a class SVC() (model - Object).  
4.2.2 Defined the Features and Target.  
4.2.3 Splited the pd.cut() data to Train and Test Data using train_test_split.  
4.2.4 Fit the Train data to the model.  
4.2.5 Predict with Test data.  
4.2.6 Calculate the accuracy, precision, recall, f1 score, confusion matrix and cross validation score.  
4.2.7 Give the classification report  
4.2.8 Plot(Heatmap - Confusion Matrix) the result.  

## 4.3 Decision Tree Classifier:  
4.3.1 Create an object of a class DecisionTreeClassifier() (model - Object).  
4.3.2 Defined the Features and Target.  
4.3.3 Splited the pd.cut() data to Train and Test Data using train_test_split.  
4.3.4 Fit the Train data to the model.  
4.3.5 Predict with Test data.  
4.3.6 Calculate the accuracy, precision, recall, f1 score, confusion matrix and cross validation score.  
4.3.7 Give the classification report  
4.3.8 Plot(Heatmap - Confusion Matrix) the result.  

## 4.4 Random Forest Classifier:
4.4.1 Create an object of a class RandomForestClassifier() (model - Object).  
4.4.2 Defined the Features and Target.  
4.4.3 Splited the pd.cut() data to Train and Test Data using train_test_split.  
4.4.4 Fit the Train data to the model.  
4.4.5 Predict with Test data.  
4.4.6 Calculate the accuracy, precision, recall, f1 score, confusion matrix and cross validation score.  
4.4.7 Give the classification report  
4.4.8 Plot(Heatmap - Confusion Matrix) the result.  

## 5. Model Evaluation and Selection:
5.1 Calculate the Performance of each model using accuracy and cross validation score.  
5.2 Print the Model with the highest performance.
