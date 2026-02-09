# ML-Models-Project


# Machine Learning Models Project

This repository contains implementations and comparisons of multiple **Machine Learning algorithms** using Python and scikit-learn. The project covers three learning categories:

- **Regression**
- **Classification**
- **Clustering (Unsupervised Learning)**

Each section uses a standard public dataset and evaluates several popular models.

---

## 📘 Regression Models

### 🔹 Models Implemented
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

### 🔹 Dataset Used
- California Housing Dataset (scikit-learn)
- Target variable: `MedHouseValue`

### 🔹 Dataset Structure
- Total columns: **9**
  - 8 feature columns
  - 1 target column

**Feature Names:**
- MedInc
- HouseAge
- AveRooms
- AveBedrms
- Population
- AveOccup
- Latitude
- Longitude

### 🔹 Evaluation Metrics
- R² Score
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)

### 🔹 Model Performance

- **Linear Regression**
  - R² = 0.5758
  - MAE = 0.5332
  - RMSE = 0.7456
  - Lowest performance due to linear assumptions

- **Decision Tree Regressor**
  - R² = 0.6221
  - MAE = 0.4547
  - RMSE = 0.7037
  - Better at capturing non-linear relationships

- **Random Forest Regressor**
  - R² = 0.8051
  - MAE = 0.3275
  - RMSE = 0.5053
  - Best performing model

### 🔹 Conclusion
- Random Forest outperformed the other models.
- Decision Tree achieved moderate accuracy.
- Linear Regression showed limited predictive power.

---

## 📗 Classification Models

### 🔹 Models Implemented
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest Classifier

### 🔹 Dataset Used
- Breast Cancer Wisconsin Dataset (scikit-learn)
- Target variable: `target`
  - 0 = malignant
  - 1 = benign

### 🔹 Dataset Structure
- Total columns: **31**
  - 30 feature columns
  - 1 target column

### 🔹 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score

### 🔹 Model Performance

- **Logistic Regression**
  - Accuracy = 0.9825
  - Precision = 0.9861
  - Recall = 0.9861
  - F1 Score = 0.9861
  - Best performing model

- **KNN**
  - Accuracy = 0.9561
  - Precision = 0.9589
  - Recall = 0.9722
  - F1 Score = 0.9655

- **Random Forest**
  - Accuracy = 0.9561
  - Precision = 0.9589
  - Recall = 0.9722
  - F1 Score = 0.9655

### 🔹 Conclusion
- Logistic Regression achieved the highest scores.
- KNN and Random Forest performed similarly.
- Dataset allowed very high classification accuracy.

---

## 📙 Clustering Models

### 🔹 Models Implemented
- K-Means Clustering
- Hierarchical (Agglomerative) Clustering

### 🔹 Dataset Used
- Iris Dataset (scikit-learn)
- Only feature columns used (unsupervised)

### 🔹 Dataset Structure
- Total columns: **4 feature columns**
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width

### 🔹 Evaluation Metrics
- Silhouette Score
- Davies–Bouldin Score

### 🔹 Model Performance

- **K-Means**
  - Silhouette Score = 0.4599
  - Davies–Bouldin Score = 0.8336
  - Slightly better cluster separation

- **Hierarchical Clustering**
  - Silhouette Score = 0.4467
  - Davies–Bouldin Score = 0.8035
  - Slightly more compact clusters

### 🔹 Conclusion
- Both clustering models performed well.
- K-Means separated clusters marginally better.
- Hierarchical clustering produced slightly tighter groups.

---

## 📌 Overall Summary

- Random Forest was the strongest model for regression.
- Logistic Regression was best for classification.
- Both K-Means and Hierarchical clustering were effective.
- The project demonstrates supervised and unsupervised learning workflows.

---

## 🛠 Technologies Used

- Python
- Google Colab
- scikit-learn
- pandas
- numpy

---

## 📂 Repository Structure

```
ML-Models-Project/
│
├── datasets/
├── regression/
├── classification/
├── clustering/
├── README.md

```

