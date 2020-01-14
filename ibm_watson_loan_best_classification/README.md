# IBM Watson - Loan Best Classifier Project

Final project of IBM's course https://www.coursera.org/learn/machine-learning-with-python on coursera

A simple comparison between Logistic Regression,SVM , Decision Tree and KNN models on a given data set of loans records. 

Steps Involved:

* **Data Cleaning**: Removing unnecessary/invalid features
* **Data Exploration**: Analyzed relations between differnet features and target . Generated new features based on available feature
* **Data Preprocessing**: Converting the categorical feature to one hot encoded feature , upsampled minor class dataset
* **Feature Engineering**: Adding additionally created features to training and test datasets
* **Model Training**: Training different classification models - Logistic Regression, SVM ,Decision Tree and KNN
* **Evaluation**: Comparing the Jaccard, F1-score, LogLoss for different models to select the most suitable one
* **Conclusions**: Choosing the best model with appropriate reasons


final results:

<img src="./final_output.png" alt="Final Output"/>

# Conclusion
SVM has the best fit with 77% test accuracy and F1 score of .62

Please read the note book for information about the data and implementation of classifiers used.

[Notebook](https://github.com/utkarshut/ML-Projects/blob/master/ibm_watson_loan_best_classification/Loan_Case_Best_Classifier.ipynb)
