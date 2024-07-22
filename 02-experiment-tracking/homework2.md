# Q1. Install MLflow

mlflow, version 2.14.3

# Q2. Download and preprocess the data

4 files were saved to the output folder

dv.pkl
test.pkl
train.pkl
val.pkl

# Q3. Train a model with autolog

min_samples_split           2

# Q4 Launch the tracking server locally

The server was launched by the next command:

mlflow ui --backend-store-uri sqlite:///mlflow.db

# Q5 Tune model hyperparameters

Metric          Value
rmse            6.336044899923993

# Q6

Metric          Value
test_rmse       5.567408012462019
