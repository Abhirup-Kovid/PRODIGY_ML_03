# PRODIGY_ML_03: Image Classification Using Support Vector Machines

This repository contains **Task 03** completed during my Machine Learning Internship at **Prodigy InfoTech**.

## 📋 Task Overview
Implement a Support Vector Machine (SVM) classifier to distinguish between images of cats and dogs using digital pixel feature matrices.

## 🛠️ Implementation Details
* **Preprocessing:** Images downsampled to 64x64 pixels and converted to grayscale to optimize structural data processing dimensions.
* **Feature Normalization:** Pixel intensity values scaled between [0, 1].
* **Model Configuration:** Evaluated using both Linear and Radial Basis Function (RBF) kernels, optimizing regularization parameters ($C=10$) to handle non-linear image spaces.