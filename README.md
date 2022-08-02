# K-EmoPhone_SupplementaryCodes

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6851298)](https://doi.org/10.5281/zenodo.6851298)
This repository contains supplementary codes and labels for the **K-EmoPhone Dataset**.

For the detailed description of the dataset, please refer to:
> ...
---

## Usage

### Installation
```console
$ git clone https://github.com/Kaist-ICLab/K-EmoPhone_SupplementaryCodes.git
$ cd K-EmoPhone_SupplementaryCodes
```

You need to download the above **K-EmoPhone Dataset** into */data/* directory.

You also need to move the *EsmResponse-1966.csv* file to */data/* directory.

### Run
You can follow the jupyter notebook instructions in *K-EmoPhone-analysis.ipynb*.

---

## Results
The evaluation results will be in the */eval/* directory.

---

## Dependency modules
* mitosheet==0.1.412
* pandas==1.3.5
* pytz==2021.3
* cloudpickle==2.0.0
* ray==1.12.1
* numpy==1.21.6
* seaborn==0.11.2
* json==2.0.9
* altair==4.2.0
* optuna==2.10.1
* sklearn==1.0.2
* imblearn==0.9.0
* pyparsing==3.0.8
* xgboost==1.6.1
