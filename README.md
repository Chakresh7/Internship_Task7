# Task 7: Support Vector Machines (SVM) – AI & ML Internship

## 📌 Objective

The goal of this task is to implement **Support Vector Machines (SVMs)** for binary classification using both **linear** and **RBF kernels**, visualize decision boundaries, and perform hyperparameter tuning.

---

## 📂 Dataset

* Used: **Breast Cancer Dataset** from Scikit-learn (`sklearn.datasets.load_breast_cancer`)
* Task: Binary classification (Malignant vs Benign)

---

## ⚙️ Steps Performed

1. **Loaded Dataset**

   * Prepared data for binary classification (features + labels).

2. **Trained SVM Models**

   * SVM with **Linear Kernel**
   * SVM with **RBF Kernel**

3. **Visualization**

   * Used 2D features for plotting decision boundaries.

4. **Hyperparameter Tuning**

   * Tuned parameters `C` and `gamma` using GridSearchCV and cross-validation.

5. **Evaluation**

   * Measured accuracy, confusion matrix, and classification report.

---

## 📊 Results

* **Linear Kernel SVM** achieved good separation with high accuracy.
* **RBF Kernel SVM** handled non-linear separation better.
* Hyperparameter tuning improved performance compared to default parameters.

---

## 🧠 What I Learned

* Concept of **margin maximization** in SVM.
* How **kernels (linear vs RBF)** affect classification.
* Role of hyperparameters `C` and `gamma`.
* How cross-validation helps in avoiding overfitting.

---

## 📝 Interview Questions Covered

1. What is a support vector?
2. What does the C parameter do?
3. What are kernels in SVM?
4. Difference between linear and RBF kernel?
5. Advantages of SVM?
6. Can SVMs be used for regression?
7. What happens when data is not linearly separable?
8. How is overfitting handled in SVM?

---

## 🛠 Tools & Libraries

* **Python**
* **Scikit-learn**
* **NumPy**
* **Matplotlib**

---

## 🚀 How to Run

```bash
git clone https://github.com/Chakresh7/Internship_Task7
cd <repo>
python svm_task.py
```
