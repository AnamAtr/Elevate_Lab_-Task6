# Elevate_Lab_-Task6
# Iris Flower Classification Using K-Nearest Neighbors (KNN)

This project demonstrates how to use the K-Nearest Neighbors (KNN) algorithm to classify iris flowers into three species based on petal and sepal dimensions. It explores model evaluation, hyperparameter tuning, and visualization of decision boundaries.

## Objective
- Understand and implement KNN for classification problems.

## Dataset
- **Source**: https://www.kaggle.com/datasets/uciml/iris
- **Classes**: Setosa, Versicolor, Virginica
- **Features**: Sepal length, Sepal width, Petal length, Petal width

## Steps Performed

1. Loaded and explored the Iris dataset.
2. Normalized features using `StandardScaler`.
3. Trained `KNeighborsClassifier` with different values of **K** (1 to 10).
4. Evaluated performance using:
   - **Accuracy score**
   - **Confusion matrix**
5. Visualized decision boundaries using the first two features.

## Results

- Best accuracy was achieved at **K = 1**, showing a strong classification capability for simple datasets like Iris.
- The **confusion matrix** confirmed that Setosa is easily separable, while some overlap exists between Versicolor and Virginica.
- Decision boundary plots clearly illustrated how the classifier separates the feature space.

## Conclusion

- **KNN** is a powerful yet simple algorithm that performs well on small datasets with low dimensionality.
- **Normalization** is essential for distance-based algorithms like KNN to avoid bias from feature scale.
- Proper selection of **K** is critical — too low leads to overfitting, too high to underfitting.
- **Visualization** helped to interpret model behavior and potential confusion between classes.

