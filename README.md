# UCS761 Deep Learning Labs

Lab submissions for UCS761 Deep Learning. All implementations are from scratch using NumPy unless stated otherwise.

---

## Labs

**Lab 1: Perceptron and Logic Gates**
Built a perceptron from scratch and trained it on AND, OR, NAND, NOR gates. XOR is included to show where a single perceptron fails and why.

**Lab 2: From Hard Decisions to Calibrated Decisions**
Replaced the step function with sigmoid to get probabilities instead of hard 0/1 outputs. Explored how threshold choice affects real-world decisions like glass quality control.

**Lab 3: Logistic Regression on Glass Dataset**
Implemented binary cross-entropy loss and gradient descent on the UCI glass dataset. Evaluated model at two different thresholds.

**Lab 4: Multiple Linear Regression on Salary Dataset**
Built a linear neuron with MSE loss to predict salary from years of experience and test score. No activation function used since the output is a continuous number.

**Lab 5: Two-Layer Network with Backpropagation**
Implemented a hidden layer with tanh activation and wrote backpropagation manually using the chain rule. Compared output against a plain linear model on log-curve data.

**Lab 6: Deep Networks and Gradient Tracking**
Implemented five activation functions with their derivatives. Ran experiments on models of increasing depth (A through D) and tracked gradient norms to observe vanishing gradients. Also includes the DLQ5 guided workshop.

**Lab 7: CNN and Vision Models**
Covered convolution, parameter sharing, pooling, padding, and dropout. Trained a CNN on MNIST using Keras and compared it against a dense network.

---

## Files Needed to Run

Lab 3 requires glass.csv placed in the same directory as the notebook.
Lab 4 requires salary.csv placed in the same directory as the notebook.

glass.csv: UCI Glass Identification Dataset
salary.csv: [Kaggle Multiple Linear Regression Dataset](https://www.kaggle.com/datasets/hussainnasirkhan/multiple-linear-regression-dataset)

---

## Requirements

```
numpy
pandas
scikit-learn
tensorflow
jupyter
```

Install with:

```
pip install numpy pandas scikit-learn tensorflow jupyter
```
