# Online_Shoppers_Purchase_Intention

Preprocessing data, performing exploratory data analysis, feature selection, building multiple machine learning classification models, and predicting whether an online shopper will make a purchase.

The dataset contains information about users' browsing sessions on an e-commerce website. The objective is to predict whether a visitor will complete a purchase (Revenue = True) based on their browsing behaviour.

* Original Source: UCI Machine Learning Repository
* Link: [Online Shoppers Purchasing Intention Dataset](https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset)

### Models Used

- Decision Tree Classifier
- Gaussian Naive Bayes
- Support Vector Machine (SVM)
- Random Forest Classifier
- Gradient Boosting Classifier

Model performance was further improved by handling class imbalance using **SMOTE** and optimizing the Gradient Boosting model using **Pipeline** and **GridSearchCV**.

### Best Model

- Gradient Boosting Classifier (Hyperparameter Tuned)

Outcome:

The tuned Gradient Boosting model achieved the best overall balance among the implemented models with:

- Accuracy: **76.89%**
- Precision: **33.45%**
- Recall: **48.17%**
- F1 Score: **39.48%**
