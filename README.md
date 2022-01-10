# Heart_disease_UCI
EDA and classification model for Heart Disease UCI data from kaggle
DSWG projects can be found at the [main GitHub repo](https://github.com/sfbrigade/data-science-wg).

## Data source
Kaggle - [Heart disease UCI](https://www.kaggle.com/ronitf/heart-disease-uci)

## Project Info
The data contains information about 303 patients with chest pain and other medical information.
Given the clinical data it is possible to predict if the patient has a heart disease?

### Methods Used
* Logistic regression
* k-Nearest Neighbour
* Decision Tree
* Naive Bayes
* Support Vector Classification

### Requirements
* Python 3.8.5
* sklearn 1.0
* numpy 1.21.2
* matplotlib 3.4.3
* seaborn 0.11.2

## Results
The following accuracies were obtained:
* Logistic regression = 0.84
* k-Nearest Neighbour = 0.92
* Decision Tree = 0.8
* Naive Bayes = 0.87
* Support Vector Classification = 0.87

As we can see, the best accuracy score was obtained with k Nearest Neighbour Classifier. However, the cross-validation scores show, that the model is not that good – it obtains a mean 0.81 accuracy with 0.06 standard deviation. The best results with cross-validation were obtained in logistic regression methods. It is important to note, that the dataset was relatively small, especially with the number of features to analyze. It is recommended to check the models with the bigger sample and then decide which one is best to use.