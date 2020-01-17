## Human Resources Analytics

I will be covering my analysis and approach through different process flows in the data science **pipeline**, which includes **statistical inference and exploratory data analysis**. The main goal is to understand the **reasoning behind employee turnover** and to come up with a model to classify an employee’s risk of attrition. A recommendation for a retention plan was created, which incorporates some best practices for employee retention at different risk levels of attrition.

The dataset can be found in the same directory HR_comma_sep.csv and includes following features:

### Steps Involved:

**Data Cleaning**: Dealing with incorrect encodings, removing unnecessary/invalid features
**Data Exploration**: Find high frequency words for spam vs not spam messages, explore features such as average length of document, average no. of digits per document and average no. of non-words per document
**Data Preprocessing**: Converting the text features into vectors using TFIDF vectorizer
**Model Training**: Training different classification models-Multinomial Naive Bayes, SVM and Logistic Regression
**Evaluation**: Comparing the accuracy and recall scores for different models to select the most suitable one
**Conclusions**: Choosing the best model with appropriate reasons
final results:
<img src="./test_scores.png" alt="Final Output"/>
Featur importance:
<img src="./feature_importance.png" alt="Final Output"/>
**Evaluation and Conclusions**
- Employee **satisfaction** is the **highest indicator** for employee turnover
- Employee **satisfaction, time spend in company,yearsAtCompany, and evaluation** were the four biggest factors in determining turnover.
- Based on above model to improve Employee Turnover Manger should focus on priorly satisfaction, time spend in company, yearsAtCompany, and evaluation of employee.


Please read the note book for information about the data and implementation of classifiers used.

[Notebook](https://github.com/utkarshut/ML-Projects/blob/master/Employee%20Turnover/employee_trurnover.ipynb)
