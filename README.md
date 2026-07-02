# ML-from-scratch

Implementation of basic Machine Learning algorithms from scratch in Python using NumPy and matplotlib.

## Algorithms

| Algorithm | Type | File |
|-----------|------|------|
| Random Linear Classifier | Classification | `randlin.ipynb` |
| Perceptron | Classification | `perceptron.ipynb` |

## Random Linear Classifier

**Dataset:** Synthetic features (not images)
- **Whisker length** — measured in cm
- **Ear flappiness index** — numerical score representing ear flexibility

**How it works:**
- Generates synthetic cat vs dog data
- Trains a linear classifier with random weight initialization
- Plots decision boundary to visualize classification
- Evaluates accuracy on test set

**Run it:**
```bash
jupyter notebook randlin.ipynb
```
## What I Learned
 - How linear classifiers work at the mathematical level
 - Why random initialization needs iterative refinement
 - Visualizing decision boundaries in 2D feature space
 - How perceptron learning rule updates weights based on errors
## Next Steps
 - [ ] Add gradient descent for weight optimization
 - [ ] Compare all algorithms with scikit-learn equivalents
