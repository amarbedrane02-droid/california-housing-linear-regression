# Multivariate Linear Regression from Scratch



Predicting house prices on the California Housing dataset using only Python and NumPy.



## Method

- Prediction: dot product of features and weights, plus a bias

- Cost: sum of squared errors divided by 2m

- Optimization: gradient descent (learning rate 0.0000005, up to 2.5 million iterations)

- Data split: 16,512 training samples and 4,128 test samples



## Results

- Training cost: about 0.359

- Test cost: about 0.333

- Exact least-squares solution (np.linalg.lstsq), training cost: about 0.26



## Notes

The features are not scaled, so a very small learning rate was needed.

Gradient descent stopped early, before reaching the exact solution.

Feature scaling would likely improve this.



## How to run

1. Install the libraries: `pip install -r requirements.txt`

2. Open `linear_regression.ipynb` in Jupyter or Kaggle and run the cells in order.

