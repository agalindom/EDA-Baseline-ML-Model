# Production Prediction Assignment

## Overview

The following project is a baseline prediction machine learning model

## Objective

Predict energy production for different treatment companies

## Table of contents
- [Data](#data)
- [Usage](#usage)
- [UseCase](#usecase)
- [Methodology](#methodology)
- [Results](#results)
- [Dependencies](#dependencies)

## Data
Contains the raw data and a processed folder where all the processed data from the different notebooks is located

## Usage
To successfully show the output of each of the notebooks
* Run: `conda env create -f environment.yml`

* Then run the notebooks in the followong order:
1. Download (downloads the data)
2. EDA & Preprocessing (Exploratory Data Analysis of the different variables in the dataset)
3. Experiment Harness & Imputation (Train test split & imputation of missing values)
4. Feature Engineering
5. Baseline (Regression baseline model)

## UseCase
- Dataset contains different values of treatment company and operator where some of these values in the dataset are unique
- Prediction of production will be performed independently of the treatment company using selected and engineered features and keeping all possible values of production in the train data

## Methodology 
- For feature engineering, group by features will be produced based on aggregations on operator/year and the top selected features that EDA show
- For the modelling part, a baseline regression will be developed based on 3 tree-based algorithms and using a 5 KFold split.
- Main metric will be RMSE

## Results
See Baseline Notebook

## Dependencies
- You can find the dependencies inside the environment.yml file




