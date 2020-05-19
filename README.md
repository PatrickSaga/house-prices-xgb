# House-prices-xgb
Tutorial Ipython Notebook for the Kaggle competitions [Housing Prices Competition for Kaggle Learn Users](https://www.kaggle.com/c/home-data-for-ml-course) & [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques). 
The aim of this repository is to provide an example tutorial of a machine learning workflow from a beginner perspective, focusing on feature-wise analysis through detailed visualizations and feature engineering.
The current version of the code achieves a public score of 13545.39 based on [RMSE](https://en.wikipedia.org/wiki/Root-mean-square_deviation) metric for the Housing Prices Competition for Kaggle Learn Users competition, leading to a Top 3% result in the leaderboard.
The current version of the code achieves a public score of 0.12532 based on [RMSE](https://en.wikipedia.org/wiki/Root-mean-square_deviation) metric (with logarithm differences) for the House Prices: Advanced Regression Techniques competition, leading to a Top 25% result in the leaderboard.
 

## Kaggle competition description
From the competition [homepage](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/):
> Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.
> With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

## Table of contents
1. Load data
2. Data exploration (EDA)
3. Missings cleaning
4. Feature engineering
5. Data preparation
6. Parametrization of the XGB model
7. Prediction and submit

### Dependencies
- [IPython](http://ipython.org/)
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [SciKit-Learn](https://scikit-learn.org/stable/)
- [SciPy](https://www.scipy.org/)
- [Seaborn](https://seaborn.pydata.org/#)
- [Matplotlib](https://matplotlib.org/)
- [XGBoost](https://xgboost.readthedocs.io/en/latest/#)
- [LightGBM](https://lightgbm.readthedocs.io/en/latest/#)


## Contributors
Patrick Sánchez Galea ([Kaggle profile](https://www.kaggle.com/saga21))
