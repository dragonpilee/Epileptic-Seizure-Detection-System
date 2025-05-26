# Epileptic Seizure Detection with EEG Signals

![Python](https://img.shields.io/badge/Language-Python-blue)
![Machine Learning](https://img.shields.io/badge/ML-Scikit--Learn-green)
![Keras](https://img.shields.io/badge/DeepLearning-Keras-orange)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-yellow)
![EEG](https://img.shields.io/badge/Data-EEG-purple)

> **Developed by Alan Cyril Sunny**  
> If you find this project helpful, please consider ⭐ [starring the repository](https://github.com/dragonpilee/epileptic-seizure-detection)!

---

![Epileptic Seizure](https://st1.thehealthsite.com/wp-content/uploads/2022/08/Epileptic-Seizures-1.jpg?impolicy=Medium_Widthonly&w=400)

---

## Table of Contents

- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Tech Stack](#tech-stack)
- [Implementation](#implementation)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## 🧠 Introduction

Epilepsy is a neurological disorder characterized by recurrent seizures, affecting millions of people worldwide. Early detection and diagnosis of epileptic seizures are crucial for effective treatment and management. EEG signals, which measure electrical activity in the brain, provide valuable information for diagnosing epilepsy.

This project leverages machine learning and signal processing techniques to develop a reliable and efficient system for detecting epileptic seizures using EEG data. By analyzing EEG recordings, the system can differentiate between seizure and non-seizure activity, facilitating timely intervention and medical assistance.

---

## ❓ Problem Statement

The visual inspection of EEG signals for epileptic seizure detection is time-consuming and subject to human error. Automated methods for detecting seizures in EEG data can significantly improve the efficiency and accuracy of diagnosis. This project addresses the need for a robust, automated system that can accurately identify epileptic seizure activity in EEG recordings.

---

## 📊 Dataset

The project utilizes the Bonn University EEG dataset, which consists of EEG recordings from subjects with and without epileptic seizures. The dataset contains multiple classes representing different types of EEG activity, with a focus on distinguishing seizure activity from non-seizure activity.

![Dataset](https://drive.google.com/uc?id=1nkOyWgqc1jc7LXD-aOfzOoA_cQa7eJ0p)

---

## 🧪 Methodology

- **Data Preprocessing**: Cleaning and preprocessing EEG data, feature extraction using wavelet transform and Hurst exponent calculation.
- **Model Development**: Training machine learning models such as Support Vector Machines (SVM), Random Forest, and LSTM neural networks for seizure detection.
- **Evaluation**: Assessing model performance using metrics such as F1-score, ROC curves, and overall accuracy.

---

## 🛠️ Tech Stack

- **Python**: Programming language for implementing algorithms and data processing.
- **NumPy**: Numerical computation.
- **Pandas**: Data manipulation and analysis.
- **scikit-learn**: Machine learning algorithms and tools.
- **Keras**: High-level neural networks API.
- **Jupyter Notebook**: Interactive computing environment.
- **Google Compute Engine**: Backend for running scripts and cloud interaction.
- **Google Colab**: Cloud-based Jupyter notebook environment.

---

## 📝 Implementation

The project is implemented using Python and libraries such as NumPy, Pandas, scikit-learn, and Keras. Code is organized into Jupyter Notebooks for clarity and reproducibility, with detailed explanations and comments throughout.

---

## 📈 Results

The trained models demonstrate high accuracy and reliability in detecting epileptic seizures in EEG recordings. Evaluation metrics such as F1-score and ROC curves indicate the effectiveness of the proposed approach, highlighting the potential of machine learning in improving epilepsy diagnosis and management.

---

## 🚀 Usage

1. Clone the repository to your local machine.
2. Install the required dependencies listed in `requirements.txt`.
3. Follow the instructions in the Jupyter Notebooks for data preprocessing, model training, and evaluation.
4. Experiment with different machine learning algorithms and parameters to improve model performance.

---

## 🤝 Contributing

Contributions are welcome! If you have ideas for enhancements or bug fixes, feel free to open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

- Alan Cyril Sunny for contributions and support.
- Bonn University for the EEG dataset.
- Contributors to open-source libraries and frameworks.
- Research studies and literature sources for valuable insights.

---
