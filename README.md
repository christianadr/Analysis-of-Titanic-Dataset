# Analysis-of-Titanic-Dataset
# Titanic - Machine Learning from Disaster (Beginner's Approach)
### Overview
The data has been splitted into two csv files:

train.csv
test.csv

According to the given instructions, the training set should be used to build the machine learning model. On the other hand, the test set will be used to see how well the model performs on unseen data. Moreover, the predictions must be saved in another csv file.

Variable notes
pclass: A proxy for socio-economic status

1 = Upper Class
2 = Middle Class
3 = Lower Class
age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

sibsp: The dataset defines family relations in this way... Sibling = brother, sister, stepbrother, stepsister Spouse = husband, wife (mistresses and fiancés were ignored)

parch: The dataset defines family relations in this way... Parent = mother, father Child = daughter, son, stepdaughter, stepson Some children travelled only with a nanny, therefore parch=0 for them.

Workflow for predicting
* Importing datasets
* Analyze the train dataset
* Analyze the test dataset
* Handling Null Values
* Analyze descriptive statistics
* Analyze Features through visualizations
* Correlation Analysis
* Data Preprocessing
* Model Training and Evaluation
* Conclusion
* Importing predicted values to submission.csv
