# Brain Tumor Detection with Deep Learning

This project focuses on identifying brain tumors from MRI scans using **PyTorch** and **EfficientNet-B0**. As a 3rd-year Double Major student in Computer Engineering and Industrial Engineering, I developed this pipeline to explore the intersection of AI and medical diagnostics.

## Project Overview
The goal of this project is to create a reliable binary classifier that distinguishes between 'Tumor' and 'Healthy' brain MRI scans. I chose **EfficientNet-B0** as the backbone architecture because it provides state-of-the-art accuracy with significantly fewer parameters compared to traditional models like ResNet, making it ideal for specialized medical imaging tasks.

## ✨ Key Features
- **Framework:** Developed using PyTorch.
- **Transfer Learning:** Fine-tuned a pre-trained EfficientNet-B0 model to leverage ImageNet features.
- **Medical Metrics:** Implemented evaluation pipelines for **Confusion Matrix**, **F1-Score**, and **AUC-ROC** to ensure clinical relevance beyond simple accuracy.
- **Reproducibility:** Seeded all random processes to ensure consistent training results.

## Summary of Results (Local Run)
*Note: Due to the large size of the MRI dataset, the shared notebook contains the clean code architecture without training outputs. Below are the metrics achieved during my final local training session:*

- **Accuracy:** ~96.4%
- **AUC-ROC:** 0.98
- **Precision/Recall:** Balanced performance across both classes, ensuring high sensitivity for tumor detection.

## Tech Stack
- Python, PyTorch, Torchvision
- Scikit-learn (for metrics)
- Matplotlib & Seaborn (for visualization)

## Future Work
I am currently working on to improve accuracy and try with other models.

---
**Derya Yalçın** *Computer Engineering & Industrial Engineering Double Major Student*
