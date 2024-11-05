# MLOps Production Ready Project

- Anaconda 
- VSCode
- Git

## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml





## MLflow

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/xans-me/mlops-example.mlflow \
MLFLOW_TRACKING_USERNAME=xans-me \
MLFLOW_TRACKING_PASSWORD=a0567893e0257a28fe9d5074a575d7d186e541dd \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/xans-me/mlops-example.mlflow

export MLFLOW_TRACKING_USERNAME=xans-me 

export MLFLOW_TRACKING_PASSWORD=a0567893e0257a28fe9d5074a575d7d186e541dd

```
