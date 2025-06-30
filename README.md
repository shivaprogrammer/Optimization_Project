Here is a complete `README.md` file for your project **"Optimization of Logistic Regression using Gradient Descent and Newton's Method"**:

---

# Optimization of Logistic Regression

This project implements and compares two optimization techniques—**Gradient Descent with Backtracking Line Search** and **Newton's Method**—to train a logistic regression model for binary classification using the Raisin dataset. The goal is to evaluate convergence, stability, and interpretability of custom-optimized models against Scikit-learn’s standard logistic regression.

## 📊 Dataset

**Raisin Dataset**
Contains geometric features of raisin samples used to classify them into two varieties:

* **Kecimen** (0)
* **Besni** (1)

### Features:

* `Area`, `Perimeter`, `MajorAxisLength`, `MinorAxisLength`, `Eccentricity`, `ConvexArea`, `Extent`, `Class`

## 🔧 Optimization Techniques

### 1. Gradient Descent with Backtracking

* Uses adaptive learning rate for controlled convergence
* Slower convergence, but flexible for large datasets
* Custom convergence checks and loss tracking

### 2. Newton's Method

* Utilizes second-order derivative (Hessian)
* Fast convergence with fewer iterations
* Sensitive to multicollinearity and singular Hessian

### 3. Scikit-learn Logistic Regression

* Serves as a baseline for performance comparison

## 📈 Visualizations & Metrics

* Loss and accuracy curves
* Weight convergence plots
* Confusion matrices
* Accuracy vs. iteration comparison across all models

## 🧪 Results Summary

| Method                   | Convergence | Stability | Complexity |
| ------------------------ | ----------- | --------- | ---------- |
| Gradient Descent         | Slow        | Stable    | Moderate   |
| Newton's Method          | Fast        | Sensitive | High       |
| Scikit-learn LogisticReg | Fast        | Stable    | Low        |

## 📁 File Structure

* `optimization_project.py`: Full implementation of the project
* `README.md`: Project documentation

## 🚀 How to Run

1. Clone this repo
2. Install dependencies:

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```
3. Run the Python file:

   ```bash
   python optimization_project.py
   ```

## 👥 Team Members

* Pooja Naveen Poonia (M24CSA020)
* Shivani Tiwari (M24CSA029)
* Suvigya Sharma (M24CSA033)

