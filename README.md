# AMS 595 / DCS 525 – Python Project 3  
### PageRank, PCA, Linear Regression, and Gradient Descent  

This project implements four fundamental numerical algorithms in Python to illustrate core concepts in data science and optimization. Each task demonstrates how theoretical linear algebra and optimization methods can be applied to real computational problems.

---

## 🧩 Project Overview

### **Task 1: PageRank Algorithm**
- Implemented the PageRank method to compute the steady-state distribution of a small web network.  
- Solved using both the **dominant eigenvector** and **power iteration** approaches.  
- Visualized final PageRank scores showing page importance.

### **Task 2: Principal Component Analysis (PCA)**
- Applied PCA to standardized height–weight data (100 samples).  
- Computed covariance matrix, eigenvalues, and eigenvectors using `scipy.linalg.eigh`.  
- Reduced the 2D dataset to 1D along the first principal component and visualized the projection.

### **Task 3: Linear Regression via Least Squares**
- Built a regression model to predict house prices based on square footage, bedrooms, and age.  
- Solved $ X\beta = y $ using `scipy.linalg.lstsq` and validated with direct normal equations.  
- Calculated **RSS = 25**, **RMSE = 2.5**, and predicted price ≈ **\$1.45M** for a given test house.

### **Task 4: Gradient Descent Optimization**
- Minimized \( f(X) = \tfrac{1}{2}\|X - A\|_F^2 \) for random matrices \( A, X \in \mathbb{R}^{100\times50} \).  
- Implemented manual gradient descent loop with convergence tolerance \(10^{-6}\).  
- Verified rapid convergence to the analytical minimum and plotted loss reduction.

---

## 📊 Results Summary

| Task | Method | Key Output |
|------|---------|-------------|
| PageRank | Eigenvector + Iteration | Stable rank vector showing top pages |
| PCA | Eigen decomposition | 55.7% variance captured by PC1 |
| Regression | Least Squares | Predicted price = \$1.45M |
| Gradient Descent | Manual optimization | Loss ↓ to ~0 in 2 iterations |

---

## 📁 Repository Structure

