# 🧠 Thyroid Disease Detection System

## 📌 Overview

This project predicts thyroid disease using Machine Learning based on patient medical data such as **T3, T4, TSH levels, age, and gender**.

The system applies **PCA (Principal Component Analysis)** for dimensionality reduction and **Nearest Centroid Classifier (NCC)** for classification.

---

## 🎯 Objective

* Detect thyroid disease (Yes/No)
* Build an end-to-end ML pipeline
* Visualize model performance
* Deploy a simple prediction interface

---

## 📊 Dataset

* Source: UCI Thyroid Dataset (via OpenML)
* Features:

  * T3
  * T4
  * TSH
  * Age
  * Gender

---

## ⚙️ Machine Learning Pipeline

1. Data Preprocessing
2. Missing Value Handling
3. Feature Scaling (StandardScaler)
4. PCA (Dimensionality Reduction)
5. Model Training (Nearest Centroid Classifier)
6. Model Evaluation

---

## 📈 Model Performance

* Accuracy Score
* Confusion Matrix
* Classification Report

---

## 📊 Visualizations

* PCA Explained Variance Graph
* PCA 2D Scatter Plot
* Confusion Matrix Heatmap

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* OpenML
* Google Colab

---

## 📁 Project Structure

```
├── app.py            # Streamlit app (UI)
├── main.py           # Model training script
├── model.pkl         # Trained NCC model
├── pca.pkl           # PCA transformer
├── scaler.pkl        # Feature scaler
├── requirements.txt  # Dependencies
├── README.md         # Project documentation
```

---

## 🚀 How to Run the Project

### 1. Clone Repository

```
git clone https://github.com/your-username/thyroid-disease-detection.git
cd thyroid-disease-detection
```

### 2. Install Dependencies

```
pip install -r requirements.txt
```

### 3. Run Application

```
streamlit run app.py
```

---

## 🧪 How It Works

1. User inputs medical values (T3, T4, TSH, etc.)
2. Data is scaled using saved scaler
3. PCA reduces dimensions
4. NCC model predicts disease
5. Result displayed to user

---

## 💡 Applications

* Healthcare decision support
* Early disease detection
* Clinical data analysis

---

## 🔮 Future Enhancements

* Improve model accuracy (Random Forest, SVM)
* Add web deployment (Streamlit Cloud)
* Integrate real-time hospital data

---

## 👨‍💻 Author

Syed Ashfan Abbas 
1BO23IS047



