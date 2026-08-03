# Intelligent Threat Items Detection in Passengers' Baggage

A machine learning-based computer vision application for automated threat detection in X-ray baggage scans. The project evaluates multiple image classification models on the CLCXray dataset and integrates the best-performing model into an interactive graphical interface for Threat/Non-Threat prediction.

> **Confidentiality Notice:** This project was developed as part of a Khalifa University research project. Due to research and intellectual property considerations, the source code and trained models are not publicly available. This repository showcases the project's objectives, methodology, user interface, and key outcomes.

---

## Overview

Airport baggage screening is a critical component of aviation security but often relies on manual inspection, making the process time-consuming and susceptible to human error. This project investigates the use of machine learning to assist security screening by automatically classifying X-ray baggage scans as either **Threat** or **Non-Threat**.

Six machine learning models were evaluated using the **CLCXray** dataset. After comparing their performance, **EfficientNet** achieved the highest classification accuracy of **90.85%** and was selected for integration into a graphical user interface developed in JupyterLab.

The resulting application allows users to upload X-ray baggage images and receive an automated classification, demonstrating the potential of AI to support airport security operations.

---

## Project Workflow

```text
X-ray Baggage Scan
        │
        ▼
 Image Preprocessing
        │
        ▼
 Image Classification Model
        │
        ▼
 Threat / Non-Threat Prediction
        │
        ▼
 Graphical User Interface
        │
        ▼
 Classification Result
```

---

## Model Evaluation

Six machine learning models were trained and evaluated using the **CLCXray** dataset to identify the most suitable model for automated baggage screening.

After comparing model performance, **EfficientNet** achieved the highest validation accuracy of **90.85%** and was selected for deployment within the application.

The integrated system demonstrated an overall prediction accuracy ranging from **90%–96%** during testing.

---

## Limitation

- Supports binary classification (Threat / Non-Threat) only.

---

## Future Improvements

- Multi-class threat classification
- Object localization using bounding boxes

---

## Author

**Shahad Almazrouei**  
B.Sc. Computer Science (Artificial Intelligence)  
Khalifa University
