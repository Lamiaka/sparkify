# Sparkify

1. [Introduction](https://github.com/Lamiaka/sparkify#Introduction)
2. [Package requirements](https://github.com/Lamiaka/sparkify#Package-requirements)
3. [Content of the repository](https://github.com/Lamiaka/sparkify#Content-of-the-repository)
3. [Results and discussion](https://github.com/Lamiaka/sparkify#Results-and-discussion)
3. [Acknowledgments](https://github.com/Lamiaka/sparkify#Acknowledgements)
3. [Ressources](https://github.com/Lamiaka/sparkify#Ressources)

## Introduction
Sparkify is a fake music streaming platform that proposes to its customers to listen to their favorite songs either via a free offer which may imply some advertisement while using the platform or via the paid offer without advertisements.
The project is proposed by the learning platform Udacity and aims at training the application of prediction algorithm as part of the Data Scientist Nanodegree leveraging the power of distributed computation with Spark.
Sparkify company would like to determine which of its customers is going to either stay or churn from the platform based on their recorded session data. A dataset with fake customer data and their use of the platform is provided to us as a study case to predict customer churn.

## Package requirements 
The minimum requirements to run this project are the standard data science libraries that are in the Anaconda distribution of Python.  
In particular:  
NumPy  
Pandas  
Matplotlib  

Additionnally, one needs to install PySpark.  
This can be done with running the command on your terminal or console: `pip install pyspark`.

## Content of the Repository 

- [Data exploration notebook](https://github.com/Lamiaka/sparkify/blob/master/1-Sparkify_data_exploration.ipynb)
- [Feature Engineering notebook](https://github.com/Lamiaka/sparkify/blob/master/2-Sparkify_feature_engineering.ipynb)
- [Feature dataset](https://github.com/Lamiaka/sparkify/tree/master/mini_sparkify_features.json) output from the feature engineering notebook
- [Modelling notebook](https://github.com/Lamiaka/sparkify/blob/master/3-Sparkify_churn_model_training.ipynb)
- [Best model](https://github.com/Lamiaka/sparkify/tree/master/Best_model_rf_acc_0.7674418604651163_f1_0.7450166112956811)

[A separate notebook](https://github.com/Lamiaka/sparkify/blob/master/1bis-Sparkify_churn_plot_states.ipynb) to plot the customers location on the US map and compare it to the US population distibution is also added.  
In [this database](https://github.com/Lamiaka/sparkify/blob/master/state_db.db) are provided the longitudes and latitudes coordinated of the 51 US States as well as the sparkify customers and their respective residency States.   
[This python file](https://github.com/Lamiaka/sparkify/blob/master/US_States_sql_table_creation.py) generates the database. 

## Results and discussion
Results on this project are detailed in [this medium post](https://lamiak.medium.com/predicting-churn-for-sparkify-381dfac1a21f).

## Acknowledgements 
Acknowledgements to the Udacity platform for providing the students with interesting use cases. Acknowledgemenst to the students on the platform and the mentors for answering questions. 
Big acknowledgemenst to the data science community for writing open source documentation and democratizing the knowledge. 

## Ressources 
[Spark documentation webpage](https://spark.apache.org/docs/latest/api/python/index.html)  
[The origins of logistic regression](https://papers.tinbergen.nl/02119.pdf)  
[Random decision Forest](https://web.archive.org/web/20160417030218/http://ect.bell-labs.com/who/tkh/publications/papers/odt.pdf)  
[Support Vector Networks](http://image.diku.dk/imagecanon/material/cortes_vapnik95.pdf)  
[Idiot's Bayes, not so stupid after all](https://www.jstor.org/stable/1403452?origin=crossref&seq=1)  
[An example of using Logistic Regression using pyspark](https://medium.com/swlh/logistic-regression-with-pyspark-60295d41221)  
[Dealing with small datasets](https://hackernoon.com/7-effective-ways-to-deal-with-a-small-dataset-2gyl407s)  
[Augmenting datasets with synthetic data](https://towardsdatascience.com/augmenting-categorical-datasets-with-synthetic-data-for-machine-learning-a25095d6d7c8)  
[Comparison of classifiers given little training data](http://www.ifp.illinois.edu/~iracohen/publications/precision-ecml04-ColorTR-final.pdf?ref=hackernoon.com)  

