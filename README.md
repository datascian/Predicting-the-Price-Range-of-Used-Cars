### CIND-820
# Predicting The Price Range Of Used Cars

## Description:

## Objectives:

## Steps:
1) Data cleaning and preprocessing. Includes one-hot encoding of categorical variables 
2) Exploratory Data Analysis 
3) Train-test split 
4) Modelling: 
    a) XGboost  
    b) Random Forest  
    c) Neural Networks  
5) Comparison of model performance 
6) Conclusion 

## The Data:

## Tools:

## EDA:

## Modelling:

  Preprocessing: Data cleaning and one-hot encoding of categorical variables

  EDA: Exploratory data analysis to get a general understanding of the data and visualize the data as well as the relationships of the different variables. 

  Train Test Split: Split the data into pandemic data and prepandemic data. The prepandemic data will be used to train the models. The prepandemic data is split into train and test. 

  XGboost: Model trained using XGBoost. The model had an F1-score of 67.60% using the prepandemic data. The performance went down to 54.72% when the model was used on the pandemic dataset. 

  Random Forest: Model trained using random forest. The model had an F1-score of 76.13% using the prepandemic data. The performance went down to 0.53.58% when the model was used on the pandemic dataset.
  
  Neural Networks: Model trained using neural networks. The model had an F1-score of 76.60% using the prepandemic data. The performance went down to 59.39% when the model was used on the pandemcid dataset.
  
  Retrained Neural Networks: The neural networks model was retrained with the combined pre-pandemic and pandemic dataset. The model had an F1-score of 74.71%. 

Link to dataset:
https://drive.google.com/drive/folders/1h3qnzHzk62q9C-J0KQCw4NqOaluTaIEX?usp=sharing  

