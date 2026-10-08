# Linear Regression with Gradient Descent

A simple Linear Regression project implemented from scratch using Python, NumPy, and Gradient Descent.

## 📌 Project Overview

This project implements a Linear Regression model to predict the profit of a restaurant based on the population of a city.

The model is trained using **Gradient Descent**. The main components of the learning algorithm, including the **Cost Function** and **Gradient Computation**, are implemented using Python and NumPy.

## 🧠 Concepts Covered

* Linear Regression
* Cost Function
* Gradient Descent
* Model parameters (`w` and `b`)
* Making predictions
* NumPy arrays and vectorized operations
* Training and evaluating a machine learning model

## 🛠️ Technologies

* Python
* NumPy
* Matplotlib

## 📊 Dataset

The dataset contains **97 training examples**.

Each example contains:

* **Input (`x`)**: Population of a city
* **Target (`y`)**: Profit of a restaurant in that city

## ⚙️ Model Training

The model starts with initial values for `w` and `b` and updates them using Gradient Descent to minimize the Cost Function.

After training, the model found approximately:

```text
w = 1.16636
b = -3.63029
```

The model can then use these learned parameters to predict the expected profit for new population values.

## 🔍 Example Predictions

For a population of **35,000**:

```text
Predicted profit: $4,519.77
```

For a population of **70,000**:

```text
Predicted profit: $45,342.45
```

## 📉 Training Result

During training, the Cost Function decreased as the number of iterations increased:

```text
Iteration    Cost
0            6.74
150          5.31
300          4.96
450          4.76
600          4.64
750          4.57
900          4.53
1050         4.51
1200         4.50
1350         4.49
```

The decrease in cost shows that the model was improving its predictions during training.

## ▶️ How to Run

Clone the repository:

```bash
git clone <your-repository-url>
```

Navigate to the project directory:

```bash
cd linear-regression-gradient-descent
```

Run the Python file:

```bash
python3 Linear_Regression.py
```

## 🎯 Purpose

This project was created as part of my Machine Learning learning journey to gain a deeper understanding of how Linear Regression and Gradient Descent work behind the scenes.

Rather than relying entirely on a machine learning library, the core parts of the algorithm were implemented and tested using Python and NumPy.
