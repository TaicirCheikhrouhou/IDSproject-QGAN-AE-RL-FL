# AE-RL IDS: Intrusion Detection System Using Adversarial Learning and Quantum GANs

This repository contains the implementation of a privacy-aware, robust Intrusion Detection System (IDS) combining Adversarial Reinforcement Learning (AE-RL) and Quantum Generative Adversarial Networks (QGANs). The system is designed to detect evolving cyber attacks and handle data scarcity by generating realistic network traffic.

## 🔹 Project Overview

### Adversarial Reinforcement Learning (AE-RL)

Developed an IDS model that learns to adapt to evolving attack patterns using a reinforcement learning agent in an adversarial environment.

### Quantum GAN (QGAN)

Generated synthetic network traffic for both normal and attack behaviors to improve model generalization and address class imbalance.

### Federated Learning (Planned)

Designed to enable privacy-preserving collaborative training across multiple nodes without sharing raw data (implementation in progress).

## 🔹 Features

- Adaptive IDS capable of detecting diverse network attacks.
- Data augmentation with QGAN to handle rare attack classes.
- Modular pipeline for training, testing, and evaluation.
- Visualization of generated data and model performance.
- Jupyter notebooks for easy experimentation in Google Colab.

## 🔹 Requirements

- Python 3.8+
- PyTorch 1.9+ (for AE-RL)
- Qiskit 0.19+ or PennyLane 0.17+ (for QGAN)
- NumPy, Pandas, Matplotlib, Scikit-learn
- Optional: GPU support for QGAN training; Google Colab recommended for computational constraints.

## 🔹 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/TaicirCheikhrouhou/IDSproject-QGAN-AE-RL-FL.git
   ```

2. Navigate into the project folder:

   ```bash
   cd IDSproject-QGAN-AE-RL-FL
   ```

## 🔹 Usage

### Data Preparation

Load and preprocess datasets (e.g., NSL-KDD). Example in notebooks:

- Download NSL-KDD from [Kaggle](https://www.kaggle.com/datasets/hassan06/nslkdd) 

### QGAN Training

Train the Quantum GAN to generate synthetic network traffic.

### AE-RL IDS Training

Train the reinforcement learning agent in the adversarial environment.

## 🔹 Contributing

Contributions are welcome! Please fork the repo, create a feature branch, and submit a pull request. 

## 🔹 References

- [NSL-KDD Dataset](https://www.kaggle.com/datasets/hassan06/nslkdd).
- [OQAN](https://arxiv.org/abs/1901.08263).
- Adversarial Reinforcement Learning:[Survey on AE-RL](https://ieeexplore.ieee.org/document/8962174).

For questions or collaborations, contact us.
