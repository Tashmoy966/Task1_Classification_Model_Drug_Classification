# Problem Statement
The Drug Classifcation Analysis is used to analyse the effect of a particular drug based on certain paramrters (Age,Sex,BP,Cholesterol,Na_to_K) and finding an effective model which holds a strong relation with the parameters to predict the specific drug consumption index.

# Dataset
The dataset used is the [Drug Classification With Different Algorithms](https://www.kaggle.com/gorkemgunay/drug-classification-with-different-algorithms/notebook) from Kaggle. 

**The 6 class labels are:**

1. **Age** :Age of the person (int64).
2. **Sex** :Gender the person holds(object or categorical) (Male or Female).
3. **Cholesterol** :Fat level of the person (object or categorical) (High or Low or Normal).
4. **Na_to_K** :Sodium or Potassium content of the body (float64).
5. **BP** : Blood Pressure of the person (object or categorical) (High or Normal).

**Target Variable:**

Drug (object or categorical)

**Drug** refer to the type of drug consumed (through medication or direct injection) 

**Type:**

A,B,C,X,Y

# Model(s) Used

1. **KNN Classifier**

In this kernel, parameters of KNN Algorithm are described and effects of these paremeters on result are observed. First prediction is predicted with default parameters and      this   result is used for comparing. After that, best value of every parameters are found and are discussed their effects on result.Finally, GridSearch algorithm is used to find best values of each parameters. So results can be compared each other in the conclusion part.

i) Calculate distance

ii) Find closest neighbors

iii)Vote for labels

![image](https://user-images.githubusercontent.com/87931949/149998804-2881e277-abfa-4867-a354-0f40f5b0b13b.png)

[Refer](https://www.datacamp.com/community/tutorials/k-nearest-neighbor-classification-scikit-learn)

2. **Random Forest**

The Random forest or Random Decision Forest is a supervised Machine learning algorithm used for classification, regression, and other tasks using decision trees.
The Random forest classifier creates a set of decision trees from a randomly selected subset of the training set. It is basically a set of decision trees (DT) from a randomly selected subset of the training set and then It collects the votes from different decision trees to decide the final prediction.

![image](https://user-images.githubusercontent.com/87931949/149999578-242ca37e-9877-445e-a104-3c9f3baf9e68.png)

Based on the MSE the entropy of the system is reduced to get the best classification.

[Refer](https://www.upgrad.com/blog/random-forest-classifier/)

3. **SVM Classifier**

**Support Vector Machines**

Generally, Support Vector Machines is considered to be a classification approach, it but can be employed in both types of classification and regression problems. It can easily handle multiple continuous and categorical variables. SVM constructs a hyperplane in multidimensional space to separate different classes. SVM generates optimal hyperplane in an iterative manner, which is used to minimize an error. The core idea of SVM is to find a maximum marginal hyperplane(MMH) that best divides the dataset into classes.

i) Generate hyperplanes which segregates the classes in the best way. Left-hand side figure showing three hyperplanes black, blue and orange. Here, the blue and orange have higher classification error, but the black is separating the two classes correctly.

ii) Select the right hyperplane with the maximum segregation from the either nearest data points as shown in the right-hand side figure.

![image](https://user-images.githubusercontent.com/87931949/150000093-cedb850e-4796-458c-909d-77076f506677.png)

[Refer](https://www.datacamp.com/community/tutorials/svm-classification-scikit-learn-python)


# Future Work

1) Need to bring some improvemrnt in the data cleaning methods through standardised scaling non object variables.
2) Merging more classes for analysis (eg medication consumption rate, other mineral components comsumed etc).
3) Check for multicollinearity between parameters for significance.

