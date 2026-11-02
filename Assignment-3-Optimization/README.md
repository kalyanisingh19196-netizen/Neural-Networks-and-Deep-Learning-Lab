Assignment 3: Optimization, Learning-Rate Scheduling, and Regularization

Objective

Understand and implement different optimization algorithms, learning-rate scheduling techniques, and regularization methods to improve neural network training and performance.

Tasks

1. Gradient Descent Algorithms

Implement and compare:

* Batch Gradient Descent
* Stochastic Gradient Descent (SGD)
* Mini-Batch Gradient Descent

Analyse their convergence speed and training performance on a small dataset.

2. Optimizers

Using an MLP on a subset of Fashion-MNIST, compare:

* SGD with Momentum
* RMSprop
* Adam

Compare their performance using suitable evaluation metrics.

3. Learning-Rate Scheduling

Implement and compare:

* Constant Learning Rate
* Step Decay
* Exponential Decay

Investigate how learning-rate scheduling affects model convergence.

4. Overfitting and Regularization

Demonstrate overfitting and evaluate:

* Dropout
* L2 Regularization
* Data Augmentation

Compare training and validation performance.

5. Early Stopping

* Implement early stopping.
* Monitor validation loss.
* Stop training when validation performance stops improving.
* Identify the best model checkpoint.

6. Plain MLP vs Residual MLP

* Implement a plain Multilayer Perceptron.
* Implement a Residual Multilayer Perceptron.
* Compare their training and validation performance.
* Analyse convergence and accuracy under controlled training conditions.

Technologies Used

* Python
* NumPy
* Matplotlib
* Pandas
* Scikit-learn
* TensorFlow/Keras (for dataset loading and image augmentation, where appropriate)

Expected Outcomes

* Understand different gradient descent algorithms.
* Compare optimization algorithms.
* Understand learning-rate scheduling.
* Identify and reduce overfitting.
* Implement regularization techniques.
* Apply early stopping.
* Compare plain and residual neural networks.

Evaluation Metrics

* Training Loss
* Validation Loss
* Test Accuracy
* Training Time
* Convergence Performance
