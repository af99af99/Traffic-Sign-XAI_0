# Explainable AI for Traffic Sign Recognition

**Thesis Title:** Explainable AI for Traffic Sign Recognition: Enhancing Transparency and Reliability in Autonomous Vehicle Systems

This repository contains the implementation code of my Bachelor's thesis.  
The study focuses on traffic sign recognition using multiple convolutional neural network models, along with an analysis of model attention using Grad-CAM.

---

## Overview

Four CNN architectures were trained and evaluated on the Bangladesh Traffic Sign Dataset (BTSD):

- LeNet-5
- Sequential CNN
- MobileNetV2
- EfficientNetV2-S

The models were compared in terms of classification performance and attention behavior.

---

## Dataset

- Dataset: Bangladesh Traffic Sign Dataset (BTSD)
- Number of classes: 28
- Training images: 1,927
- Test images: 409

The training data was split into 80% for training and 20% for validation. The test set was kept separate for final evaluation.

---

## Experimental Setup

- All models were trained for 15 epochs
- Evaluation metrics: Accuracy, Weighted Precision, Weighted Recall, Weighted F1-score
- Explainability method: Grad-CAM
- Additional analysis: Attention consistency and heatmap intensity

---

## Results

Test set performance:

| Model              | Accuracy |
|--------------------|----------|
| LeNet-5            | 97.56%   |
| EfficientNetV2-S   | 79.71%   |
| MobileNetV2        | 64.06%   |
| Sequential CNN     | 61.37%   |

LeNet-5 achieved the highest classification accuracy on this dataset.  
EfficientNetV2-S showed relatively higher attention consistency among the models evaluated with Grad-CAM.

---

## Repository Contents

- Training notebooks for the four models
- Grad-CAM implementation
- Quantitative attention analysis

---

## Note

This work presents a comparative study of different CNN models and their explainability on a single dataset.  
The results should not be interpreted as evidence of robustness under adversarial conditions, adverse weather, or real-world autonomous driving scenarios.

---

## Author

Afroza Rahman  
Bachelor's Thesis Project