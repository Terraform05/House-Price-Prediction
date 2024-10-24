# House Prices Prediction

## Overview and Goal 
This project focuses on predicting house sales prices based on a comprehensive dataset that includes 79 explanatory variables describing almost every aspect of residential homes in Ames, Iowa. The goal is to create a model that accurately predicts house prices.


- [SlideDeck Presentation]()
- [Writeup]()

## Dataset
The dataset contains various features related to house characteristics:
- Characteristics to be explored

The dataset was compiled by Dean De Cock and serves as an educational tool for data scientists looking for a modernized alternative to the Boston Housing dataset.

## Building (pip) (untested)

1. Make sure you running a python ver `>=3.10`
2. Clone this repository
3. Run `pip install -r requirements.txt` in the root directory of this repository

## Notebooks (in /notebooks)

| Notebook               | Description                                                                      |
| ---------------------- | -------------------------------------------------------------------------------- |
| `main.ipynb`           | Main notebook. Data exploration, analysis, features & model training             |
| `testing_models.ipynb` | Testing saved models from `main.ipynb` on dataset                                |


## Models (in /models) 
(load using `pickle.load`)

| File                    | Name                              | Time     | Mean 5-fold RMSE | Mean 5-fold r^2 | RMSE   | r^2    |
| ----------------------- | --------------------------------- | -------- | ---------------- | --------------- | ------ | ------ |
| `model.pkl`     | Model Name           | XX.Xs    | X.XXX           | X.XXX          | X.XXXX | X.XXXX |



## Citation
Montoya, A. & DataCanary. (2016). *House Prices - Advanced Regression Techniques*. Kaggle. [https://kaggle.com/competitions/house-prices-advanced-regression-techniques](https://kaggle.com/competitions/house-prices-advanced-regression-techniques)
