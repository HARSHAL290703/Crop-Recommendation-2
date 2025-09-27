# 🌾 Crop Recommendation System

The **Crop Recommendation System** is a machine learning–based web application designed to assist farmers in making informed decisions about which crop to cultivate based on soil and environmental conditions. It leverages real-world agricultural data to provide accurate, real-time predictions through a user-friendly interface.

---

## 🚀 Features

* **ML Model Training & Comparison**

  * Logistic Regression → **96.5% accuracy**
  * Decision Tree → **98.7% accuracy**
  * Random Forest → **99.5% accuracy** *(Best Performer)*
* **Model Deployment**

  * Optimized Random Forest model saved as `.pkl`
  * Integrated with **Flask backend** for real-time predictions
* **Responsive Frontend**

  * Built with **HTML, CSS, and JavaScript**
  * Takes soil and environmental parameters (N, P, K, temperature, humidity, pH, rainfall) as inputs
  * Provides **instant predictions** for recommended crops
* **User-Centric Design**

  * Simple and intuitive interface, accessible for **non-technical users**
  * Real-time results with improved usability

---

## 🛠️ Tech Stack

* **Machine Learning:** Scikit-learn, Pandas, NumPy
* **Model Deployment:** Flask, Pickle
* **Frontend:** HTML, CSS, JavaScript
* **Dataset:** Kaggle Crop Recommendation Dataset

---

## 📊 Workflow

1. Data preprocessing and cleaning
2. Training multiple ML models
3. Model evaluation and accuracy comparison
4. Saving the best model (`Random Forest`) as `.pkl`
5. Flask backend integration
6. Building responsive frontend for prediction display

---

## 📌 How to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/HARSHAL290703/Crop-Recommendation-2.git
   ```
2. Navigate to project folder:

   ```bash
   cd Crop-Recommendation-2
   ```
3. Install required Python libraries:

   ```bash
   pip install -r requirements.txt
   ```
4. Run the Flask app:

   ```bash
   python app.py
   ```
5. Open the application in your browser:

   ```
   http://127.0.0.1:5000/
   ```

---

## 🌱 Impact

This system enables farmers to:

* Choose the **most suitable crop** for cultivation based on their soil/environmental inputs.
* Improve **yield and profitability** through data-driven decision making.
* Access a **simple, fast, and reliable tool** without needing technical expertise.

---
