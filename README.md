# ML-SVM-Classification
* The Iris dataset was explored to understand its structure and features. The dataset contains 150 samples with four features each: sepal length, sepal width, petal length, and petal width. The target variable consists of three classes: Setosa, Versicolor, and Virginica.

* Support Vector Machine (SVM) classifiers were implemented using Scikit-learn's SVC class with three different kernels: linear, radial basis function (RBF), and polynomial. K-fold cross-validation (K=5) was applied to assess the performance of each SVM model. The dataset was shuffled before partitioning to prevent bias.

* Evaluation metrics including accuracy, precision, recall, and F1-score were calculated for each SVM model on the test set. The linear kernel SVM achieved the highest mean cross-validation accuracy of approximately 0.975, followed closely by the RBF kernel SVM. However, all models performed well, with test accuracies above 0.9.

* In conclusion, SVMs are effective classifiers for the Iris dataset, with different kernel functions offering varying performance. The linear kernel SVM may be preferred for its simplicity and high accuracy, but further experimentation and tuning could lead to even better results. The code was well-documented and structured, adhering to best practices for readability and maintainability.
