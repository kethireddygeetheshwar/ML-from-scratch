# ML-from-scratch

A hands-on collection of fundamental machine-learning algorithms implemented from scratch in Python with NumPy and visualized with matplotlib. The goal is to understand the mathematics and learning dynamics behind simple linear classifiers rather than relying on a black-box library.

## What is implemented

| Algorithm | Task | Implementation |
|---|---|---|
| Random Linear Classifier | Binary classification | `randlin.ipynb` |
| Perceptron | Binary classification | `perceptron.ipynb` |

## Dataset

The notebooks use a small synthetic cat-vs-dog dataset with two numerical features:

- Whisker length (cm)
- Ear flappiness index

The dataset is intentionally simple so the learning process and decision boundary can be inspected visually.

## Concepts demonstrated

- Linear decision boundaries
- Random weight initialization
- Iterative weight updates
- Rosenblatt perceptron learning rule
- Training error and convergence
- 2D decision-boundary visualization
- Train/test evaluation on synthetic data

## Getting started

### Requirements

```bash
pip install numpy matplotlib jupyter
```

### Run the notebooks

```bash
jupyter notebook randlin.ipynb
jupyter notebook perceptron.ipynb
```

## Learning notes

The project focuses on understanding the mechanics that are often hidden behind high-level ML APIs: how weights are represented, how predictions are produced, how classification errors drive updates, and why a simple linear boundary can or cannot separate a dataset.

## Roadmap

- [ ] Add a reusable Python module instead of notebook-only implementations
- [ ] Implement batch gradient descent
- [ ] Add logistic regression from scratch
- [ ] Add train/validation/test evaluation utilities
- [ ] Compare scratch implementations against scikit-learn baselines
- [ ] Add unit tests for core mathematical operations
- [ ] Add experiment notes with accuracy and convergence comparisons

## Project philosophy

Each new algorithm should include the implementation, a small experiment, visual diagnostics, and a concise explanation of the mathematics behind it.
