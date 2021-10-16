Sentiment Classification of Tweets README file
------------------------------------------------------------------
Introduction:
Sentiment Classification of Tweets evlauates the performance of logistic regression model, k-nearest neighbors model, decision tree model and multi-layer perceptron model on feature "count", "tfidf" and "glove100" based on accuracy, precision, recall and F1 scores.

Language & Platform:
Sentiment Classification of Tweets is a project based on python language development, it is implemented on jupyter notebook.

Sections:
1. Data Engineering: Read in data in csv files, extract training and testing features from data, extract training and testing labels from data.
2. Baseline: Create baseline model using weighted random baseline, obtain baseline accuracy, precision, recall and F1 scores.
3. Training and Developing:
    a) Logistic Regression: Implement logistic regression model with feature "count", "tfidf" and "glove100" seperately, obtain evaluation metrics for each feature. 
    b) KNN: Implement k-nearest neighbors model with feature "count", "tfidf" and "glove100" seperately, test for best parameter K, obtain evaluation metrics for each feature.
    c) Decision Tree: Implementdecision tree model with feature "count", "tfidf" and "glove100" seperately, test for best maximum depth of tree, obtain evaluation metrics for each feature.
    d) Multi-layer Perceptron: Implement multi-layer perceptron model with feature "count", "tfidf" and "glove100" seperately, obtain evaluation metrics for each feature. 
4. Predict the text value: Predict the text value with the model with best overal effectiveness, save the result into a new csv file.