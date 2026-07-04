# GeneGuard AI

An end-to-end genomics machine learning pipeline for disease classification and biomarker discovery.

## Overview

GeneGuard AI is a machine learning project that classifies diseases using RNA-Seq gene expression data and identifies informative biomarkers. The project demonstrates a complete machine learning workflow, including data generation, preprocessing, feature selection, model training, evaluation, and visualization.

The pipeline is designed to be reproducible and follows good software engineering practices, including configurable parameters, logging, and organized output directories.

---

## Features

- Synthetic RNA-Seq gene expression data generation
- Data preprocessing and standardization
- ANOVA-based feature selection
- Support Vector Machine (SVM) classifier with RBF kernel
- 5-Fold Cross-Validation
- Model evaluation using Accuracy and Classification Report
- ROC Curve with AUC
- PCA visualization of genomic clusters
- Automatic logging and output saving
- Reproducible and modular pipeline

---

## Tech Stack

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## Machine Learning Pipeline

1. Generate synthetic RNA-Seq gene expression data.
2. Split the dataset into training and testing sets.
3. Standardize the features.
4. Select important genes using ANOVA.
5. Train an SVM classifier.
6. Perform 5-Fold Cross-Validation.
7. Evaluate the model on the test set.
8. Generate the ROC Curve.
9. Visualize genomic clusters using PCA.

---

## Results

The model is evaluated using:

- Accuracy Score
- Classification Report
- Cross-Validation Accuracy
- ROC Curve (AUC)
- PCA Visualization

---

## Output Screenshots

### Confusion Matrix
<img width="741" height="389" alt="image" src="https://github.com/user-attachments/assets/0894b55c-3041-4cb5-9dc0-cea9d8dbf529" />

### ROC Curve
<img width="905" height="490" alt="image" src="https://github.com/user-attachments/assets/f014e20b-bbe9-4f6e-b458-b671ee50b055" />


---

### PCA Visualization
<img width="1082" height="591" alt="image" src="https://github.com/user-attachments/assets/61aee6b3-0a65-4368-90c0-718dbb5d1118" />

---
## Installation

Clone the repository:

```bash
git clone https://github.com/Somiyakhan10/GeneGuard-AI.git
```

Navigate to the project directory:

## Future Improvements

- Train the model on real-world RNA-Seq datasets.
- Perform hyperparameter tuning.
- Explore deep learning approaches.
- Extend the project to multi-class disease classification.
- Build a web interface using Streamlit.
