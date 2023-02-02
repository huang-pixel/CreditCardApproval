# Project Analysis 

## Objective

The purpose of this project is to illustrate the machine learning and data processing techniques learned in the project offered on the `Datacamp` website to to predict if a person's application for a credit card would get approved or not given some information about that person.  

I will use the Credit Approval Dataset which is a collection of credit card applications and the credit approval decisions. The data is available from the [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/credit+approval)[^1]. The implementation of the above technology consists of data visualisation, data transformation, logistics regression, evaluating multiple models. The procedure is organised as follows: 

[^1]:The UCI Machine Learning Repository is a collection of databases, domain theories, and data generators that are used by the machine learning community for the empirical analysis of machine learning algorithms.


- Generate data visualisations to understand the baseline data
- Convert data as required
- Generate and apply models to answer research questions
- Fine-tuning model parameters to find the best model performance
- Comparing the various models


## Data overview and transformations

### Description 

The first step in any analysis is to obtain the [dataset](http://archive.ics.uci.edu/ml/machine-learning-databases/credit-screening/) and [codebook](http://archive.ics.uci.edu/ml/machine-learning-databases/credit-screening/crx.names). Both the dataset and the codebook can be downloaded for free from the UCI website. To protect confidentiality of the data, all attribute names and values have been changed to meaningless symbols. This database contains 690 instances, 15 attributes and 2 classes attributes[^2]in total. There are also a few missing values(5%). 

[^2]: There are 383 (55.5%) applications that got denied and 307 (44.5%)

### Transformations

#### In the numeric columns
- Imputing the missing values with mean

#### In the non-numeric columns 
- imputing these missing values with the most frequent values

#### Preprocessing the data
- Convert the non-numeric data into numeric
- Scale the feature values to a uniform range

### Making predictions with Logistics Regression
- Get the accuracy score and confusion matrix

### Fine-tuning model parameters
- Grid Search with different hyperparameters and cross-validation 

### Ranking Classifiers
- Observation the report of classifiers
- Draw boxplot to visualise the range of variation in accuracy
### Result 
- The logistics regression model and DecisionTree are able to yield an accuracy score of 100%. As for the KNN model, it achieves an accuracy of over 90 percent. 
### Reflections
- Although the accuracy of the results is ideal, which is the best model?
- It is possible to realise that the different models have different problems, their respective advantages and disadvantages
- The sample data size for this study was small












