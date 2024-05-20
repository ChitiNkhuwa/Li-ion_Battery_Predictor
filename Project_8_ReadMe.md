# Predicting the Crystal System Class of Li-ion Batteries

## Solution Overview
This project aimed to build a model that could predict the crystal system class of Li-ion batteries using a dataset of their physical and chemical properties involved several steps:

### Process

#### Data Loading and Exploration
The dataset was loaded and explored to understand its structure, identify missing values, and examine the distribution of crystal systems.

#### Data Cleaning
Outliers were handled, data consistency was ensured, and data types were validated.

#### Feature Engineering
Relevant features were selected and scaled using StandardScaler.

#### Data Splitting
The data was split into training and testing sets.

#### Dimensionality Reduction
PCA was applied to reduce the dimensionality of the data for visualization purposes.

#### Model Training
A KMeans model with 3 clusters was trained on the PCA-transformed training data.

#### Model Evaluation
The model's performance was evaluated using silhouette score and Calinski-Harabasz score on the testing data.

#### Visualization
The clusters formed by the KMeans model were visualized using a scatter plot.

## Conclusion
The trained KMeans model achieved a reasonable level of performance in predicting the crystal system class of Li-ion batteries, as indicated by the evaluation metrics and visualization.

- **Silhouette Score**: 0.46453681514520423
- **Calinski-Harabasz Score**: 98.60947372803625

## Insights and Next Steps
The trained model could be used to predict the crystal system class for new, unseen Li-ion battery data.

## Dataset Link
The dataset used for this analysis can be found on Kaggle: [Crystal System Properties for Li-ion Batteries](https://www.kaggle.com/datasets/divyansh22/crystal-system-properties-for-liion-batteries).
.
