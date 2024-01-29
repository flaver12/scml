# FIFA Player Performance Analysis and Prediction

This project focuses on analyzing and predicting player performances in the FIFA video game series. Using data from FIFA 23, we explore various player attributes and build a machine learning model to predict players' potential ratings.

## Dataset

The dataset used in this project is the "FIFA 23 Complete Player Dataset", which can be downloaded from [Kaggle](https://www.kaggle.com/datasets/stefanoleone992/fifa-23-complete-player-dataset). It includes detailed attributes for every player available in the game, along with their ratings across different versions of FIFA.

## Features

The Jupyter Notebook `fifaplayer.ipynb` encompasses the following key components:

1. **Data Preprocessing**: Handling large datasets with optimized data types and imputing missing values.
2. **Exploratory Data Analysis**: Analyzing trends in player attributes like Agility, Ball Control, and Strength across different FIFA versions.
3. **Machine Learning Model**: Training a RandomForestRegressor model to predict player potentials in FIFA 23 based on historical data.
4. **Model Evaluation**: Using Mean Squared Error (MSE) and R-squared (R²) statistics to assess model performance.
5. **Result Visualization**: Comparing actual and predicted player potentials using scatter plots for a comprehensive evaluation of the model's accuracy.

## Requirements

To run this notebook, you will need the following Python libraries:
- pandas
- matplotlib
- scikit-learn
- seaborn

These can be installed via pip:
```
pip install pandas matplotlib scikit-learn seaborn
```

## Usage

1. Download the dataset from Kaggle and place it in the same directory as the Jupyter Notebook.
2. Ensure all required libraries are installed.
3. Run the Jupyter Notebook to see the analysis and model predictions.

