# ETL Job Failure Prediction

Predict which Informatica ETL jobs are likely to fail, using workflow and session run history.

## Approach

- Exploratory analysis of workflow and session logs
- Logistic Regression, Decision Tree, KNN and Random Forest on run status

## Results

Accuracy between about 0.97 and 0.98 in the saved notebook output.

## Start here

[Informatica_Job_Analysis_refined.ipynb](Informatica_Job_Analysis_refined.ipynb)

## Data

Anonymised job logs, included as `Export_EDW.csv.zip`.
