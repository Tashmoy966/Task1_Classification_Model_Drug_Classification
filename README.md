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

# Future Work
Good ideas or strategies that you were not able to implement which you think can help improve performance.
