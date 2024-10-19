# Temperature-Prediction-using-Regression-Models-on-Algerian-Forest-Fires-Dataset
Introduction
This project aims to predict temperature using the Algerian Forest Fires dataset. The dataset contains meteorological and forest fire-related features from two different regions of Algeria (Bejaia and Sidi Bel-abbes). By applying multiple regression models, this project seeks to estimate temperature, an important factor in understanding and managing forest fires.
Dataset
The Algerian Forest Fires dataset used in this project is publicly available. It contains features such as wind speed, humidity, rainfall, and several fire-related indices (FFMC, DMC, DC, ISI, etc.). The data has been preprocessed to handle missing values, remove outliers, and convert necessary columns to appropriate data types.
Steps Involved:
    Data Preprocessing: Handling missing values, feature conversions, outlier detection using the IQR method, and dropping irrelevant columns.
    Exploratory Data Analysis (EDA): Visualizing distributions, correlations, and class-wise analysis using histograms, boxplots, and heatmaps.
    Outlier Removal: Implementing the IQR method to remove outliers from critical features.
    Feature Scaling: Standardizing features using StandardScaler to improve model performance.
    Regression Models:
        Linear Regression
        Lasso Regression
        Ridge Regression
        ElasticNet Regression
        Cross-validated variants: LassoCV, RidgeCV, ElasticNetCV
Model Evaluation: Evaluating model performance using metrics like MAE, R² score, and RMSE.
Multicollinearity Check: Identifying and removing highly correlated features to reduce multicollinearity.

Results
The best performing models were found to be ElasticnetCV, achieving an MAE of 2.11915 and an R² score of 0.465
