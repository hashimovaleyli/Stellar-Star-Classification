# Stellar-Star-Classification
Overview
This project demonstrates a machine learning pipeline for classifying stellar objects (Galaxy, Quasar, and Star) using a dataset of astronomical features such as right ascension angle, declination angle, and redshift. The steps include data cleaning, exploratory data analysis (EDA), Principal Component Analysis (PCA), and applying the k-Nearest Neighbors (kNN) classification algorithm.


Steps
1. Data Cleaning
Removed unnecessary ID columns.
Identified and removed outliers using boxplots.
Checked for missing values and duplicates.
Renamed columns for better readability and converted class labels to factors.
2. Exploratory Data Analysis (EDA)
Univariate Analysis: Histograms of features like ascension angle, declination angle, filters (ultraviolet, green, red), and redshift.
Multivariate Analysis: Boxplots of stellar class against right ascension angle.
Correlation Matrix: Visualized correlations between features using corrplot.
3. Principal Component Analysis (PCA)
Performed PCA on the dataset to reduce dimensionality.
Created scree plots and loading plots to visualize explained variance.
Generated biplots for the first three principal components.
4. k-Nearest Neighbors (kNN) Model
Split the dataset into training (70%) and testing (30%) sets.
Normalized the data for better kNN performance.
Trained a kNN classifier and evaluated it using accuracy, confusion matrix, and ROC curves.
Dataset
The dataset used in this project is publicly available. Download it from Kaggle. Ensure the file is placed in the working directory and named stellar_class.csv.
