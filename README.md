# AWS SageMaker Project

## Description
This project utilizes AWS SageMaker for data processing and machine learning tasks. The workflow includes data preparation, model training, and deployment using AWS services.

## Setup
### Install dependencies:
```sh
pip install -r requirements.txt
```
---
### Configure AWS credentials:
```sh
aws configure
```
Ensure you have the correct IAM permissions.
---
### Requirements
* sagemaker
* scikit-learn
* pandas
* numpy
* ipykernel
---
## Execution
Run the Jupyter Notebook in VS Code to process data and train models:
```sh
jupyter notebook Project.ipynb
```
Follow the step-by-step procedures inside the notebook.

---
## Notes
* AWS CLI was used for authentication and S3 bucket access.
* Ensure all necessary AWS permissions are granted for SageMaker operations.
