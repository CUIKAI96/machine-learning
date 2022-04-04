# Machine Learning

Depending on different purposes, machine learning algorithms can be categorized into **supervised learning**, **unsupervised learning**, and **reinforcement learning**. 

## Supervised Learning
The idea of supervised learning is that we want to predict what the outcome would be based on the previous observed knowledge/history data, which perfroms as training data. A nature way of solving this problem would be looking at all the history data, and choose the one mostly similar to what we have as the output. But this is not a stisfactory approach for lack of flexibility and accuracy. Hence, we come up with better developed and systematic way of doing this repeatedly. Measuring the similarity of test and train, and generate it's label or value in a fancy, scientic way. 

In addtion, all the fancy manth turned out to be solving an optimization problem, which gives us the parameters we need for the prediction. Hence, optimization problem formation is the key to any machine learning algorithm. 

Supervised learning focuses on developing an algorithm that can predict output of a given input by learning from the histroy or training dataset. This is also called learning labels. Depending on if the label is continuous or discrete, supervied learning is furtuer categorized into **regression** and **classification**. 

Common regression algorithms are linear regression, Bayesian linear regression, gaussian process regression. ARIMA and other time series predictive algorithms are derived from regression. 

Common classification algorithms are 
* perceptron, 
* logistic regression
* Support Vector Machine
* GDA, QDA, LDA
* naive bayes

## Unsupervised Learning
Unsupervised learning can learn the pattern from given data, such as distribution, cluster, and structure. 

Common unsupervised learning algorithms are
* k-means cluster 
* density estimation

## Reinforcement Learning
Reinforcement learning produces action decisions. It's optimized to find suitable action to take in a given situation in order to maximize a reward function. 


When learning and applying a new machine learning algorithm, you need to pay special attention to all the assumptions that were made to get the conclusion. 

Other techniques that weren't included are graphs, such as, decision trees, markcov chains, etc. 
