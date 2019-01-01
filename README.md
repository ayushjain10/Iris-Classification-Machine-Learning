# Iris-Machine-Learning-Classification
Classifying Iris flowers using various ML algorithms such as KNN, Naive Bayes, Logistic Regression, SVM

This is an example of supervised learning where the class label is given in the dataset. We divide the dataset in 80-20 ratio as training data and test data. We train the model using training data and the check the accuracy of the model using test data.

We have achieved 100% accuracy by training the model using Support Vector Machine (SVM). 

The project can be divided into following parts:

1) Data Visualization using matplotlib and pandas library to plot the multi-variate and univariate plots to get the signifance of each feature and the relation between each attribute.
(We see that for some attributes, there is a linear relationship i.e. between petal-length and petal-width plots)

2) Splitting the dataset into training and test data. This was achieved using sklearn library. This is a wonderful library and provides a lot of API's for Machine Learning Algorithms.

3) For the re-sampling technique, we chose k-fold cross validation method as it is better than Validation set approach and LOOCV.

4) Now performed the below algorithms on the training data and noted the accuracy :
  Logistic Regression         :           94.16%
  K-Nearest Neighbor          :           95.83%
  Naive Bayes                 :           92.5%
  Support Vector Machines     :           97.5%
  
5) Constructed the model using SVM ML algorithm and tested the accuracy of the model on the test dataset.

6) Achieved 100% accuracy on the test dataset. All the 30 flowers were correctly classified.
