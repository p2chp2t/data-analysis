# Kaggle Competition: Classification & Regression
- allowed to use one of the following options: Decision Trees, Rule-based Models, k-Nearest Neighbor, or Naïve Bayes Classifier. 
- machine learning libraries including sklearn, pytorch, etc. are fine, except for large language models![image](https://github.com/user-attachments/assets/a91ae4d6-e478-4af0-b529-3266981eb36b)

# Dataset - NBA player dataset
You will get the stats of the NBA player per year.
The dataset consists of personal statistics, such as the goals, assists, blocks, steals and more.
In the classification task, your goal is to predict the position of the player. (Column ‘position’ in csv file)
In the regression task, your goal is to predict the minutes played in a year. (Column “MIN” in csv file)
Summary
  Training set : 15000
  Test set : 2000
  Classification task class number : 6
  Regression task range of the label : 0 ~

# Evaluation
In the classification task, we will use Weighted F1 score for the evaluation metric.
In the regression task, we will use Mean Squared Error for the evaluation metric.
