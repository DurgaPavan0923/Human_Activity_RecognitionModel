# 🏃‍♂️ Human Activity Recognition (HAR)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![ML Models](https://img.shields.io/badge/Models-LogReg%2C%20XGBoost%2C%20DecisionTree-orange)
![DL Models](https://img.shields.io/badge/DeepLearning-CNN%2C%20LSTM-purple)
![google Colab](https://img.shields.io/badge/Colab-Compatible-yellow)

A machine learning and deep learning-based system for classifying human physical activities—such as walking, running, sitting, and standing—using sensor data from wearable devices (accelerometers and gyroscopes). This project includes preprocessing, training, and evaluation pipelines, making it ideal for smart health, fitness tracking, and ambient intelligence applications.

---

## 🚀 Project Highlights

- 📊 **Sensor-Based Classification**  
  Uses time-series data from accelerometers and gyroscopes to identify physical activities.

- 🧠 **ML & DL Models**  
  Implements Logistic Regression, Decision Trees, XGBoost, CNNs, and LSTMs for robust classification.

- 🧼 **Preprocessing Pipeline**  
  Includes normalization, windowing, feature extraction, and label encoding.

- 📈 **Evaluation Metrics**  
  Accuracy, precision, recall, F1-score, and confusion matrix for model comparison.

- 🧪 **Colab-Ready Notebook**  
  Fully executable in Google Colab with minimal setup.

---

## 🗂️ Folder Structure

```bash
HAR-Project/
│
├── data/                   # Raw and preprocessed sensor data
├── notebooks/              # Jupyter/Colab notebooks for training and evaluation
├── models/                 # Saved model weights and architectures
├── utils/                  # Helper functions for preprocessing and visualization
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## ⚙️ Setup Instructions

### 🔧 Local Setup

```bash
git clone https://github.com/SatChittAnand/Human_Activity_RecognitionModel.git
cd Human_Activity_RecognitionModel

```

### ☁️ Colab Setup

Just open the notebook in `notebooks/Human_Activity_RecognitionModel.ipynb` and run all cells. No local installation required.

---

## 📊 Dataset

You can use publicly available datasets like:

- [UCI HAR Dataset](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones)
- [WISDM Dataset](https://www.cis.fordham.edu/wisdm/dataset.php)

Or plug in your own wearable sensor data in `.csv` format.

---

## 🧠 Models Implemented

| Model Type       | Algorithms Used                          |
|------------------|-------------------------------------------|
| Machine Learning | Logistic Regression, Decision Tree, XGBoost |
| Deep Learning    | CNN, LSTM (for sequential time-series data) |

---

## 📈 Evaluation Metrics

- Accuracy  
- Precision & Recall  
- F1-Score  
- Confusion Matrix  
- ROC Curve (for binary classification)

---

## 📌 Applications

- 🏋️ Fitness Tracking System
- 🧘 Smart Health Monitoring  
- 🏠 Ambient Assisted Living  
- 📱 Wearable Device Intelligence  

---

## 🙌 Contributing

Pull requests are welcome! If you’d like to contribute preprocessing modules, new models, or dataset integrations, feel free to fork and submit.

---

## 📄 License

This project is licensed under the MIT License. See `LICENSE` for details.
