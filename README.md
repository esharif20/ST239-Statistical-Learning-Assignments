# ST239 Statistical Learning Assignment

This repository contains my solutions for the **ST239 Statistical Learning** assignment.  
The assignment is worth 100% of the module mark and is divided into four main questions, each focusing on different aspects of statistical learning and data science.

---

## Assignment Overview

### **Question 1 – Dimensionality Reduction of Feature Space**

- Dataset: `penguins.pkl` (344 penguins, 7 variables).
- Techniques applied:
  - **Principal Component Analysis (PCA)** → unsupervised, finds directions of maximum variance.
  - **Linear Discriminant Analysis (LDA)** → supervised, finds directions that best separate classes.
  - **Support Vector Machine (SVM)** (ST239 only) → classification with separating hyperplanes.
- Deliverables:
  - Visualisations of reduced feature space.
  - Explanation of variance captured by components.
  - Comparison of PCA vs LDA vs SVM results.

👉 Tests ability to **reduce feature space, visualise results, and interpret differences** between methods.

---

### **Question 2 – A Comparison of Clustering Techniques**

**Part (a): Computational Analysis**

- Datasets: 5 `.csv` files with different clustering structures.
- Techniques applied:
  - **Hierarchical clustering** (single, complete, average, medoid linkage).
  - **K-means clustering** (with optimal `k` selection).
  - **DBSCAN** (density-based clustering).
- Requirements:
  - Visualisations: dendrograms, cluster assignment plots.
  - Evaluation against true labels.
  - Discussion of strengths/weaknesses of each method.

**Part (b): Manual Hierarchical Clustering**

- Apply hierarchical clustering with **complete linkage** using **single matching distance** on a categorical dataset of animals.
- Draw dendrogram, explain algorithm, and interpret results.

👉 Tests understanding of **unsupervised learning methods**, both computational and conceptual.

---

### **Question 4 – Extended Data Analysis on Online Shopping Dataset**

- Dataset: `OnlineShopping.csv` (user sessions with categorical & numerical features, target = `Revenue`).
- Workflow:
  - **Exploratory Data Analysis**: summary statistics, visualisations.
  - **Preprocessing**: one-hot encoding, scaling, feature engineering.
  - **Model building**:
    - At least **1 probabilistic method** (e.g. logistic regression, Naive Bayes).
    - At least **2 other methods** (e.g. decision trees, random forest, SVM, k-NN).
  - **Evaluation**: accuracy, precision, recall, ROC-AUC.
  - **Interpretation**:
    - Expert-level: technical findings, metrics, variable significance.
    - Non-expert: plain English summary for decision-makers.
  - **Report writing**: conclusions, limitations, potential extensions.

👉 Tests ability to deliver a **full applied data science pipeline**: preprocessing → modelling → evaluation → reporting.

---

## Submission Components

- `Q1.ipynb` → Jupyter Notebook for Question 1.
- `Q2.ipynb` → Jupyter Notebook for Question 2.
- `Q4.ipynb` → Jupyter Notebook for Question 4.
- `ST239 Report - u5552234.pdf` → Final report with technical and non-technical analysis.

---

## Learning Outcomes

This assignment demonstrates skills in:

- Dimensionality reduction and supervised vs unsupervised learning.
- Clustering and critical comparison of algorithms.
- Synthesising module knowledge via structured mindmapping.
- End-to-end applied data analysis with real-world datasets.
- Communicating insights to both technical and non-technical audiences.
