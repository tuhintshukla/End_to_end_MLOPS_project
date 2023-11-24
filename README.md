# End-to-end-Machine-Learning-Project-with-MLflow


## Workflows

1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the app.py



# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/someshnaman/End_to_end_MLOPS_project
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -p ./env python=3.8 -y
```

```bash
conda activate ./env
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```



## MLflow

[Documentation](https://mlflow.org/docs/latest/index.html)


##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/someshnaman/End_to_end_MLOPS_project.mlflow \
MLFLOW_TRACKING_USERNAME=someshnaman \
MLFLOW_TRACKING_PASSWORD=6e7e6b4e21fb207c4cbf0d4d7f20506e23e748cc \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/someshnaman/End_to_end_MLOPS_project.mlflow

export MLFLOW_TRACKING_USERNAME=someshnaman 

export MLFLOW_TRACKING_PASSWORD=6e7e6b4e21fb207c4cbf0d4d7f20506e23e748cc

```
