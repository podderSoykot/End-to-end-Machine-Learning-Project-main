# End-to-end-Machine-Learning-Project


## Workflow
1. update config.yaml
2. update schema.yaml
3. update prams.yaml
4. update the entity
5. update the configuration manager in src config
6. update the components
7. update the pipeline
8. update the main.py
9. update the dvc.yaml 




# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/podderSoykot/End-to-end-Machine-Learning-Project-main
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mlproj python=3.8 -y
```

```bash
conda activate mlproj
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

MLFLOW_TRACKING_URI=https://dagshub.com/podderSoykot/End-to-end-Machine-Learning-Project-main.mlflow \
MLFLOW_TRACKING_USERNAME=podderSoykot \
MLFLOW_TRACKING_PASSWORD=32a62a6b9e7119b292593d2b339676175b4441ae \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/podderSoykot/End-to-end-Machine-Learning-Project-main.mlflow 

export MLFLOW_TRACKING_USERNAME=podderSoykot

export MLFLOW_TRACKING_PASSWORD=32a62a6b9e7119b292593d2b339676175b4441ae

```

