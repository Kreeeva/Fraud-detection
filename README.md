# Fraud-detection
## Project Description
Credit card fraud detection

Like any other technology that has been introduced in the world, the internet also comes with pros and cons. All of us enjoy the pros as the internet has changed our lifestyle by enhancing our communication. But, at the same time, we are witnessing digital frauds, which include fraudulent transactions through stolen credit cards. Credit card companies must identify fraudulent credit card transactions so that customers are not charged for items that they did not purchase. And this project is all about detecting such fraudulent transactions with the help of customers' attributes and transactions information.

## Credit Card Fraud Detection Dataset
The dataset used contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced; the positive class (frauds) account for 0.172% of all transactions. The dataset has been collected and analyzed during a research collaboration of Worldline and the Machine Learning Group (http://mlg.ulb.ac.be) of ULB (Universite Libre de Bruxelles) on big data mining and fraud detection. More details on current and past projects on related topics are available on http://mlg.ulb.ac.be/BuFence and http://mlg.ulb.ac.be/ARTML.

 

As the dataset was created using the PCA method, preprocessing of data has little scope. The imbalance between classes is compensated using oversampling and undersampling. The logistic regression, random forest, support vector machine, k-means are used within a cross-validation framework. Lastly, Recall and Accuracy are chosen as metrics while deducing the best classifier. A buffer section on outlier detection is added at the end.

## Take Aways
Exploratory Data Analysis
The dataset in this project does not have much information about what physical quantity each variable represents in this dataset except the two, amount, and time. Thus, analyzing the dataset using statistical tools is critical for such a dataset. You will learn how to draw statistical conclusions for all the variables. Additionally, the project solution will teach you how to create plots for visualizing the distribution of variables and deduce which variables play an essential role in segregating fraudulent and non-fraudulent transactions. The analysis will also assist you in concluding that the data is imbalanced and by what amount. Furthermore, you will learn plotting boxplots for visualizing outliers and evaluating the interquartile range of different features.

 

Data Preparation
As the dataset is highly skewed towards non-fraudulent transactions, using classification algorithms in this project will reveal that one needs to use either undersampling or oversampling methods. This project will discuss both the ways in detail and assist you in understanding which technique will suit a particular problem. You will also learn how to prepare the data to implement algorithms of the scikit-learn library in Python. Additionally, you will learn about different methods for scaling the variables and outliers detection.

 

Machine Learning Algorithms
This project is a beginner-friendly project on machine learning as it will teach you all the basics of this exciting domain. You will learn about the four types of machine learning problems: unsupervised learning, supervised learning, semi-supervised learning, and reinforcement learning. The project defines all these problems in detail with examples and various use cases. The goal is to detect which transactions are fraudulent or not, and this problem is an instance of a binary classification problem in supervised learning. To solve this problem, you will use algorithms like Random Forests, K-Nearest Neighbour, and Logistic Regression and deduce which is the best among them with the help of different statistical parameters like Precision, Recall, Accuracy, etc. Also, you will learn about preparing a credit card fraud detection project report with the help of classification metrics like the ROC curve, confusion matrix. The project will also assist you in understanding why accuracy is not an important metric for an imbalanced dataset. Furthermore, you will learn about using hyperparameter tuning techniques: GridSearchCV for undersampled data and RandomSearchCV for oversampled data.

 

FAQs on the Credit Card Fraud Detection Data Science Project
1) Which are the best algorithms for credit card fraud detection?
The problem of credit card fraud detection is an example of a binary classification problem that can be solved using classification algorithms like Random Forests, Logistic Regression, Support Vector Machines, K-Nearest Neighbour, etc. You can analyze the performance of these algorithms using metrics like Recall, Precision, Accuracy, Confusion Matrix, ROC Curve, etc., and deduce which works best for your dataset.

 

Another way of solving this problem is to treat this as an anomaly detection problem wherein the frauds are treated as anomalies. Then algorithms like Autoencoders, Isolation forest can be used to find out these anomalies. 

 

2) Why is Machine learning used in Credit Card Fraud Detection?
Machine learning algorithms do not assume the logic that differentiates fraudulent transactions from non-fraudulent ones. Rather, they leverage the transactions details and customers’ information to deduce the characteristics of fraudulent transactions. These algorithms are best suited to reveal the hidden patterns in the dataset and are therefore becoming a popular choice for solving problems like detecting credit card frauds.
