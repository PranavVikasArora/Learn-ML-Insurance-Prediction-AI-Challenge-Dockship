# Learn-ML-Insurance-Prediction-AI-Challenge-Dockship
The aim of this challenge is to predict whether the customer will be interested in purchasing additional insurance for vehicles. Building systems for customer segmentation which ease in targeting potential customers for selling products or services is a huge requirement in companies these days. The use may be of insurance, user subscription and many more.

The dataset consists of the following attributes:

id (Unique ID for the customer)
Gender
Age
Driving License (0: Not present, 1: have one)
Region_Code
Previously_Insured (1: already has insurance, 0: doesn't have)
Vehicle_Age
Vehicle_Damage (1: customer got vehicle damage in past, 0: no past history of damage)
Annual_Premium (Amount to be paid annually)
PolicySalesChannel
Vintage (Number of days customer has been in the company)
Response ('Target Column' ) (1: Customer is interested, 0: not interested)
as part of the "TRAIN.csv" file provided for training. No additional data may be used for training.

The test set consists of "TEST.csv" for all the same attributes as "TRAIN.csv" except for the target column. There is an additional "sample_submission.csv" provided to give an example submission

ipynb was coded on google collab since hyperparameter tuning and voting classifier require higher specs

ML_Insurance_GBMVoting code gives better accuracy(esp gbm2) also use VIF for variable selection not part of these notebooks
