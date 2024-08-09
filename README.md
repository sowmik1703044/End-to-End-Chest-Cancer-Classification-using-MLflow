# End-to-End-Chest-Cancer-Classification-using-MLflow


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


##### cmd
- mlflow ui


### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/sowmiksarker17044/End-to-End-Chest-Cancer-Classification-using-MLflow.mlflow \
MLFLOW_TRACKING_USERNAME=sowmiksarker17044 \
MLFLOW_TRACKING_PASSWORD=1ab39dbe9cc91a5de48e02e659a92c434ed594f8 \
python script.py


Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/sowmiksarker17044/End-to-End-Chest-Cancer-Classification-using-MLflow.mlflow

export MLFLOW_TRACKING_USERNAME=sowmiksarker17044 

export MLFLOW_TRACKING_PASSWORD=1ab39dbe9cc91a5de48e02e659a92c434ed594f

```