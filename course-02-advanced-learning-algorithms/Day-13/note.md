# Day 21 - Decision Tree Learning (Week 4 - Course 2)

## Course

Machine Learning Specialization

### Course 2: Advanced Learning Algorithms

---

## Topics Covered

- Measuring Purity
- Choosing a Split: Information Gain
- Putting It Together
- One-Hot Encoding of Categorical Features
- Continuous-Valued Features
- Regression Trees (Optional)
- Decision Trees Lab

---

## What I Learned

### Measuring Purity

A decision tree tries to create groups where the examples are as similar as possible.

A node is **pure** when all examples belong to the same class.

Example:

✅ Pure Node

```
Spam
Spam
Spam
Spam
```

❌ Impure Node

```
Spam
Spam
Not Spam
Spam
```

The purer the node, the better the split.

---

### Information Gain

Information Gain measures how much a split improves the purity of the data.

The decision tree evaluates different features and chooses the one with the **highest Information Gain**.

Higher Information Gain = Better Split

---

### Building a Decision Tree

The learning process follows these steps:

1. Start with all training data.
2. Calculate the purity of the current node.
3. Test every possible feature.
4. Calculate Information Gain for each split.
5. Choose the best feature.
6. Repeat until a stopping condition is reached.

---

### One-Hot Encoding

Machine learning models cannot work directly with text values.

One-Hot Encoding converts categorical values into binary (0 or 1) features.

Example:

Color

```
Red
Blue
Green
```

becomes

| Red | Blue | Green |
|-----|------|-------|
|1|0|0|
|0|1|0|
|0|0|1|

---

### Continuous-Valued Features

Decision trees can also split numerical values.

Example:

Age > 25?

- Yes
- No

Instead of checking categories, they compare values against a threshold.

---

### Regression Trees

Decision trees are not only for classification.

They can also predict continuous values, such as:

- House prices
- Salaries
- Temperatures

These are called **Regression Trees**.

---

## Key Concepts

- Pure nodes contain similar examples.
- Information Gain measures the quality of a split.
- The tree always chooses the split with the highest Information Gain.
- One-Hot Encoding converts categorical data into numbers.
- Decision trees can work with both categorical and numerical features.
- Regression Trees predict continuous values.

---

## Key Takeaways

- Higher purity leads to better predictions.
- Information Gain helps select the best feature.
- One-Hot Encoding is necessary for categorical variables.
- Decision Trees support both classification and regression tasks.

---

## Achievements

✅ Completed Decision Tree Learning

✅ Completed Decision Trees Lab

✅ Achieved **100%** on the Practice Quiz

---

## Personal Reflection

Today I learned how decision trees decide the best way to split data using purity and Information Gain. I also learned how categorical features are converted using One-Hot Encoding and how decision trees can solve both classification and regression problems. This gave me a much deeper understanding of how decision trees are built from the ground up.

---

## Progress

- [x] Week 1 - Neural Networks
- [x] Week 2 - Neural Network Training
- [x] Week 3 - Advice for Applying Machine Learning
- [ ] Week 4 - Decision Trees (In Progress)

---

> 🌱 Understanding how models make decisions is just as important as building them.