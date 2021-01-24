# Titanic
April 14, 1912, one of the well known tragedy Titanic happened. The legendary ship have sank after colliding into an iceberg. 
More than thousands of passengers have died during the incident. However, there are also some passengers that have survived from the disaster. 
Are those survivors survived base on luck? Or there is some characteristics on them that have helped them get through this disaster? 
Our main goal for this project will be using the passenger data (name, age, gender,…) to examine what kind of passenger is more likely to survive.

## Data Analysis
* Have a general idea on the data and figureing out simple relations between features and target.
<img src="https://github.com/yhhsu0409/Titanic/blob/master/ReadMe_Pic/sex_bar_plot.png" width="400" height="300">

## Feature Engineering
* Clean the feature for further Machine Learning (Fill in unknown, transform data into numbers, create new features...)
* Extract title from name and create new Title Feature
* Categorize into groups
<img src="https://github.com/yhhsu0409/Titanic/blob/master/ReadMe_Pic/clean_feature.png" width="350" height="250">

## Machine Learning
* Use the features to predict test group's survival
* Gridsearch, Decision Tree, Random Forest, KNN, Logistic Regression, SVC, Naive Bayes
* Result with a 79% accuracy
<img src="https://github.com/yhhsu0409/Titanic/blob/master/ReadMe_Pic/Predict%20Target.png" height="300">

## References
* Albon, C. (2018). Machine Learning with Python Cookbook: Practical Solutions from Preprocessing to Deep Learning (1st ed.). O’Reilly Media. 
* Minsuk Heo. (2017, October 22). Kaggle - Titanic Solution [Video]. YouTube. https://www.youtube.com/watch?v=COUWKVf6zKY
