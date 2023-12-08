# DLone Kidney Disease Classification

## Workflows


    Update config.yaml
    Update secrets.yaml [Optional]
    Update params.yaml
    Update the entity
    Update the configuration manager in src config
    Update the components
    Update the pipeline
    Update the main.py
    Update the dvc.yaml
    app.py


```
#How to run?
```

### Steps: 

Clone the Repo

```bash
https://github.com/nikilsivakumar/DLoneKidney
```

### Step 1: Create Conda env after opening the repository 

```bash
conda create -n cnncls python=3.9 -y
```

```bash
conda activate cnncls
```

### Step 2: Install the requirements

```bash
pip install -r requirements.txt
```


#### cmd
-mlflow ui

### dagshub
[dagshub](https://dagshub.com)

MLFLOW_TRACKING_URI=https://dagshub.com/nikilsivakumar/DLoneKidney.mlflow \
MLFLOW_TRACKING_USERNAME=nikilsivakumar \
MLFLOW_TRACKING_PASSWORD=f3ccb698b3b0f38c4dae57bfc0bef36ae87b1f53 \
python script.py

Run this to export as env Variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/nikilsivakumar/DLoneKidney.mlflow
export MLFLOW_TRACKING_USERNAME=nikilsivakumar
export MLFLOW_TRACKING_PASSWORD=f3ccb698b3b0f38c4dae57bfc0bef36ae87b1f53

```

### DVC Command

1. dvc init
2. dvc repro
3. dvc dag