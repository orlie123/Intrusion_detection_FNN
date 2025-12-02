# Intrusion Detection System using Feedforward Neural Network (FNN)

## Project Overview
This project implements an Intrusion Detection System (IDS) using a Feedforward Neural Network (FNN) on the UNSW-NB15 dataset. The goal is to classify network traffic as normal or attack (binary classification).

### Dataset
- **UNSW-NB15**: A comprehensive dataset for network intrusion detection, containing normal and attack traffic.
- Download from: [UNSW-NB15 Dataset](https://research.unsw.edu.au/projects/unsw-nb15-dataset)
- File used: `UNSW_NB15.csv` (place in the root directory).

### Features
- Data preprocessing: Handling missing values, encoding categorical features, scaling.
- FNN model: Built with TensorFlow/Keras, including dense layers and dropout for regularization.
- Evaluation: Accuracy, precision, recall, F1-score, confusion matrix.
- Visualization: Confusion matrix heatmap.

### Requirements
Install dependencies with:
pip install -r requirements.txt


### Usage
1. Download and place `UNSW_NB15.csv` in the root.
2. Open `intrusion-detection-fnn.ipynb` in Jupyter Notebook or JupyterLab.
3. Run the cells sequentially.

### Model Architecture
- Input layer: Based on feature count.
- Hidden layers: Dense with ReLU activation and dropout.
- Output layer: Sigmoid for binary classification.

### Results
- Achieves high accuracy on test data (details in notebook).

### License
MIT License
