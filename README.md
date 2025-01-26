
# Laptop Price Prediction Using Machine Learning


This project uses machine learning to predict laptop prices based on features such as brand, processor, RAM, storage, GPU, and display size. The goal is to build a predictive model that can estimate the price of a laptop accurately, assisting consumers, retailers, and manufacturers in making informed decisions.
## Features

- Brand: Laptop brand (e.g., Dell, HP, Apple).
- Processor: Type and speed of the processor (e.g., Intel i5, AMD Ryzen 7).
- RAM: Size of RAM (e.g., 8GB, 16GB).
- Storage: Storage type and capacity (e.g., 512GB SSD, 1TB HDD).
- GPU: Graphics card details (e.g., NVIDIA GTX 1650).
- Display: Display size and resolution (e.g., 15.6 inches, 1920x1080).
- Price: The target variable (laptop price).


# Requirements

## Package            Version

- numpy              1.18.5
- pandas             1.1.0
- matplotlib         3.3.0
- seaborn            0.10.0
- scikit-learn       0.23.0
- xgboost            1.3.3

## DataSet

- You will need a dataset that includes information about laptops such as brand, processor, RAM, storage, GPU, display, and price. A typical dataset might be in a CSV format, which can be loaded into a Pandas DataFrame for analysis.


# Exploratory Data Analysis (EDA)

## Data Collection:

- The first step is to gather the dataset. It can come from various sources such as CSV files, databases, or APIs.
- The dataset usually contains features (columns) and records (rows).
## Data Cleaning:

- **Handling Missing Data**: Missing or null values are a common issue. You can either drop rows/columns with missing values or fill them with statistical measures like mean, median, or mode.
- **Handling Duplicates**: Duplicate rows or entries can distort analysis, so identifying and removing duplicates is crucial.
- **Correcting Errors**: Ensure there are no outliers, incorrect data entries, or anomalies in the dataset.

## Bivariate Analysis:

-  **Correlation Analysis** : For numerical variables, calculate the correlation coefficient (e.g., Pearson's correlation) to see how strongly features are related to each other or the target variable.
- **Visualization** : Use scatter plots, pair plots, or heatmaps to visualize relationships between pairs of features or between a feature and the target variable.
- Scatter plots help in visualizing linear relationships.
- Pair plots are useful for seeing relationships between multiple variables.
- Heatmaps help in identifying correlation matrices.


## Identifying Outliers:

- Outliers can distort analysis and model performance. Use boxplots or z-scores to identify and decide how to handle them (remove or adjust).
## Feature Engineering:

- Based on insights from EDA, create new features or modify existing ones that may help in improving the model's predictive power.
- **Example**: Creating a new feature like price per GB for laptops, which can provide a more informative measure of pricing.
## Data Distribution:

- Visualize the data distribution of the target variable (e.g., price) using histograms or density plots to check if it’s skewed or follows a normal distribution. This can help decide which models or transformations to apply.

## Model Training
- The following models are trained to predict laptop prices:

- Linear Regression
- Random Forest Regressor
- XGBoost
- Ridge Regression
- Lasso Regression
- Support Vector Regressor (SVR)
- Gradient Boosting Regressor
- K-Nearest Neighbors Regressor (KNN)
- Decision Tree Regressor
## Evaluation Metrics
- R² (Coefficient of Determination): Measures the model's fit to the data.
- MSE (Mean Squared Error): Evaluates prediction accuracy.


## Contributing
- Feel free to fork this repository, open issues, and submit pull requests for improvements or bug fixes.