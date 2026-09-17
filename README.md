
# Assignment 07: Classification Algorithms Model Building

## Objective
The objective of this assignment is to evaluate the understanding and application of supervised machine learning classification techniques on a real-world dataset.

## Dataset
- **Name:** Breast Cancer Wisconsin Dataset
- **Source:** Scikit-learn library (`sklearn.datasets.load_breast_cancer`)
- **Target:** Binary classification (Malignant vs. Benign tumors)

---

## Key Components Implemented

### 1. Loading and Preprocessing
- Loaded the breast cancer dataset from `sklearn.datasets`.
- Checked for missing values to ensure data integrity.
- Split the dataset into **80% Training** and **20% Testing** sets.
- Performed feature scaling using **`StandardScaler`** to normalize the feature values.

### 2. Classification Algorithms Implemented
The following 5 classification models were trained and evaluated:
1. **Logistic Regression** (Linear model using sigmoid function)
2. **Decision Tree Classifier** (Tree-based threshold splitting)
3. **Random Forest Classifier** (Ensemble of decision trees)
4. **Support Vector Machine (SVM)** (Optimal hyperplane margin separation)
5. **k-Nearest Neighbors (k-NN)** (Distance-based majority voting)

---

## Model Comparison & Performance

| Algorithm | Accuracy Score |
| :--- | :--- |
| **Logistic Regression** | ~97.37% |
| **Decision Tree** | ~95.61% |
| **Random Forest** | ~96.49% |
| **Support Vector Machine (SVM)** | **~98.25% (Best)** |
| **k-Nearest Neighbors (k-NN)** | ~94.74% |

### Conclusion:
- **Best Performing Model:** **Support Vector Machine (SVM)** achieved the highest accuracy (~98.25%) because the linear boundary effectively separated the scaled tumor features.
- **Evaluation Metrics Used:** Accuracy, Precision, Recall, F1-Score, and Classification Report.

---

## Technologies & Libraries Used
- **Python**
- **Jupyter Notebook**
- **Pandas & NumPy** (Data manipulation)
- **Scikit-Learn** (Model building & preprocessing)

## How to Run the Code
1. Clone the repository or download the `.ipynb` file.
2. Open the notebook in Jupyter Lab or Jupyter Notebook:
   ```bash
   jupyter notebook
