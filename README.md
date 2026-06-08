
# Neural Networks Architectures
Assignment 3 of the Applied Data Science course, implementing and analyzing a variety of neural network architectures — from foundational MLPs to transformer-based models — using TensorFlow/Keras and PyTorch.

---

##  Notebooks Overview

### 1. `MLP_Binary_Classification.ipynb`
Implements a Multilayer Perceptron for binary classification to predict whether a credit card client will default on their next payment.

- **Dataset:** Default of Credit Card Clients
- **Key Experiments:** Optimizer selection (Adam, SGD, RMSprop), learning rate tuning, activation functions, network depth, dropout, batch normalization, L1/L2 regularization
- **Evaluation:** Precision & Recall (due to class imbalance)

---

### 2. `MLP_Regression.ipynb`
Applies a Multilayer Perceptron to a regression problem, exploring how architectural choices affect prediction performance on continuous targets.

---

### 3. `CNNs.ipynb`
Investigates CNN architectures for image classification using the **Fashion-MNIST** dataset.

- **Dataset:** Fashion-MNIST (10 clothing categories) 
- **Key Experiments:**
  - Kernel size 
  - Stride effects
  - Number of filters
  - Pooling operations
  - Network depth
  - Data augmentation
- **Transfer Learning:** Fine-tuned a pretrained **MobileNetV2** backbone
- **Evaluation:** Accuracy, Loss, F1-score, Learning curves

---

### 4. `RNNs.ipynb`
Explores recurrent architectures for sequence modeling tasks, comparing vanilla RNN, LSTM, and GRU networks.

---

### 5. `DistilBERT_fine_tuning.ipynb`
Fine-tunes a pretrained **DistilBERT** model (via HuggingFace Transformers) on the **BBC News** dataset for multi-class text classification, and benchmarks it against recurrent architectures (RNN, LSTM, GRU).

- **Dataset:** BBC News (5 categories: business, entertainment, politics, sport, tech)
- **Key Steps:** Tokenization, custom PyTorch Dataset, HuggingFace Trainer API, fine-tuning
- **Evaluation:** Accuracy, F1-score
- **Frameworks:** PyTorch, HuggingFace Transformers, TensorFlow

---

##  Mini Research Report

### `Research_about_Models.pdf` — *Which ML Models Are Actually Used in Industry?*

A literature and industry review summarizing which machine learning models dominate real-world production environments, based on Kaggle practitioner surveys and industry reports.
---

##  Datasets

The datasets used across these notebooks are hosted on Google Drive:

> **[Access Datasets on Google Drive](https://drive.google.com/drive/folders/18qsvEwK7gNg4TYvg9gdteyWXwI1hGzjU?usp=drive_link)**  
