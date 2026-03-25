# Machine Learning Lab 07: Deep Learning for Image, Text, and Activity Recognition

This repository contains four professional machine learning projects demonstrating the application of Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs/LSTMs) for diverse classification tasks.

## Projects Included

1.  **Handwritten Digit Classification (CNN)**
    - **Notebook:** `notebooks/CNN_MNIST.ipynb`
    - **Model:** Convolutional Neural Network (CNN)
    - **Dataset:** MNIST
    - **Features:** Hyperparameter tuning using KerasTuner (Grid Search).

2.  **Sentiment Analysis on Movie Reviews (RNN)**
    - **Notebook:** `notebooks/RNN_IMDB.ipynb`
    - **Model:** Recurrent Neural Network (RNN) with LSTM
    - **Dataset:** IMDB
    - **Features:** Sentiment classification (Positive/Negative) with optimized embedding layers.

3.  **Human Activity Recognition (CNN-LSTM)**
    - **Notebook:** `notebooks/CNN_LSTM_HAR_UCI.ipynb`
    - **Model:** Hybrid CNN-LSTM Architecture
    - **Dataset:** UCI HAR (Human Activity Recognition using Smartphones)
    - **Features:** Processes 3D time-series signal data from accelerometer and gyroscope.

4.  **News Topic Classification (RNN)**
    - **Notebook:** `notebooks/RNN_AG_New.ipynb`
    - **Model:** Recurrent Neural Network (RNN) with LSTM
    - **Dataset:** AG News
    - **Features:** 4-class multiclass classification with professional evaluation metrics (Weighted Precision/Recall/F1).

---

## Installation & Setup

### 1. Clone the Repository
```bash
git clone <repository-url>
cd <repository-folder>
```

### 2. Install Dependencies
Ensure you have Python 3.8+ installed. Install the required libraries via `pip`:
```bash
pip install -r requirements.txt
```

### 3. Folder Structure
The project follows a standard machine learning repository structure:
- `data/`: Contains all datasets (locally ignored for large distributions).
- `notebooks/`: Contains the Jupyter Notebooks for each project.
- `requirements.txt`: List of required Python packages.

---

## Evaluation & Professional Standards
- **Clean Code**: All notebooks follow professional standards with English documentation and standardized variable scopes.
- **Reproducibility**: Clear sequential steps from data loading to hyperparameter tuning and final evaluation.
- **Clean Diff**: All notebooks are committed with cleared outputs to ensure stable version control.
