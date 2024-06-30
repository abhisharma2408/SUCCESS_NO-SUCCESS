# Predicting_Success

## Overview

This project focuses on creating a classification model to predict the success of a new startup. The model is based on feature-based data and utilizes tree classifiers.

## Preprocessing

Before building the classification model, the data underwent preprocessing steps. These steps included handling missing values and encoding categorical variables.

## Handling Imbalanced Data

Upon analyzing the data, it was observed that the dataset was highly imbalanced. To address this issue, the SMOTE (Synthetic Minority Over-sampling Technique) algorithm was used to oversample the minority class.

## Usage

To use this project, follow these steps:

### Clone the repository.
- go to your desired directory in which you want to clone

```bash
    cd path/to/your/projectory
```
- now clone using the command 
```bash
    git https://github.com/abhisharma2408/SUCCESS_or_NOT.git
```

### Install the required dependencies.
- run the following command to intall all the required dependencies used in the code
```bash
    pip install -r requirements.txt
```

### Prepare your dataset by following the preprocessing steps mentioned in the Preprocessing section.
### Run the main script to train and evaluate the classification models.
### Analyze the evaluation results to identify the best performing models for your dataset.

## Classification Models

Three classification models were chosen for this project: Logistic Regression, KNN Classification, and Decision Tree Regression. To find the best parameters for each model, RandomizedSearchCV was employed.

## Evaluation

The models were evaluated using F1 score, ROC-AUC score, and the standard model.score metric. Based on these evaluations, two models were identified as the best performers, based on different accuracy measure

## Acknowledgements

Dataset : [Crunchbase_big_startup_success](https://www.kaggle.com/datasets/yanmaksi/big-startup-secsees-fail-dataset-from-crunchbase)