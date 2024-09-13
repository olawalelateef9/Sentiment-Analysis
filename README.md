# Sentiment-Analysis
Sentiment analysis helps identify the sentiment (positive, negative, or neutral) in text data such as customer reviews. Sentiment analysis is a critical task in natural language processing for understanding the emotions/opinions expressed in text. This project utilizes a variety of machine learning techniques to predict sentiment from text data. 
### Sentiment Analysis Project Overview

This project focuses on Sentiment Analysis, the task of determining the emotional tone behind a series of words used in text, often categorized as positive, negative, or neutral. Using machine learning techniques, we classify sentiment from text data. Three models—Logistic Regression, Support Vector Classifier (SVC), and Naive Bayes—were trained and evaluated based on key performance metrics such as accuracy, precision, and recall.

### Model Performance Overview

#### 1. **Logistic Regression**
- **Accuracy**: 91.49%
- **Precision**: 0.9150
- **Recall**: 0.9149

Logistic Regression performed well, achieving an accuracy of 91.49%. The precision and recall scores of 0.9150 and 0.9149 indicate that the model is balanced in terms of identifying positive sentiments accurately while also correctly retrieving most positive instances.

#### 2. **Support Vector Classifier (SVC)**
- **Accuracy**: 92.36%
- **Precision**: 0.9243
- **Recall**: 0.9236

SVC outperformed Logistic Regression with a slightly higher accuracy of 92.36%. With a precision of 0.9243 and recall of 0.9236, it proved to be the best model in terms of both identifying and retrieving positive sentiments, making it the most effective classifier in this analysis.

#### 3. **Naive Bayes**
- **Accuracy**: 75.27%
- **Precision**: 0.8038
- **Recall**: 0.7527

Naive Bayes, although computationally efficient, had lower performance compared to the other models with an accuracy of 75.27%. The precision score of 0.8038 indicates it has a decent capability of identifying positive sentiment correctly, but its recall of 0.7527 means it struggles to identify all the positive instances effectively.

### Conclusion

In this sentiment analysis project, the **Support Vector Classifier (SVC)** model emerged as the most accurate and balanced model with the highest precision and recall values. **Logistic Regression** followed closely behind with comparable performance. **Naive Bayes**, while less accurate, offers a lightweight alternative, suitable for larger datasets or real-time applications where speed is a priority over precision.

This analysis demonstrates that SVC is the best option for achieving high sentiment classification performance, especially in tasks where precision and recall are critical.
