# Titanic-PCA-Dimensionality-Reduction
A small code of Titanic-PCA-Dimensionality-Reduction
# 📉 Principal Component Analysis (PCA) on Titanic Data

This project contains a Jupyter Notebook that demonstrates the implementation of **Principal Component Analysis (PCA)**, a fundamental technique for **dimensionality reduction** in machine learning. The notebook applies PCA to a subset of the **Titanic Dataset** to transform the original features into a lower-dimensional space while retaining most of the variance.

---

## 🎯 Project Goals

The objective is to showcase the complete pipeline for performing PCA:

1.  **Data Preparation:** Load and select relevant numerical features from the Titanic dataset (`Age`, `Pclass`, `SibSp`, and `Survived`).
2.  **PCA Implementation:** Calculate the principal components (eigenvectors and eigenvalues) of the data's covariance matrix.
3.  **Transformation:** Use the derived principal components to project the original data into a new, lower-dimensional space (e.g., 2 components: PC1 and PC2). 
4.  **Visualization (Implied):** Prepare the transformed data for visualization to demonstrate feature separation in the new space.

## 🗃️ Dataset Used

The analysis is performed on the **Titanic Dataset**, which is loaded from a CSV file (likely `tested.csv` or similar). The key features used for PCA include:
* `Age`
* `Pclass` (Passenger Class)
* `SibSp` (Siblings/Spouses Aboard)
* `Survived` (The target variable, included in the final output for analysis)

## ⚙️ Technology Stack and Dependencies

The project relies on core Python libraries for numerical computing and data manipulation.

| Library | Role |
| :--- | :--- |
| **`pandas`** | Data loading, structuring, and manipulation. |
| **`numpy`** | Essential for linear algebra operations, including calculating eigenvectors, eigenvalues, and performing the final data transformation (`np.dot`). |

### Installation
```bash
pip install pandas numpy

```bash
pip install pandas numpy
