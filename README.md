# Linear Regression with Python

A simple Python project that uses **Linear Regression** to find the best-fitting line for a given set of `x` and `y` values, visualize the data, and predict new `y` values.

## Features

* Input custom `x` and `y` values
* Visualize the data points
* Train a Linear Regression model
* Calculate the slope (`m`) and intercept (`b`)
* Display the regression line
* Predict `y` for a given `x`
* Print the final equation in the form:

```text
y = mx + b
```

## Requirements

Install the required libraries:

```bash
pip install numpy matplotlib scikit-learn
```

## How to Use

Open the Python file and replace the placeholder values with your own data:

```python
x = np.array(['here']).reshape(-1, 1)
y = np.array(['and here'])
```

For example:

```python
x = np.array([1, 2, 3, 4, 5]).reshape(-1, 1)
y = np.array([2, 4, 5, 4, 6])
```

Run the program:

```bash
python main.py
```

The program will:

1. Plot the original data points.
2. Train a Linear Regression model.
3. Calculate the slope and intercept.
4. Plot the regression line.
5. Predict `y` for a given `x` value.
6. Print the equation of the regression line.

## Example Output

```text
1.0 1.2
[6.2]
The equation of the line is: y = 1.0x + 1.2
```

## Formula

The resulting regression line is represented as:

```text
y = mx + b
```

Where:

* `m` = slope of the line
* `b` = y-intercept
* `x` = input value
* `y` = predicted value

## Libraries

* **NumPy** — numerical arrays and data handling
* **Matplotlib** — data visualization
* **Scikit-learn** — Linear Regression model

## Project Purpose

This project was created as a simple introduction to **Linear Regression**, data visualization, and using machine learning models with Python.
