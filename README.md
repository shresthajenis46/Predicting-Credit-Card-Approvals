## Predicting Credit Card Approvals
- ### Overview and Goal :

Commercial banks receive a lot of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example.

Manually analyzing these applications is mundane, error-prone, and time-consuming (and time is money!). Luckily, this task can be automated with the power of machine learning and pretty much every commercial bank does so nowadays.

In this notebook, I will build an automatic credit card approval predictor using machine learning techniques, just like the real banks do.

![credit_card](images/credit_card.jpg)


We'll use the Credit Card Approval dataset from the UCI Machine Learning Repository. The structure of this notebook is as follows:

<ol> <li>
First, we will start off by loading and viewing the dataset.
<li>We will see that the dataset has a mixture of both numerical and non-numerical features, that it contains values from different ranges, plus that it contains a number of missing entries.
<li>We will have to preprocess the dataset to ensure the machine learning model we choose can make good predictions.
<li>After our data is in good shape, we will do some exploratory data analysis to build our intuitions.
<li>Finally, we will build a machine learning model that can predict if an individual's application for a credit card will be accepted.
</ol>
