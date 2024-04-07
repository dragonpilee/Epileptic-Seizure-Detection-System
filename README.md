# Epileptic Seizure Detection with EEG Signals

![Epileptic Seizure](https://st1.thehealthsite.com/wp-content/uploads/2022/08/Epileptic-Seizures-1.jpg?impolicy=Medium_Widthonly&w=400)

Epileptic Seizure Detection with EEG Signals is a project aimed at developing a machine learning solution to detect epileptic seizures using EEG (Electroencephalography) signals. The project utilizes advanced techniques such as wavelet transform, feature extraction, and classification algorithms to accurately identify seizure activity in EEG recordings.

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

## Introduction

Epilepsy is a neurological disorder characterized by recurrent seizures, affecting millions of people worldwide. Early detection and diagnosis of epileptic seizures are crucial for effective treatment and management of the condition. EEG signals, which measure electrical activity in the brain, provide valuable information for diagnosing epilepsy.

This project aims to leverage machine learning and signal processing techniques to develop a reliable and efficient system for detecting epileptic seizures using EEG data. By analyzing EEG recordings, the system can differentiate between seizure and non-seizure activity, facilitating timely intervention and medical assistance for individuals with epilepsy.

## Problem Statement

The visual inspection of EEG signals for epileptic seizure detection is time-consuming and subject to human error. Automated methods for detecting seizures in EEG data can significantly improve the efficiency and accuracy of diagnosis. This project addresses the need for a robust, automated system that can accurately identify epileptic seizure activity in EEG recordings.

## Dataset

The project utilizes the Bonn University EEG dataset, which consists of EEG recordings from subjects with and without epileptic seizures. The dataset contains multiple classes representing different types of EEG activity, with a focus on distinguishing seizure activity from non-seizure activity.

![Dataset](https://drive.google.com/uc?id=1nkOyWgqc1jc7LXD-aOfzOoA_cQa7eJ0p)

## Methodology

The methodology employed in this project includes:
- Data Preprocessing: Cleaning and preprocessing EEG data, feature extraction using wavelet transform and Hurst exponent calculation.
- Model Development: Training machine learning models such as Support Vector Machines (SVM), Random Forest, and LSTM neural networks for seizure detection.
- Evaluation: Assessing model performance using metrics such as F1-score, ROC curves, and overall accuracy.

## Tech Stack

The project is built using the following technologies and libraries:
- **Python**: Programming language for implementing algorithms and data processing.
- **NumPy**: Library for numerical computation in Python.
- **Pandas**: Library for data manipulation and analysis.
- **scikit-learn**: Library for machine learning algorithms and tools.
- **Keras**: High-level neural networks API, running on top of TensorFlow or Theano.
- **Jupyter Notebook**: Interactive computing environment for code development and experimentation.
- **Google Compute Engine**: Backend for running Python3 scripts and interacting with Google Cloud services.
- **Google Colab**: Cloud-based Jupyter notebook environment provided by Google for running Python code and machine learning experiments.

## Implementation

The project is implemented using Python and various libraries such as NumPy, Pandas, scikit-learn, and Keras. The code is organized into Jupyter Notebooks for ease of understanding and reproducibility. Detailed explanations and comments are provided throughout the codebase to facilitate comprehension and future development.

## Results

The trained models demonstrate high accuracy and reliability in detecting epileptic seizures in EEG recordings. Evaluation metrics such as F1-score and ROC curves indicate the effectiveness of the proposed approach. The results highlight the potential of machine learning in improving the diagnosis and management of epilepsy.

## Usage

To utilize the project:
1. Clone the repository to your local machine.
2. Install the required dependencies listed in the `requirements.txt` file.
3. Follow the instructions in the Jupyter Notebooks for data preprocessing, model training, and evaluation.
4. Experiment with different machine learning algorithms and parameters to improve model performance.

## Contributing

Contributions to the project are welcome! If you have ideas for enhancements or bug fixes, feel free to open an issue or submit a pull request. Your contributions can help improve the effectiveness and usability of the epileptic seizure detection system.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

Special thanks to:
- Alan Cyril Sunny for his contributions and support throughout the project development.
- Bonn University for providing the EEG dataset used in this project.
- Contributors to open-source libraries and frameworks used in the implementation.
- Research studies and literature sources that provided valuable insights and guidance.
