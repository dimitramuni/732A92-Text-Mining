# Comparative Study of Binary Sentiment Analysis for the Product Review dataset with the Explainable AI framework

## 732A92-Text-Mining
Academic project at Linköping University, March 2023

## Abstract
This project aimed to analyze binary sentiment for the Amazon Fine Food Reviews [dataset](https://snap.stanford.edu/data/web-FineFoods.html)
using different vectorization and word embedding techniques and evaluated the performance on the gold standard dataset. In the first part of the project, we utilized two different word vectorization (i.e. count and TF-IDF vectorizers) techniques in conjunction with three linear classifiers (i.e. Multinomial Naive Bayes, Logistic Regression, and Support Vector Machine (SVM)) to create six experimental pipelines. Furthermore, we used the Halving Grid Search technique to find the best-performing model with five-fold cross-validation. Here SVM slightly outperformed the other two models with an accuracy of 93%. In the second part of the project, we utilized four pre-trained compact BERT models and DistilBERT to perform sentiment classification on a smaller subset of original data; as expected, DistilBERT outperformed the other compact BERT models, however, as it was not tuned on the entire training data, the performance was not as high as SVM model. In the third part of the project, we performed LIME (Ribeiro et al., 2016) analysis for a subset of misclassified samples identified from the final SVM model and documented actionable insights

*Keywords* : vectorization, Multinomial Naive Bayes, Halving Grid Search, Linear SVM, Logistic Regression, small BERT, DistilBERT, LIME, binary sentiment classification
