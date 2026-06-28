# Heart Sound Classification using Machine Learning, Deep Learning, and Explainable AI (XAI)

## 📌 Project Overview

Heart diseases are one of the leading causes of mortality worldwide. Early diagnosis using heart sound analysis can help identify abnormal cardiac conditions at an early stage. This project develops an intelligent **Heart Sound Classification System** using **Machine Learning (ML)** and **Deep Learning (DL)** models to classify heart sounds into **Normal** and **Abnormal** categories.

The system uses the **PhysioNet Heart Sound Dataset** and applies signal preprocessing, feature extraction, model training, evaluation, and **Explainable AI (XAI)** techniques to improve interpretability.

The project compares multiple ML and DL models and integrates **SHAP Explainability** to understand feature importance and prediction reasoning.

---

## 🎯 Objectives

* Build an intelligent heart sound classification system.
* Compare multiple **Machine Learning** and **Deep Learning** models.
* Improve abnormal heart sound detection accuracy.
* Apply **Explainable AI (XAI)** for transparent medical predictions.
* Create a reliable system for early heart disease screening.

---

## 📂 Dataset

Dataset Used: **PhysioNet Heart Sound Dataset**

The dataset contains heart sound recordings collected from multiple patients and categorized into:

* **Normal Heart Sound**
* **Abnormal Heart Sound**

### Dataset Structure

```text
training-a/
training-b/
training-c/
training-d/
training-e/
training-f/
```

Each folder contains:

* `.wav` heart sound recordings
* `REFERENCE.csv` labels file


---

## ⚙️ Technologies Used

### Programming Language

* Python

### Libraries

* NumPy
* Pandas
* Librosa
* Matplotlib
* Scikit-learn
* TensorFlow / Keras
* XGBoost
* SHAP (Explainable AI)

---

## 🔬 Methodology

### 1. Data Collection

Heart sound recordings are collected from the **PhysioNet dataset**.

### 2. Preprocessing

* Noise reduction
* Resampling audio
* Normalization
* Data augmentation

### 3. Feature Extraction

Extracted audio features include:

* MFCC
* Chroma Features
* Spectral Contrast
* Zero Crossing Rate
* Mel Spectrogram
* Temporal Features

### 4. Model Training

### Machine Learning Models

* SVM
* Random Forest
* Decision Tree
* Logistic Regression
* KNN
* Gradient Boosting
* AdaBoost
* XGBoost

### Deep Learning Models

* CNN2D
* LSTM
* CNN + LSTM
* CNN + BiLSTM
* RNN
* Hybrid CNN-RNN-LSTM

### 5. Evaluation Metrics

Models are evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

### 6. Explainable AI (XAI)

This project uses **SHAP Explainability** to:

* Identify important heart sound features
* Explain prediction behavior
* Improve transparency in medical diagnosis

---

## 🏆 Results

| Model             | Accuracy |
| ----------------- | -------- |
| XGBoost           | 93.5%    |
| Gradient Boosting | 92.1%    |
| Random Forest     | 91.9%    |
| KNN               | 91.3%    |
| CNN + BiLSTM      | 91%+     |
| CNN2D             | 88%      |
| LSTM              | 81%      |

**Best Model:** XGBoost

The XGBoost model achieved the highest classification performance and demonstrated strong capability in detecting abnormal heart sounds.

---

## 🧠 Explainable AI (XAI)

SHAP (SHapley Additive exPlanations) is used to interpret predictions.

Features contributing to classification are visualized using:

* SHAP Summary Plot
* SHAP Force Plot
* Feature Importance Graph

This improves trust and interpretability in medical AI systems.

---

## 📊 Project Workflow

```text
Dataset Collection
        ↓
Preprocessing
        ↓
Feature Extraction
        ↓
ML & DL Model Training
        ↓
Performance Evaluation
        ↓
Best Model Selection
        ↓
Explainable AI (SHAP)
        ↓
Final Prediction
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/heart-sound-classification.git
```

Install required libraries:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python main.py
```

---

## 📈 Future Improvements

* Real-time heart sound classification
* Deployment using Streamlit or Flask
* Multi-class heart disease detection
* Attention Mechanism
* Transformer-based models
* Grad-CAM for deep learning explainability

- Deploy using Streamlit
- Add Explainable AI visualization
- Improve model accuracy
---

## 👩‍💻 Author

**Laxmipriya Rout**

AI/ML Research Enthusiast interested in:

* Medical AI
* Heart Sound Analysis
* Explainable AI (XAI)
* Deep Learning
* Healthcare Security

---

## ⭐ Acknowledgment

Special thanks to:

* PhysioNet Dataset
* TensorFlow Community
* Open-source contributors

If you found this project useful, consider giving it a ⭐ on GitHub.
