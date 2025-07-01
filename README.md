# K-Nearest Neighbors (KNN) Classification on Iris Dataset

## Overview
This project demonstrates the implementation of the K-Nearest Neighbors (KNN) algorithm for classifying species in the Iris dataset. The model is trained, evaluated, and visualized using standard ML practices.

## Key Steps
- Loaded the Iris dataset
- Normalized features using `StandardScaler`
- Split data into training and testing sets
- Trained models for different values of K (1 to 10)
- Evaluated each model using accuracy score
- Visualized accuracy vs K
- Displayed confusion matrix for best K
- Plotted decision boundaries using the first two features

## Visual Outputs
The following graphs were generated:
1. **Accuracy vs K Plot** – to visualize how model accuracy changes with different K values.
2. **Confusion Matrix** – for evaluating prediction correctness across classes.
3. **Decision Boundary Plot** – showing how the model separates classes using two selected features (for visual interpretation of model behavior).

## Libraries Used
- `scikit-learn`
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

## Outputs
- Accuracy vs K Plot
- Confusion matrix 
- Decision boundary plot

## Learnings
- How the KNN algorithm works
- Importance of normalization in distance-based models
- Impact of K value on classification performance
- How to evaluate classification models using accuracy and confusion matrix
- How to interpret decision boundaries in 2D space

## Dataset
- [Iris Dataset](https://www.kaggle.com/datasets/uciml/iris)
