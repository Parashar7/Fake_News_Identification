# Fake_News_Identification

# Aim
Our aim is to identify textual properties that can be used to distinguish fake contents from real. By using those properties, we train a combination of different machine learning algorithms using various ensemble methods and evaluate their performance on real world datasets. Experimental evaluation confirms the superior performance of our proposed ensemble learner approach in comparison to individual learners. This study is based on the result of confusion matrix.

# Confusion Matrix

A confusion matrix is a table that is often used to describe the performance of a classification model (or "classifier") on a set of test data for which the true values are known. The confusion matrix itself is relatively simple to understand, but the related terminology can be confusing.

true positives (TP): These are cases in which we predicted yes (they have the disease), and they do have the disease.

true negatives (TN): We predicted no, and they don't have the disease.

false positives (FP): We predicted yes, but they don't actually have the disease. (Also known as a "Type I error.")

false negatives (FN): We predicted no, but they actually do have the disease. (Also known as a "Type II error.")

![Screenshot 2022-02-28 113540](https://user-images.githubusercontent.com/67996367/155932637-f58b7d07-ec47-4b92-a4e4-de9a6e72e6db.png)

# Accuracy 

Accuracy is often the most used metric representing the percentage of correctly predicted observations, either true or false. To calculate the accuracy of a model performance, the following equation can be used:

![Screenshot 2022-02-28 114106](https://user-images.githubusercontent.com/67996367/155933239-ef57dff2-ad15-43af-92ce-df4306171092.png)
