# Give Me Some Credit
## Project Objective: To build a Classification Model to Detect the Likelihood of Borrower Default
This project will explore the factors that have an affect on a borrower's likelihood to repay. The data source is from <a href="https://www.kaggle.com/competitions/GiveMeSomeCredit/"> Kaggle's Give me Some Credit</a> The dataset was originally created for the intended purpose of building credit scoring models. It consists of features that can be used to probabilistically determine the likelihood of a borrower defaulting on a loan or not.

Accurately classifying a borrower is important to financial institutions as it mitigates the risk of credit default. Furthermore, the integrated adoption of such a model can help decision makers to recommend appropriate financial instruments to consumers.

I will walk you through an exploratory data analysis of a dataset comprising of 11 features and 150,000 records. After which, I will train three classification models: 1) Logistic Regression, 2) Random Forest Classification, and 3) XGBoost Classification. Each model is evaluated using a ROC curve/AUC score. AUC scores range from 0 to 1, where 1 indicates a perfectly explanatory model, and 0 reflects the inverse (a perfectly incorrect model). A score of 0.5 indicates that the model is no better at explaining the probability of an outcome than a random guess.

SPOILER ALERT!: XGB won with an AUC score 0f 0.86

The complete notebook can be found here: <a href="https://github.com/drjodyannjones/JN-credit-scoring-analysis/blob/main/give-me-more-credit.ipynb"> View the Jupyter Notebook </a>.

The Slide deck for the analysis can be found here: <a href="https://github.com/drjodyannjones/JN-credit-scoring-analysis/blob/main/Give%20me%20More%20Credit.pdf"> View the Slide Deck </a>.







