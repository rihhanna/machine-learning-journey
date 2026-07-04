# Day 23 — Course 3 | Week 1: Unsupervised Learning

## Topics Learned

### Introduction to Unsupervised Learning
- Learned that unsupervised learning works with **unlabeled data**.
- The goal is to discover hidden patterns and structures within the data.
- Unlike supervised learning, there are no target labels (`y`) provided during training.

---

## K-Means Clustering

### What is Clustering?
- Clustering groups similar data points together.
- Each group is called a **cluster**.
- The algorithm tries to make data points within the same cluster as similar as possible.

### K-Means Algorithm
- Learned how K-Means works step by step:
  1. Randomly initialize K centroids.
  2. Assign each data point to its nearest centroid.
  3. Compute the new centroid by taking the mean of all assigned points.
  4. Repeat until the centroids stop changing (convergence).

### Cost Function
- Learned that the K-Means cost function measures how close data points are to their assigned centroid.
- The objective is to minimize the total distance between points and their centroids.

### Random Initialization
- Learned that different random initializations can produce different clustering results.
- Running K-Means multiple times helps find a better solution.

### Choosing the Number of Clusters (K)
- Learned that selecting the correct value of K is important.
- Too few clusters may combine different groups.
- Too many clusters may split natural groups unnecessarily.

---

## Anomaly Detection

### What is Anomaly Detection?
- Detects unusual or rare examples that differ significantly from normal data.
- Common applications include:
  - Fraud Detection
  - Network Security
  - Medical Diagnosis
  - Manufacturing Quality Control
  - Server Monitoring

### Gaussian (Normal) Distribution
- Learned how normal data often follows a Gaussian distribution.
- Estimated the probability of each feature belonging to the normal distribution.

### Anomaly Detection Algorithm
- Calculated the probability of each example.
- Compared that probability with a threshold (ε).
- If the probability is below the threshold, the example is considered an anomaly.

### Evaluating an Anomaly Detection System
- Learned how to split data into:
  - Training Set
  - Cross Validation Set
  - Test Set
- Used Precision, Recall, and F1 Score to evaluate model performance.
- Selected the best threshold based on the highest F1 Score.

### Anomaly Detection vs. Supervised Learning
- Learned when anomaly detection is preferred over supervised learning.
- Anomaly detection is useful when abnormal examples are rare or difficult to collect.

### Choosing Features
- Learned that selecting informative and relevant features greatly improves anomaly detection performance.

---

## Programming Assignments

- ✅ K-Means Clustering Lab — 100%
- ✅ Anomaly Detection Lab — 100%

---

## Key Takeaways

- Unsupervised learning finds hidden patterns without labeled data.
- K-Means is one of the most popular clustering algorithms.
- Clustering groups similar data together automatically.
- Cost functions help optimize clustering performance.
- Anomaly detection identifies unusual observations.
- Gaussian distributions estimate how likely an example is.
- Precision, Recall, and F1 Score help evaluate anomaly detection models.
- Good feature selection leads to better model performance.

---

## Reflection

This week introduced me to the world of **Unsupervised Learning**. I learned how machines can discover patterns without labeled data using **K-Means Clustering**, and how **Anomaly Detection** identifies rare or unusual observations. These concepts expanded my understanding of machine learning beyond prediction and showed me practical techniques used in fraud detection, recommendation systems, cybersecurity, and many other real-world applications.

🎯 **Progress:** Week 1 of Course 3 completed successfully with **100%** in quizzes and programming assignments.