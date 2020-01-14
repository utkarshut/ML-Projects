# Spam Classification
In this project, we will explore text message data and create models to predict if a message is spam or not. We obtained the data set from https://www.kaggle.com/uciml/sms-spam-collection-dataset. This is a Supervised Text Classification problem. The dataset can be found in the same directory spam.csv and includes following features:

Steps Involved:

* **Data Cleaning**: Dealing with incorrect encodings, removing unnecessary/invalid features
* **Data Exploration**: Find high frequency words for spam vs not spam messages, explore features such as average length of document, average no. of digits per document and average no. of non-words per document
* **Data Preprocessing**: Converting the text features into vectors using TFIDF vectorizer
* **Feature Engineering**: Adding additionally created features to training and test datasets
* **Model Training**: Training different classification models-Multinomial Naive Bayes, SVM and Logistic Regression
* **Evaluation**: Comparing the accuracy and recall scores for different models to select the most suitable one
* **Conclusions**: Choosing the best model with appropriate reasons
* **Dependencies**:

- pandas
- numpy
- sklearn
- scipy
- wordcloud
- sklearn


## Evaluation and Conclusions

In case of spam detection problem, accuracy is not the best measure for evaluating our algorithm as the classes are imbalanced. In this case, our priority is to minimize the False Negatives i.e. an regular message being categorized as Spam. Therefore, our algorithm should have a high recall score = TP / TP + FN.

Let's compare our models below:

**Multinomial Naive Bayes without additional features**: Accuracy = 93.30%, Recall = 86.65%

**Multinomial Naive Bayes with additional features**: Accuracy = 95.40%, Recall = 91.78%

**SVM Classifier with additional features**: Accuracy = 98.45%, Recall = 94.98%

**Logistic Regression with additional features**: Accuracy = 99.28%, Recall = 93.60%

Although, Logisitic Regression model has the highest accuracy, the **SVM classifier** has the **highest recall** and **slightly lower accuracy**, therefore SVM should be the choice of classifier.

Please read the note book for information about the data and implementation of classifiers used.

[Notebook](https://github.com/utkarshut/ML-Projects/blob/master/Spam%20Classification/Spam_Classification.ipynb)

