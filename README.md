# Churn-Prediction-for-Telecom-company

##  Main Assignment Conditions
The telecom operator Interconnect would like to be able to forecast their churn of clients. 
If it's discovered that a user is planning to leave, they will be offered promotional codes and special plan options. 
Interconnect's marketing team has collected some of their clientele's personal data, including information about their plans and contracts.

## Goal
Develop a binary classification model for the telecom operator Interconnect that predicts whether a customer will leave the company soon based on the clientele's personal data, including information about their plans and contracts.

- Primary metric: AUC-ROC, it should be more than 0.75, preferably above 0.88.

- Additional metric: Accuracy.

## Data description
The data consists of files obtained from different sources:

- contract.csv — contract information
- personal.csv — the client's personal data
- internet.csv — information about Internet services
- phone.csv — information about telephone services
- In each file, the column customerID contains a unique code assigned to each client.

- Target feature: the 'EndDate' column equals 'No'.

- The contract information is valid as of February 1, 2020.
