# Day 20 - Decision Trees (Week 4 - Course 2)

## Course

Machine Learning Specialization

### Course 2: Advanced Learning Algorithms

---

## Topics Covered

- Decision Tree Model
- Decision Tree Learning Process

---

## What I Learned

### What is a Decision Tree?

A Decision Tree is a supervised machine learning algorithm used for both **classification** and **regression** tasks.

It makes predictions by asking a series of questions (decisions) about the input features until it reaches a final prediction.

Example:

```
Is Age > 30?
        │
   Yes      No
    │        │
Has Income > 50K?
    │
Yes      No
 │        │
Buy     Don't Buy
```

---

### Decision Tree Learning Process

A decision tree learns by repeatedly splitting the dataset into smaller groups.

At each step, it chooses the feature that best separates the data.

The goal is to create groups that contain similar examples.

This process continues until:

- The data is perfectly separated.
- A stopping condition is reached (maximum depth, minimum samples, etc.).

---

## Key Concepts

### Root Node
The first decision in the tree.

### Internal Node
A decision point that splits the data.

### Leaf Node
The final prediction or output.

---

## Advantages

- Easy to understand and visualize.
- Works with both numerical and categorical data.
- Requires little data preprocessing.
- Can model non-linear relationships.

---

## Limitations

- Can easily overfit if the tree grows too deep.
- Sensitive to small changes in the training data.

---

## Key Takeaways

- Decision Trees are supervised learning algorithms.
- They work by asking a sequence of questions.
- Each split aims to make the data more pure.
- Root Node → Internal Nodes → Leaf Nodes.
- Trees can solve both classification and regression problems.

---

## Achievements

✅ Completed Decision Tree Model

✅ Completed Decision Tree Learning Process

✅ Achieved **100%** on the Practice Quiz

---

## Personal Reflection

Today I started the final week of Course 2 and learned the fundamentals of Decision Trees. I now understand how a model can make predictions by asking a sequence of questions and splitting the data step by step until it reaches a final decision. Decision Trees are simple to understand and form the basis of more advanced algorithms such as Random Forests and Gradient Boosting.

---

## Progress

- [x] Week 1 - Neural Networks
- [x] Week 2 - Neural Network Training
- [x] Week 3 - Advice for Applying Machine Learning
- [ ] Week 4 - Decision Trees (In Progress)

---

> 🌱 Every lesson brings me one step closer to becoming a Machine Learning Engineer.