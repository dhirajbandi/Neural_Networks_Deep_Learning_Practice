# Neural Network Practice Repository

## Overview
This repository contains a series of Jupyter notebooks where I have explored various neural network architectures, hyperparameter tuning, and dataset applications.

## Notebooks

### 1. Neural_practice.ipynb
- Used the **fashion_mnist** dataset instead of the default dataset.
- Tuned hyperparameters to improve validation accuracy and reduce loss.
- Key improvements:
  - Increased model capacity (more `Conv2D` layers and filters).
  - Added **Batch Normalization** for faster convergence.
  - Implemented **Dropout** to prevent overfitting.
  - Used **Learning Rate Scheduling** (`ReduceLROnPlateau`).
  - Implemented **Early Stopping** to avoid over-training.
- Included **Confusion Matrix Plot** for performance evaluation.

### 2. Neural_practice_1.ipynb
- Implemented basic string modifications and reversal.
- Developed functions for:
  - Replacing ‘python’ with ‘pythons’ in a string.
  - Determining letter grades based on class scores.

### 3. Neural_practice_2.ipynb
- Worked on different tasks and questions:
  - Mounted Google Drive for dataset access.
  - Performed various dataset-related operations.

### 4. Neural_practice_3.ipynb
- Loaded **MNIST dataset** without scaling images.
- Built multiple models with different activation functions and hidden layers.
- Mounted Google Drive to retrieve external datasets (`data.csv`).

### 5. Neural_practice_4.ipynb
- Modified model architecture based on given steps.
- Compared model accuracy (initial model vs. modified model):
  - Accuracy: **65.54%** (slight 0.1% drop from initial model).
- Completed additional tasks.

### 6. Neural_practice_5.ipynb
- Implemented **Denoising Autoencoder** techniques.

### 7. Neural_practice_6.ipynb
- ICP-6 Assignment.
- Installed necessary dependencies (`tensorflow`, `scikeras`).
- Completed assigned tasks.

## Getting Started
1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Install dependencies:
   ```bash
   pip install tensorflow numpy pandas matplotlib
   ```
3. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Author
**Dhiraj Bandi**  
Email: dhirajbandiwork@gmail.com  

---
This repository is for educational purposes and contains practice material in deep learning.
