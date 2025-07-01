Iris Classification using K-Nearest Neighbors (KNN)

This project demonstrates how to classify flowers from the Iris dataset using the K-Nearest Neighbors (KNN) algorithm. It walks through data preprocessing, normalization, model training, evaluation, and decision boundary visualization.

Project Steps

1. Load and Explore Dataset

   * Used the classic Iris dataset with 150 samples and 3 flower species.

2. Data Preprocessing

   * Dropped irrelevant columns (like Id)
   * Normalized numerical features using Min-Max Scaling

3. Modeling with KNN

   * Applied KNeighborsClassifier from sklearn
   * Performed train-test split (80/20)
   * Achieved 100% accuracy with K = 1

4. Hyperparameter Tuning

   * Experimented with K from 1 to 20
   * Plotted accuracy vs. K to find the optimal value

5. Model Evaluation

   * Evaluated using accuracy score, confusion matrix, and classification report

6. Visualization

   * Visualized decision boundaries using two features: Petal Length and Petal Width

Results

* Best K: 1
* Accuracy: 100%
* Confusion Matrix: Perfect classification across all species

Libraries Used

* Python (3.x)
* pandas, numpy
* matplotlib
* scikit-learn

Conclusion

This project showcases a complete classification pipeline using KNN. It’s a beginner-friendly example of how to approach machine learning tasks with clear logic, evaluation, and visualization.

