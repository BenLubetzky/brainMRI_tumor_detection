# Brain Tumor Classification

> Binary classification of brain MRI scans — detecting the presence or absence of a tumor using transfer learning.

[![Kaggle](https://img.shields.io/badge/Kaggle-Notebook-blue?logo=kaggle)](https://www.kaggle.com/code/benlubetzky/brain-mri)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## Overview

This project classifies brain MRI images as **tumor (YES)** or **no tumor (NO)** using a deep learning pipeline built around transfer learning. The emphasis is not just on achieving high accuracy, but on understanding *why* the model performs the way it does — particularly given the challenges of a small, imbalanced dataset.

---

## Objectives

- **Transfer learning** — Leverage pretrained CNNs to extract meaningful features from a small medical dataset
- **Small dataset handling** — Apply data augmentation and regularization techniques to prevent overfitting
- **Class imbalance** — Explore strategies to handle unequal class distribution (e.g. class weighting, oversampling)
- **Result analysis** — Go beyond accuracy: examine confusion matrices, ROC curves, and misclassified examples to understand model behaviour

---

## Dataset

Brain MRI images labeled as tumor-positive or tumor-negative.

> The dataset is available directly on Kaggle. See the notebook link below for access and preprocessing details.

---

## Approach

1. **Preprocessing** — Resize, normalize, and augment MRI images
2. **Model** — Pretrained CNN backbone (transfer learning) with a custom classification head
3. **Training** — Addressed class imbalance through weighted loss / resampling
4. **Evaluation** — Accuracy, precision, recall, F1-score, confusion matrix, ROC-AUC

---

## Results

Key findings and model performance metrics are documented in the Kaggle notebook, including an analysis of failure cases and what they reveal about the model's limitations.

[View the full notebook on Kaggle](https://www.kaggle.com/code/benlubetzky/brain-mri)

---

## Inspiration

This project was inspired by [Brain MRI CNN + Transfer Learning](https://www.kaggle.com/code/gallo33henrique/brain-mri-cnn-1-transfer-learning) by Henrique Gallo.

---

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

*This readme was created with the help of Claude ai*
