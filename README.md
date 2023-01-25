# Fraud-detector 🦚

### Context
It is important that credit card companies can recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. Trying to analyze data and identify fraudulent credit card transactions.

<img src='https://cdn.dribbble.com/users/6441473/screenshots/14811036/media/a2f1ca0a075b669a90633e42101b01d5.png?compress=1&resize=1000x600'>

### Content
It contains only numerical input variables resulting from a PCA transformation. Unfortunately, we cannot provide the original features and more background information about the data due to confidentiality issues. Features V1, V2, … V28 is the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependent cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

### Algorithm 
Logistic Regression is used to train the model. Logistic regression analysis is used to examine the association of categorical independent variables with one dichotomous dependent variable, Class. Dataset used <a href='https://www.kaggle.com/mlg-ulb/creditcardfraud'>Credit Card Fraud detection</a>

