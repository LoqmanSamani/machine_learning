<h2>Machine Learning Repository</h2>


![Static Badge](https://img.shields.io/badge/license-MIT-red?style=plastic)
![Static Badge](https://img.shields.io/badge/python-blue?style=plastic&logo=python&logoColor=white)
![Static Badge](https://img.shields.io/badge/TensorFlow-white?style=plastic&logo=tensorflow)
![Static Badge](https://img.shields.io/badge/scikit_learn-orange?style=plastic&logo=scikit-learn&logoColor=white)
![Static Badge](https://img.shields.io/badge/numpy-midnightblue?style=plastic&logo=NumPy)
![Static Badge](https://img.shields.io/badge/pandas-blue?style=plastic&logo=pandas)
![Static Badge](https://img.shields.io/badge/matplotlib-yellow?style=plastic&logo=seaborn&logoColor=white)
![Static Badge](https://img.shields.io/badge/seaborn-red?style=plastic&logo=seaborn)
![Static Badge](https://img.shields.io/badge/SciPy-darkblue?style=plastic&logo=scipy&logoColor=white)
![Static Badge](https://img.shields.io/badge/SymPy-lightgreen?style=plastic&logo=sympy)

Welcome to my Machine Learning Repository! This repository contains materials, tasks, and projects that I completed during my journey of learning machine learning through two specialization courses offered by ***[DeepLearning.AI](https://www.deeplearning.ai)*** on ***[Coursera](https://www.coursera.org/)***.


### Specializations

1. ***[Mathematics for Machine Learning and Data Science Specialization](https://www.coursera.org/specializations/mathematics-for-machine-learning-and-data-science)***

   This specialization comprises three fundamental courses:

    - [Linear Algebra for Machine Learning and Data Science](https://github.com/LoqmanSamani/machine-learning/tree/systembiology/linalg)
    - [Calculus for Machine Learning and Data Science](https://github.com/LoqmanSamani/machine-learning/tree/systembiology/calculus)
    - [Probability & Statistics for Machine Learning & Data Science](https://github.com/LoqmanSamani/machine-learning/tree/systembiology/stats)

2. ***[Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction)***
    
    This specialization consists of three comprehensive courses:
    
     - [Supervised Machine Learning: Regression and Classification](https://github.com/LoqmanSamani/machine-learning/tree/systembiology/supervised_learning)
      - [Advanced Learning Algorithms](https://github.com/LoqmanSamani/machine-learning/tree/systembiology/advanced_algorithms)
      - [Unsupervised Learning, Recommenders, Reinforcement Learning](https://github.com/LoqmanSamani/machine-learning/tree/systembiology/unsupervised_learning)
      

### Models

In the ***[models](https://github.com/LoqmanSamani/machine-learning/tree/systembiology/models)*** directory, you'll find implementations of more than 15 machine learning models that I developed during my learning journey. These models cover a wide range of topics, including supervised and unsupervised learning, feature engineering, model evaluation, and more. 

Feel free to explore the models and adapt them to your own projects and datasets. Happy learning!


| Model                                                                                                                                   | Explanation                                                                                                                                                                                                                                                                                                                    |
|-----------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ***[Linear Regression 1](https://github.com/LoqmanSamani/machine-learning/blob/systembiology/models/regression1.py)***                  | Multiple linear regression model with one perceptron trained on a synthetic dataset. It aims to predict a continuous target variable by fitting a linear equation to observed data.                                                                                                                                            |
| ***[Linear Regression 2](https://github.com/LoqmanSamani/machine-learning/blob/systembiology/models/regression2.py)***                  | Multiple linear regression model with one perceptron trained on the [house.csv](https://github.com/LoqmanSamani/machine-learning/blob/systembiology/data/house.csv) dataset for predicting house prices. It utilizes features such as square footage, number of bedrooms, etc., to estimate the price of houses.               |
| ***[Logistic Regression](https://github.com/LoqmanSamani/machine-learning/blob/systembiology/models/logistic_regression.py)***          | Logistic regression model with one perceptron trained on a synthetic dataset. It is used for binary classification tasks, predicting the probability that an instance belongs to a particular class using the logistic function.                                                                                               |
| ***[Neural Network](https://github.com/LoqmanSamani/machine-learning/blob/systembiology/models/neural_network.py)***                    | Neural network with two layers for classification trained on a synthetic dataset. It consists of interconnected nodes (neurons) that process input data, enabling complex pattern recognition tasks by learning from labeled examples.                                                                                         |
| ***[Naive Bayes Classifier 1](https://github.com/LoqmanSamani/machine-learning/blob/systembiology/models/naive_bayes_classifier1.py)*** | Naive Bayes classifier for continuous datasets trained on [dog_data1.csv](https://github.com/LoqmanSamani/machine-learning/blob/systembiology/data/dog_data1.csv). It is a probabilistic classifier based on Bayes' theorem, assuming independence between features, and used for predicting the probability of a given class. |
| ***[Naive Bayes Classifier 2](https://github.com/LoqmanSamani/machine-learning/blob/systembiology/models/naive_bayes_classifier2.py)*** | Email spam detector trained on the [emails.csv](https://github.com/LoqmanSamani/machine-learning/blob/systembiology/data/emails.csv) dataset. It classifies emails as spam or not spam based on the occurrence of certain keywords and features extracted from the email content, using a Naive Bayes classifier.              |
| ***[Mini Batch Regression](https://github.com/LoqmanSamani/machine-learning/blob/systembiology/models/batch_regression)***              | Linear regression model with mini-batch gradient descent algorithm trained on the [house.csv](https://github.com/LoqmanSamani/machine-learning/blob/systembiology/data/house.csv) dataset. It optimizes model parameters by updating them in small batches of data, improving efficiency and convergence speed compared to batch gradient descent.                                                               |
| ***[L2 Regression](https://github.com/LoqmanSamani/machine-learning/blob/systembiology/models/l2_regression.py)***                      | Multiple linear regression model with L2 regularization term. It includes a penalty term in the loss function to prevent overfitting by shrinking the coefficients towards zero, improving the model's generalization performance.                                                                                             |
| ***[L2 Logistic Regression](https://github.com/LoqmanSamani/machine-learning/blob/systembiology/models/l2_logistic_regression.py)***    | Logistic regression model with L2 regularization term. Similar to L2 regression, it prevents overfitting by adding a penalty term to the loss function, promoting smaller parameter values and improving the model's robustness against noise in the data.                                                                     |
| ***[L2 Neural Network](https://github.com/LoqmanSamani/machine-learning/blob/systembiology/models/l2_neural_network.py)***              | Neural network model for multiclass classification (handwritten digit recognition) tasks with L2 regularization term. It incorporates regularization to the network's loss function, helping to prevent overfitting by penalizing large weights and reducing model complexity.                                                 |
| ***[Decision Tree](https://github.com/LoqmanSamani/machine-learning/blob/systembiology/models/decision_tree.py)***                      | Decision tree model for classification tasks. It partitions the input space into regions and predicts the target variable's class by following a tree-like structure of if-else conditions based on the input features' values.                                                                                                |
| ***[K-Means Clustering](https://github.com/LoqmanSamani/machine-learning/blob/systembiology/models/k-means_clustering.py)***            | K-means model for classification tasks trained on a synthetic dataset. It partitions data into 'k' clusters based on similarity and assigns each data point to the nearest cluster centroid, facilitating data analysis and pattern discovery.                                                                                 |
| ***[Anomaly Detection](https://github.com/LoqmanSamani/machine-learning/blob/systembiology/models/anomaly_detection.py)***              | Anomaly detection model with density estimation using Gaussian distribution. It identifies outliers or anomalies in data by calculating the probability of observing each data point under a fitted Gaussian distribution and flagging points with low probability.                                                            |
| ***[Recommender System 1](https://github.com/LoqmanSamani/machine-learning/blob/systembiology/models/collaborative_filtering.py)***     | Collaborative filtering algorithm to build a recommender system. It recommends items to users based on their past interactions and similarities with other users' preferences or item characteristics, leveraging user-item interaction data.                                                                                  |
| ***[Recommender System 2](https://github.com/LoqmanSamani/machine-learning/blob/systembiology/models/content_based_filtering.py)***     | Content-based filtering algorithm to build a recommender system. It recommends items to users based on similarities between items' features and user preferences, using item descriptions, metadata, or other relevant information.                                                                                            |
| ***[PCA](https://github.com/LoqmanSamani/machine-learning/blob/systembiology/models/PCA.py)***                                          | Principal Component Analysis (PCA) for reducing the dimensions of a dataset. It identifies the directions (principal components) that capture the most variance in the data and projects the data onto these components to achieve dimensionality reduction.                                                                   |


This project is licensed under the [MIT LICENSE](https://github.com/LoqmanSamani/machine-learning/blob/systembiology/LICENSE)

