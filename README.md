# RNN Sentiment Analysis on IMDB Dataset

This repository demonstrates natural language preprocessing and model building using Recurrent Neural Networks (RNNs) in TensorFlow/Keras on the IMDB sentiment classification dataset.

## Highlights
- **Data Preprocessing**: Word tokenization (`MAX_WORDS=10000`) and sequence padding (`MAX_LEN=500`).
- **Modeling**: Embedding layers, LSTM blocks, and a dense output layer.
- **Hyperparameter Tuning**: KerasTuner Random Search and Grid Search utilized to identify optimal architecture configuration.
- **Evaluation**: End-to-end evaluation metrics including Accuracy, Precision, Recall, and F1-score with visualization of Confusion Matrix.

## Getting Started

### Prerequisites 
Ensure Python 3 is installed and install the required dependencies:

```bash
pip install -r requirements.txt
```

### Execution
Open `RNN_IMDB.ipynb` in a Jupyter Notebook environment to run the training and evaluation steps linearly.
