# Day 3 — Multiple Features, Vectorization & Gradient Descent

## 📌 What I Learned

Today I continued learning about Multiple Linear Regression and explored how machine learning models handle multiple features efficiently.

---

## 🧠 Multiple Features

Unlike simple linear regression, which uses one feature, multiple linear regression uses several features to make predictions.

### Example:

Predicting a house price using:

* House size
* Number of bedrooms
* Age of the house
* Location

The model combines all these features to produce a prediction.

### Model Formula

y = w₁x₁ + w₂x₂ + w₃x₃ + ... + b

Where:

* x = features (inputs)
* w = weights (importance of each feature)
* b = bias
* y = prediction

---

## ⚡ Vectorization

Vectorization is a technique that allows computers to perform calculations on many values at the same time instead of using loops.

### Benefits:

* Faster computation
* Cleaner code
* More efficient training

Instead of calculating each feature one by one, vectorization processes all features together using vectors and matrices.

---

## 📉 Gradient Descent for Multiple Linear Regression

Gradient Descent is used to find the best values for the weights and bias.

The algorithm:

1. Starts with initial values.
2. Calculates the prediction error.
3. Updates the weights and bias.
4. Repeats the process until the cost becomes small.

### Learning Rate (α)

The learning rate controls the size of each update step.

* Small learning rate → slow learning
* Large learning rate → may overshoot the minimum

Choosing the right learning rate helps the model converge efficiently.

---

## 🔑 Key Takeaways

* Multiple Linear Regression uses multiple features to make predictions.
* Vectorization makes computations much faster.
* Gradient Descent optimizes the model by reducing prediction error.
* Learning rate controls how quickly the model learns.

---

## 🧠 Reflection

Today’s lesson helped me understand how machine learning models work with real-world data that contains many features. The idea of vectorization was especially interesting because it showed how mathematical operations can make model training much more efficient.
