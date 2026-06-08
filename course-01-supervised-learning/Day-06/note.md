# Day 6 — Cost Function for Logistic Regression

## 📌 What I Learned

Today I continued learning Logistic Regression and focused on how the model measures prediction errors using the Cost Function.

I also completed the labs and achieved 100% on the practice quiz.

---

## 🧠 Why Do We Need a Cost Function?

A machine learning model needs a way to measure how good or bad its predictions are.

The Cost Function helps us:

* Measure prediction errors
* Evaluate model performance
* Guide Gradient Descent toward better parameters

The goal is always to minimize the cost.

---

## 📊 Logistic Loss

In Logistic Regression, we cannot use the same cost function used in Linear Regression.

Instead, we use Logistic Loss (Log Loss).

### Desired Behavior

* If the prediction is correct → Low loss
* If the prediction is wrong → High loss

This encourages the model to make accurate predictions.

---

## 🎯 Simplified Cost Function

The overall cost function calculates the average loss across all training examples.

The objective is to find model parameters that minimize this cost.

---

## ⚙️ Relationship with Gradient Descent

Gradient Descent uses the cost function to determine how to update the model parameters.

Process:

1. Calculate cost
2. Calculate gradients
3. Update parameters
4. Repeat until the cost becomes small

---

## 💻 Practice

* Completed Logistic Loss Lab
* Completed Cost Function Lab
* Completed Practice Quiz

Score: 100/100 ✅

---

## 🧠 Reflection

Today helped me understand how Logistic Regression evaluates prediction errors. Although the mathematical formulas are still new to me, I now understand the main idea: the model uses a special cost function called Logistic Loss to measure mistakes and improve its predictions over time.

---

✨ Learning Machine Learning one step at a time.
