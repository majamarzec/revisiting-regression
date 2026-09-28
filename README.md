# Revision of regression from sklearn

1. diabetes_regressor.ipynb - task from [ML in Neuroscience workshop notebook](https://zvibaratz.github.io/ml_for_neuro/chapters/chapter_03/exercise_03.html) with explanatory comments
2. olds_ridge_sklearn.ipynb - task from [sklearn ols vs ridge  tutorial](https://scikit-learn.org/stable/auto_examples/linear_model/plot_ols_ridge.html)

# PyTorch with StatQuest
3. PyTorch_starter.ipynb - first custom NN & one-parameter training, in-depth starter tutorial

# Skills:

17 Sep
* theory & formulas
* visualisation & plotting with interesting kwargs
* evaluation metrics (mse, r2 (RSS, TSS))
* evaluation character on both train (how the model fits the data) and test data (predictive performance)
* bridge between theory and implementation (manual -> sklearn)
* simple (one independent variable) vs multiple linear regression

28 Sep
* theory on NN basics (weights & biases initialization, activation functions, hidden layers)
* the chain rule of derivatives in context of back propagation
* the most common optimiser: GD: learning late, step; minimum step size, maximum number of steps (derivative in 2D -> gradient in ND)
* tensors as not just renamed scalars/ vectors/ matrices/ndarrays but as PyTorch objects taking advantage of GPU/TPU hardware acceleration resulting in faster mathematical operations & automatic differentiation (that is a backbone for GD and back proparation)

# Environment (private):
dl_venv
