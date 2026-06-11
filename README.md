# ML From Scratch 🧠

Implementations of core machine learning algorithms from scratch using **NumPy only** — no scikit-learn, no shortcuts.

Built to develop real algorithmic intuition, not just API familiarity.

---

## Algorithms Implemented

### Supervised Learning

| Algorithm | Type | Key Concepts |
|---|---|---|
| Linear Regression | Regression | Gradient descent, MSE loss |
| Logistic Regression | Classification | Sigmoid, BCE loss, decision boundary |
| K-Nearest Neighbors | Classification and Regression | Distance metrics, lazy learning |
| Support Vector Machine | Classification | Hinge loss, margin maximization |
| Naive Bayes | Classification | Bayes theorem, conditional probability |
| Perceptron | Classification | Step activation, weight update rule |

### Unsupervised Learning

| Algorithm | Type | Key Concepts |
|---|---|---|
| Principal Component Analysis | Dimensionality Reduction | Eigendecomposition, variance explained |

---

## Why From Scratch?

Most ML tutorials stop at `model.fit()`. This repo goes deeper:

- Every forward pass written manually
- Every update rule derived, not copied
- Every loss function implemented and understood

If you can write it without a library, you actually understand it.

---

## Structure

```
ml-from-scratch/
├── linear_regression.ipynb
├── logistic_regression.ipynb
├── knn.ipynb
├── svm.ipynb
├── naive_bayes.ipynb
└── perceptron.ipynb
└── pca.ipynb
└── README.md
```

---

## Key Concepts Covered

- **Loss functions** — MSE, BCE, Hinge — derived and implemented manually
- **Gradient descent** — weight and bias update rules from first principles
- **Activation functions** — Step (perceptron), Sigmoid (logistic regression)
- **Distance metrics** — Euclidean, Manhattan in KNN
- **Probability theory** — Bayes theorem applied in Naive Bayes
- **Linear algebra** — Eigendecomposition in PCA, dot products throughout

---

## Stack

- Python 3.x
- NumPy only

---

## Connect

Built by Arham 
Feel free to explore, fork, or reach out.
