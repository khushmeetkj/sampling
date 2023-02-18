# Using various sampling Methods to train ML models on imbalanced and comparing their accuracies
We are given an imbalanced dataset (Credit Card Fraud) on which we need to apply various sampling methods and train various ML models and then draw conclusions about their accuracies.

The various sampling methods that we'll be using are:
  1. Random Sampling
  2. Systematic Sampling
  3. Stratified Sampling
  4. Cluster Sampling
  
The various ML models that we'll be using are:
  1. SVM
  2. Logistic Regression
  3. Decision Tree
  4. KNN
  5. Naive Bayes
  


##Steps


Step 1: Balance the imbalance dataset

Step 2: Apply the sampling technique to get the sample

Step 3: Split the sample into training set and testing set

Step 4: Train the model 

Step 5: Calculate evaluation parameters

Step 6: Repeat step 4 and 5 for all 5 models 

Step 7: Repeat step 2,3,4,5 and 6 for all 4 samplings techniques

Step 8: Represent accuracy of various models and sampling techniques in form of dataframe.



##Conclusion


We conclude that for:
    1. SVM: Cluter sample gives the best accuracy in this case
    2. Logistic Regression: Random sampling gives the best accuracy in this case
    3. Decision Tree: Systemic and cluster sampling gives the best accuracy in this case
    4. KNN: Stratified sampling gives the best accuracy in this case
    5. Naive Bayes: Cluster sampling gives the best accuracy in this case
        
Furthermore, we can conclude that if we choose:
    1. Random Sampling: Logistic Regression will give us results with most accuracy in this case
    2. Systematic Sampling: Decision Tree will give us results with most accuracy in this case
    3. Stratified Sampling: KNN and Decision Tree will give us results with most accuracy in this case
    4. Cluster Sampling: Decision Tree will give us results with most accuracy in this case
