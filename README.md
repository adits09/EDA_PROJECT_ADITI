# EDA_PROJECT_ADITI
# Exploratory Data Analysis (EDA) - Phase 1

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a housing market dataset. The objective is to understand the structure of the dataset, clean and transform the data, and analyze relationships between different variables using statistical methods and visualizations.

## Dataset

The dataset contains information related to housing markets, including:

- City
- Year
- Month
- Sales
- Volume
- Median House Price
- Listings
- Inventory
- Date

## Phase 1 tasks:

- Loaded the dataset
- Performed basic statistical analysis
- Analyzed missing values
- Handled missing data using median imputation
- Cleaned the dataset by removing duplicate records and correcting data formats
- Applied data transformation techniques
- Performed Univariate Analysis (3 visualizations)
- Performed Bivariate Analysis (3 visualizations)
- Performed Multivariate Analysis (3 visualizations)

## Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Phase 2 Tasks

- Performed 1D Statistical Analysis
- Calculated statistical measures such as:
  - Mean
  - Median
  - Standard Deviation
  - Variance
  - Minimum
  - Maximum
  - Skewness
- Created distribution and box plot visualizations
- Performed 2D Statistical Analysis
- Calculated correlation and covariance between variables
- Performed linear regression analysis
- Created scatter plots and regression visualizations
- Performed 3D Statistical Analysis
- Created 3D scatter plots using multiple variables
- Analyzed correlations among three variables
- Performed K-Means Clustering
- Applied data standardization before clustering
- Used the Elbow Method to determine the number of clusters
- Analyzed and visualized the resulting clusters
- Performed Hierarchical Clustering
- Created a hierarchical clustering dendrogram
- Applied Agglomerative Clustering
- Analyzed and visualized the resulting clusters

## Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy


## Phase 3(a) task - PCA
- Standardization: Scaled the numerical features before PCA.
- Dimensionality reduction: Transformed five original features into five principal components.
- Explained variance: Identified how much variation each component captures.
- Component selection: Used cumulative explained variance to decide how many components to retain.
- Visualization: Plotted the first two principal components to inspect the data in two dimensions.
- Feature contributions: Examined the PCA loadings to understand which original features influence each component.


## Phase 3(b): Simple Linear Regression

- Implemented Simple Linear Regression on the Texas Housing dataset.
- Selected `sales` as the independent variable and `volume` as the dependent variable.
- Split the dataset into training (80%) and testing (20%) sets.
- Trained a Linear Regression model using Scikit-learn.
- Generated predictions for the test dataset.
- Evaluated model performance using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R-squared (R²) Score
- Visualized actual data points and the regression line.
- Displayed the regression equation using the model's intercept and coefficient.

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Conclusion: Simple Linear Regression was used to model the relationship between housing sales and sales volume. The model was trained and evaluated using a train-test split, and its performance was assessed using regression metrics and visualizations.
