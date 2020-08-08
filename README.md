# Spam-Filtration-Using-NLP-and-ML-Algorithms
A email spam prediction project using Machine Learning.
The dataset contains one set of email messages
in English of 5572 emails tagged according being ham
or spam.
I pre-processed the raw text data using NLP methods such as
removing stopwords,stemming,tokenization.
Trained the Naive Bayes and SVM model with the
training set. I choose the LinearSVC classifier for SVM
model. I performed GridSearchCV for SVM model to
find the Best value of Hyperparameter ‘C’. The SVM
model performed slightly better than the Naive Bayes
model and Gave an accuracy of 98.55 % on the test
dataset. whereas Naive Bayes gave an accuracy of
97.93 % using 5-Fold Cross Validation.
i saved the SVM model to a pickle file.
#
previously got accuracy of 97.83% for SVM model and 96.03% for Naive Bayes model.
But got better results after some modifications.
