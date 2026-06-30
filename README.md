# ML-from-scratch
ML algorithms from scratch 

Implementation of basic Machine Learning algorithms using NumPy,scikit and matlpotlib

## What's Inside

Cat vs Dog classification using a random linear classifier implemented from scratch in Python.


- `randlin.ipynb` — Full implementation in Jupyter Notebook

## Dataset
Synthetic features (not images):
- **Whisker length** — measured in cm
- **Ear flappiness index** — numerical score representing ear flexibility

## How It Works
- Generates synthetic cat vs dog data based on whisker length and ear flappiness
- Trains a linear classifier with random weight initialization
- Plots decision boundary to visualize classification
- Evaluates accuracy on test set

## Run It
```bash
jupyter notebook randlin.ipynb
```markdown
## What I Learned
- How linear classifiers work at the mathematical level
- Why random initialization needs iterative refinement
- Feature scaling and its impact on convergence
- Visualizing decision boundaries in 2D feature space
## Next Steps
- [ ] Add gradient descent for weight optimization
- [ ] Implement perceptron learning rule
- [ ] Compare with scikit-learn's LogisticRegression
- [ ] Add more features (tail length, paw size)
