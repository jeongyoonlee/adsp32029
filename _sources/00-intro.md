# Introduction

Welcome to **ADSP 32029: Causal Models in Data Science**, a graduate-level course offered by the University of Chicago in Autumn 2025. This course provides a rigorous and comprehensive treatment of causal inference and machine learning methods, with a particular focus on their application to observational data for drawing robust causal conclusions.

## Instructor

**Jeong-Yoon Lee** is a Senior Manager in Applied Science at Uber, where he leads research and development in personalization, targeting, optimization, and causal inference for marketing applications.

Jeong is also leading the **CausalML project**, an open-source Python package that democratizes access to state-of-the-art causal machine learning algorithms. He has co-organized the CausalML tutorials and workshops at KDD since 2021.

As an avid participant in machine learning competitions, Jeong won the KDD Cup in 2012 and 2015 and was ranked in the top 10 at Kaggle in 2015. He also served as the KDD Cup co-chair at KDD 2018.

Prior to joining Uber, Jeong was a Sr. Research Scientist at Netflix, a Sr. Applied ML Scientist at Microsoft, and the Chief Data Scientist at Conversion Logic. 

Jeong received his Ph.D. in Computer Science from the University of Southern California and his B.S. in Electrical Engineering from Seoul National University.

## Course Overview

This course is structured around the [**Causal ML Book**](https://causalml-book.org/labs.html) by Victor Chernozhukov, Christian Hansen, Nathan Kallus, Martin Spindler, and Vasilis Syrgkanis, which serves as our primary textbook and guide through the evolving landscape of causal machine learning.

In an era where data-driven decision making is paramount, understanding causality—not just correlation—has become essential for researchers, analysts, and practitioners across domains. This course bridges the gap between traditional econometric approaches to causal inference and modern machine learning techniques, providing you with the tools to tackle complex causal questions in high-dimensional, noisy, and heterogeneous data environments.

## What You'll Learn

### Foundational Concepts
- **Linear regression** and its causal interpretation
- **Randomized control trials** as the gold standard for causal inference
- **Causal diagrams (DAGs)** for representing and reasoning about causal relationships
- Addressing fundamental challenges: **confounding** and **selection bias**

### Causal Machine Learning Techniques
- **High-dimensional regression** using regularization methods (Lasso, Ridge)
- **Nonlinear regression** with tree-based models and neural networks
- **Double Machine Learning (DML)** for debiased estimation in complex settings

### Causal Inference Designs
- **Heterogeneous Treatment Effects** and personalized causal inference
- **Instrumental Variables** for addressing endogeneity
- **Difference-in-Differences** for policy evaluation
- **Regression Discontinuity Designs** for quasi-experimental analysis


## Course Schedule
Please note that this schedule is tentative and subject to change at the instructor's discretion.

| Week | Dates | Topic | Assignments |
| ---: | ---: | :--- | :--- |
| **1** | 09/29 | Course Intro. Ch1 Introduction & Predictive Inference with Linear Regression. Ch2 Causal Inference via Randomized Experiments | |
| **2** | 10/06 | Ch3 Predictive Inference with High-Dimensional Linear Regression. Ch4 High-Dimensional Linear Regression and Causal Effects | |
| **3** | 10/13 | Ch5 Causal Inference: Conditional Ignorability and Propensity Scores. Ch6 Causal Inference via Linear Structural Equation. Ch7 Causal Inference with Directed Acyclic Graphs and SEMs | |
| **4** | 10/20 | Ch8 Modern Nonlinear Regression: Trees, Neural Networks, and Prediction Quality. Ch9 Statistical Inference in Nonlinear Regression Models | |
| **5** | 10/27 | Mid-Term Exam | |
| **6** | 11/03 | Ch10 Feature Engineering for Causal and Predictive Inference | |
| **7** | 11/10 | Ch11 DAGs: Good and Bad Controls for Causal Inference. Ch12: Unobserved Confounders, Instrumental Variables, and Proxy Controls | |
| **8** | 11/17 | Ch13 DML Inference Under Weak Identification. Ch14 Statistical Inference Under Weak Identification | |
| **9** | 12/01 | Ch15 Causal Machine Learning: CATE Estimation and Validation. Ch16: Causal Inference with Difference-in-Differences and DML. Ch17: Regression Discontinuity Designs in Causal Inference | |
| **10** | 12/08 | Group Project Presentations | |


## Contact Information

* E-mail: jeong at uber dot com
* Course GitHub Discussions: https://github.com/jeongyoonlee/adsp32029/discussions/
* Course GitHub Issue: https://github.com/jeongyoonlee/adsp32029/issues