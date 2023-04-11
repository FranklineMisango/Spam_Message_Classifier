
# SMS Spam Classifier

[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)

<p align ="center">
  <a href="https://github.com/FranklineMisango/Spam_Message_Classifier">
    <img src="spam.jpg" alt="Logo">
  </a>
</p>

## 📌 Introduction:-

This an NLP Model that uses SMS data to predict whether the SMS is spam using These Machine Learning Algorthims: 

* Support Vector Classifier
* KNeighborsClassifier()
* MultinomialNB()
* DecisionTreeClassifier
* LogisticRegression
* RandomForestClassifier
* AdaBoostClassifier
* BaggingClassifier
* ExtraTreesClassifier
* GradientBoostingClassifier
* XGBClassifier

Data cleaning and processing techniques are done using the TFIDF Vectorizer 

## ✔❌Accuracy Summaries : Top Models  ❌✔:-

| Text Preprocessing Type              |     Accuracy        |
|--------------------------------------|---------------------|
|SVC                                   | 97.58%              |
|Multinomial NB                        | 97.09%              |
|Logistic Regression                   | 97.03%              |
|Random Forest                         | 97.58%              |          
|Extra Tree Classifier                 | 97.49%              |
|XGBClassifier                         | 97.49%              |    


## WorkFlow:-
![Workflow of SMS spam Classifer](workflow.gif)

## 🏁 Datasets Used:-

* The dataset used is SMS Spam Dataset created by UCI Machine Learning.This dataset is downloaded in kaggle.You can download it [here](https://www.kaggle.com/uciml/sms-spam-collection-dataset/download)

## 📧Contact:-
For any kind of suggesstions/ help in models code Please Message [me](franklinemisango4@gmail.com)

## 📜 LICENSE
[Apache ](https://github.com/FranklineMisango/Spam_Message_Classifier/blob/main/LICENSE)

## Installation

* Run `pipenv shell`
* Run `streamlit run app.py`
* The Model's website should open in a new Browser window 
![Movie image](image_Spam.png)
