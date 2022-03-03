# Machine-Learning-Projects
 Credit Card Fraud Detection Using Machine Learning
 
 
 ![1-Credit-card-fraud-detection-with-classification-algorithms (2)](https://user-images.githubusercontent.com/66740565/156515357-1e869cf3-167c-4859-8d2e-e722fc8d5f26.jpg)

 
In this project I build machine learning models to identify fraud in European credit card transactions. I also make several data visualizations to reveal patterns and structure in the data.

The dataset, hosted on Kaggle, includes credit card transactions made in September 2013 by European cardholders. The data contains 284,807 transactions that occurred over a two-day period, of which 492 (0.17%) are fraudulent. Each transaction has 30 features, all of which are numerical. The features V1, V2, ..., V28 are the result of a PCA transformation. To protect confidentiality, background information on these features is not available. The Time feature contains the time elapsed since the first transaction, and the Amount feature contains the transaction amount. The response variable, Class, is 1 in the case of fraud, and 0 otherwise.

# Summary 
  1. We have tried several models till now with both balanced and imbalanced data. We have noticed most of the models have performed more or less well in terms of  Precision and Recall.

  2. So here, to save the banks from high-value fraudulent transactions, we have to focus on a high recall in order to detect actual fraudulent transactions.

  3. After performing several models, we have seen that in the balanced dataset with the Logistic regression model where F1-Score is 0.94 and Support Vector Machine (SVM) has good Precision values and also high Recall where F1-Score is 0.93.

  4. Hence, we can go with the logistic model here. It is also easier to interpret and explain to the business.

 
 # Note: I am not including the dataset file in this repository because of its size. You can download it from the aforementioned kaggle link.
