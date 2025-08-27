# 📊 Digits Classification with Linear Discriminant Analysis (LDA)

This project demonstrates **Linear Discriminant Analysis (LDA)** for both **dimensionality reduction** and **classification** using the classic **Digits dataset** from scikit-learn.  
It is a continuation of the PCA project, but here the focus is on **class separability** instead of variance.

---

## 📌 Project Objectives
- Apply **LDA** to the Digits dataset.
- Understand the difference between **PCA vs LDA**.
- Visualize data projected onto the **first 2 & 3 Linear Discriminants**.
- Analyze **explained separability ratio** via scree and cumulative plots.
- Perform **classification using LDA** and evaluate accuracy.

---

## 📂 Repository Structure
```
├── outputs/
│ ├── results/ # plots & evaluation metrics
│ └── models/ # saved models (future use)
├── notebooks/ # Jupyter notebooks
└── README.md # project documentation
```

---

## 📊 Results

- **Maximum components (PCA vs LDA):**
  - PCA → up to 64 (equal to number of features).
  - LDA → up to 9 (equal to `n_classes - 1`).

---

## 📌 Key Learnings
- **PCA** captures global variance, but does not use class labels.  
- **LDA** finds axes that best separate known classes.  
- On the Digits dataset, **LDA with 9 features** achieves almost the same accuracy as using all 64 features.  
- LDA projections in 2D or 3D give **clearer class clusters** compared to PCA.
