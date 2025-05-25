# 🚗 Insurance Fraud Detection App

An interactive **Streamlit-based web application** that predicts whether an insurance claim is fraudulent based on user-provided details. Built with **machine learning**, this tool assists insurance providers in **detecting potential frauds** efficiently and transparently.

---

## 🌟 Features

* 🎯 **Accurate Fraud Predictions** using a trained Gradient Boosting Classifier
* 🧠 **Real-Time Inference** powered by `joblib`, `scikit-learn`, and `Streamlit`
* 📊 **Balanced Dataset** to ensure unbiased predictions
* ⚙️ **Preprocessing Pipeline** including Label Encoding and Standard Scaling
* 🔒 **User-Friendly Interface** with detailed feedback and prediction confidence
* 
---
## 📂 Project Structure

```bash
📁 Insurance-Fraud-Detection-App/
├── app.py                  # Streamlit frontend app
├── trained_model.py        # ML model training script
├── balanced_dataset.csv    # Cleaned & balanced dataset
├── fraud_model.pkl         # Trained ML model
├── scaler.pkl              # Scaler for numeric features
├── encoders.pkl            # Label encoders for categorical fields
```

---

## 🚀 Getting Started

### 🔧 Prerequisites

* Python 3.7+
* pip

### 📦 Install Dependencies

```bash
pip install -r requirements.txt
```

**`requirements.txt` sample:**

```txt
streamlit
scikit-learn
pandas
joblib
```

### ▶️ Run the App

```bash
streamlit run app.py
```

---

## 🧠 Model Training Overview

The `trained_model.py` script:

* Loads and cleans the dataset
* Balances fraud vs non-fraud samples
* Encodes categorical features
* Scales numeric features
* Trains a **Gradient Boosting Classifier**
* Evaluates accuracy and metrics
* Saves the model and preprocessing tools

---

## 🔍 How It Works

1. User provides claim details (e.g. month, age, accident area)
2. Inputs are encoded and scaled
3. The ML model makes a prediction
4. App displays if it's fraud or not, with confidence scores

---

## 📈 Model Performance

* ✅ **Balanced Accuracy** on test set
* 📋 Uses **classification report** for precision, recall, and F1-score
* ⚖️ Balanced dataset ensures **fairness across classes**

---


