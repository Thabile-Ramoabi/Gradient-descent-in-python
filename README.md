# Linear Regression Using Gradient Descent

This project demonstrates how to perform simple linear regression using **gradient descent** in Python. It generates synthetic data, fits a line using gradient descent, and visualizes the result.

##  Files

- `linear_regression.py` - The main script containing the data generation, gradient descent implementation, and plotting.
- `data.csv` - CSV file containing the generated noisy data points (x, y).

##  Description

1. **Data Generation**:  
   Generates 50 random `x` values and corresponding `y` values using the linear equation `y = 2x + 5` with added Gaussian noise.

2. **Gradient Descent**:  
   Optimizes the slope `m` and intercept `c` to best fit the noisy data.

3. **Visualization**:  
   Plots the data points and the regression line using `matplotlib`.

##  Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib

Install dependencies with:

```bash
pip install numpy pandas matplotlib
```

## ▶ Run

```bash
python main.py
```

##  Output

- Prints the learned values of `m` and `c`
- Displays a plot of the data points and the fitted regression line

##  Reproducibility

The results are reproducible thanks to a fixed random seed (`np.random.seed(42)`).
