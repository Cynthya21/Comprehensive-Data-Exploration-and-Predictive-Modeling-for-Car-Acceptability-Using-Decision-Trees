# Comprehensive Data Exploration and Predictive Modeling for Car Acceptability Using Decision Trees

## What is it?

This project focuses on predicting car acceptability using decision tree algorithms. The process involves a comprehensive exploration of a dataset, visualization of key factors affecting car acceptability, and the development of a predictive model. The project aims to provide insights into the factors influencing car acceptability and build a robust model to classify cars as acceptable or unacceptable.

## Files

- **myCarTrainDataset_2023.csv**: The training dataset used for model development.
- **myCarTestDataset_2023.csv**: The test dataset used for model evaluation.

## Key Features

### Data Exploration

- **Summary Statistics**: Detailed examination of the dataset to uncover patterns and insights.
- **Visualization**: Graphical representation of data to highlight important trends and relationships.

### Predictive Modeling

- **Decision Tree Construction**: Building a decision tree using the Hunt Algorithm, Gini impurity measure, and Greedy Strategy.
- **Pruning**: Simplification of the decision tree to improve generalization and reduce overfitting.
- **Performance Evaluation**: Use of a confusion matrix to assess the model's accuracy, precision, and recall.

## Data Exploration Details

- The training dataset contains attributes such as "buying," "maint," "persons," "safety," and the target variable "acceptance."
- No missing values were detected, ensuring a clean dataset ready for analysis.
- Notable class imbalance in the target variable, with more instances labeled as "unacc" compared to "acc."

## Visualization Insights

- **Acceptance Distribution**: Dominance of "unacc" (Unacceptable) cars.
- **Buying and Maintenance Costs**: High costs correlate with unacceptability.
- **Seating Capacity**: Cars with fewer than 3 seats are more likely labeled as unacceptable.
- **Safety Ratings**: High safety ratings correlate with acceptability.

## Predictive Modeling Details

- **Decision Tree Construction**: Utilized Gini impurity and Greedy Strategy to select the best split points for each attribute.
- **Pruning**: Post-pruning was applied to remove nodes that do not significantly contribute to the predictive power of the tree.
- **Confusion Matrix**: Generated to evaluate the model's performance on the test dataset.

