# codeless-ai-ml-2022

# Overview
The project is a classification type project using a Stroke Prediction Dataset on Kaggle.

https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

In this project, we will determine which machine learning algorithm will be useful with this dataset.
<p float="left">
 <img src="img/1.png" alt="image" width="50%"/> 
</p>

# Tool
knime

# Nodes being used in KNIME
-CSV Reader

-Number to String

-Column Filter 

-Partitioning

-Naive Bayes Learner

-Naive Bayes Predictor

-Decision Tree Learner

-Decision Tree Predictor

-Logistic Regression Learner

-Logistic Regression Predictor

-Random Forest Learner

-Random Forest Predictor

-Scorer 

# Model
*1.Our dataset is in CSV format, so we need a CSV reader node to access it*
<p float="left">
 <img src="img/csv.png" alt="image" width="50%"/> 
</p>
using CSV Reader node for access data.

*2.Data Cleaning*
<p float="left">
 <img src="img/2.png" alt="image" width="50%"> 
</p>
Converts numbers in a column (or a set of columns) to strings. I use Column filter to remove columns that I don't need or are not important for use and use Partitioning to divide information, The first is for the ML to learn and the other is for the ML to test.

*3.classification model (Naive Bayes model)*
<p float="left">
 <img src="img/3.png" alt="image" width="50%"/> 
</p>
using Naive Bayes Learner node and Naive Bayes Predictor node.

*4.classification model (Decision Tree model)*
<p float="left">
 <img src="img/4.png" alt="image" width="50%"/> 
</p>
using Decision Tree Learner node and Decision Tree Predictor node.

*5.classification model (Logistic Regression model)*
<p float="left">
 <img src="img/5.png" alt="image" width="50%"/> 
</p>
using Logistic Regression Learner node and Logistic Regression Predictor node.

*6.classification model (Random Forest model)*
<p float="left">
 <img src="img/6.png" alt="image" width="50%"/> 
</p>
using Random Forest Learner node and Random Forest Predictor node.

*7.score of each classification model*
-Naive Bayes model
<p float="left">
 <img src="img/naive bayes.png" alt="image" width="50%"/> 
</p>
-Decision Tree model
<p float="left">
 <img src="img/decision tree.png" alt="image" width="50%"/> 
</p>
-Logistic Regression model
<p float="left">
 <img src="img/logistic.png" alt="image" width="50%"/> 
</p>
-Random Forest model
<p float="left">
 <img src="img/random.png" alt="image" width="50%"/> 
</p>

# Conclusion
In summary, using the Random Forest model gives the best accuracy with a score of 94.129% Error: 5.871% in an 80:20 split, Random Forest model fit this data best.
<p float="left">
 <img src="img/random.png" alt="image" width="50%"/> 
</p>

# Member name
-Nurhaya Benraheem 632431008

-Waenurhuda Hayeewaeming 632431004