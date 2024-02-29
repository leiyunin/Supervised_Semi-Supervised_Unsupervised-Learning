# Supervised_Semi-Supervised_Unsupervised-Learning

# Overview
This study delves into the application of Supervised, Semi-Supervised, and Unsupervised Learning techniques on two distinct datasets: the Breast Cancer Wisconsin (Diagnostic) Dataset and the Banknote Authentication Dataset, employing a Monte-Carlo Simulation to assess and compare their performance:

- **Datasets Used**:
  - Breast Cancer Wisconsin (Diagnostic) Data Set for exploring different learning methodologies.
  - Banknote Authentication Data Set specifically for Active Learning Using Support Vector Machines.

- **Learning Approaches**:
  - **Supervised Learning**: Involves training an L1-penalized SVM with cross-validation on the cancer dataset, focusing on metrics like accuracy and F1-score.
  - **Semi-Supervised Learning**: Begins with a partially labeled training set, progressively incorporating unlabeled data into the training process based on their SVM decision boundary distance.
  - **Unsupervised Learning**: Applies k-means and spectral clustering without initial labels, assigning labels post-analysis based on cluster proximity and majority polling.

- **Evaluation and Analysis**:
  - Performance metrics such as accuracy, precision, recall, F1-score, and AUC are calculated for each method.
  - The effectiveness of each learning approach is compared using average scores from multiple runs.

- **Active Learning on Banknote Authentication**:
  - Conducts 50 iterations of training SVMs with incrementally added data points, comparing passive (random selection) and active (selection based on proximity to the hyperplane) learning strategies.
  - Averages test errors for a Monte Carlo simulation, plotting average test error against the number of training instances to derive insights into learning efficiency.

This comparative analysis aims to highlight the strengths and limitations of each learning method in handling complex datasets, offering insights into their practical utility and effectiveness in real-world applications.