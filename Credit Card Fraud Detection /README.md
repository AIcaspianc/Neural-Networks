**Problem Statement - Credit Card Fraud Detection Case Study**

**Context**

According to Nielsen, the United States experienced about $9 billion in fraud involving various cards (credit, debit, etc.) in 2016, with projections suggesting an increase to $12 billion by 2020. To put this into perspective, in 2017, the revenues of both PayPal and Mastercard were approximately $10.8 billion each. This highlights the urgent need for credit card companies to accurately identify fraudulent transactions to prevent customers from being billed for purchases they didn't make.

**Goal** In the role of a Data Scientist at CCFraud, a credit card company, your task involves using credit card transaction data to develop a fraud detection model. This model will be built using Multilayer Perceptrons, implemented through Keras.

**Data Attributes**

- **Time** : This represents the number of seconds elapsed between each transaction and the dataset's first transaction.
- **Amount** : This is the value of the transaction. This attribute can be utilized for cost-sensitive learning that varies depending on the transaction.
- **Class** : This is the target variable, indicating fraud if its value is 1, and non-fraudulent otherwise.

**Learning Objectives**

- Conducting Exploratory Data Analysis.
- Preparing data for training the model.
- Training the model using a Neural Network approach.
- Evaluating the performance of the model.
