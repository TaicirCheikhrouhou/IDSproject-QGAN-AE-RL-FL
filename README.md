# Federated Robust Intrusion Detection System Using Quantum GANs and Contrastive Adversarial Representation Distillation

## Overview
This project proposes a privacy-preserving and adversarially robust Intrusion Detection System (IDS) that leverages **Quantum Generative Adversarial Networks (QGAN)**, **Contrastive Adversarial Representation Distillation (CARD)**, and **Federated Learning (FL)**.

Traditional IDS models face several challenges:
- **Data imbalance and scarcity**: rare attack types (e.g., U2R, R2L) are underrepresented.  
- **Adversarial vulnerability**: small perturbations can evade detection.  
- **Data privacy**: organizations cannot share sensitive logs for centralized training.  

This hybrid approach addresses all three challenges by combining quantum-enhanced data generation, robust knowledge distillation, and federated learning for collaborative training without data sharing.

---

## Key Features
- **Quantum Data Augmentation (QGAN):** Generates synthetic attack samples to balance rare classes.  
- **Adversarially Robust Transfer Learning (CARD):** Distills robustness from a strong teacher model into a lightweight student model.  
- **Federated Learning Framework:** Enables collaborative IDS training without exposing raw data.  
- **Cross-Dataset Evaluation:** Benchmarked on NSL-KDD and CIC-IDS2017 datasets under clean and adversarial conditions.
