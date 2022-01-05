# Build an ML Pipeline for Short-Term Rental Prices in NYC
A project requirement for [Udacity Machine Learning DevOps Engineer Nanodegree](https://www.udacity.com/course/machine-learning-dev-ops-engineer-nanodegree--nd0821). For full details on the implementation of the project, check [notes.md](notes.md).

## For Reviewer
* Github: https://github.com/roy-salvador/nd0821-c2-build-model-workflow-starter
* W&B Project: https://wandb.ai/roy-salvador/nyc_airbnb

To run the released pipeline on a new sample of data with initial failure
```
mlflow run https://github.com/roy-salvador/nd0821-c2-build-model-workflow-starter.git \
             -v 1.0.1 \
             -P hydra_options="etl.sample='sample2.csv'"
```
To run the release with filtering of data points outside NYC successfully
```
mlflow run https://github.com/roy-salvador/nd0821-c2-build-model-workflow-starter.git \
             -v 1.0.2 \
             -P hydra_options="etl.sample='sample2.csv'"
```
