# Research Documentation

This directory documents my research work, including thesis projects, experimental pipelines, and reproducibility notes.

---

## Current Research

**Memory-Efficient and Explainable Deep Learning Framework for Pneumonia Detection from Chest X-Ray Images Using a Quantized EfficientNet-B0**

### Objectives

Develop a deep learning framework that maintains diagnostic accuracy while enabling model interpretability and efficient deployment on resource-constrained hardware for medical imaging applications.

### Methodology

- Transfer learning with EfficientNet architectures for chest X-ray classification
- Post-training static INT8 quantization for model compression
- Explainability via Grad-CAM++, saliency maps, and feature visualization
- External validation on RSNA pneumonia detection dataset

### Highlights

- ROC-AUC: **0.9678**
- Accuracy: **91.83%**
- Sensitivity: **96.67%**
- Static INT8 compression: **71%**
- CPU latency reduced from **~120 ms to ~15 ms**
- External validation on the **RSNA dataset**

### Current Status

Under supervisor review. Code and documentation to be released upon approval.

### Reproducibility

Once published, this directory will contain:
- Full experiment tracking configuration
- Dataset preparation and preprocessing scripts
- Training and evaluation pipeline
- Model weights and quantization artifacts
- Reproducibility instructions

---

## Previous Work

### Bachelor Thesis

**Stock Forecasting for Nepali Stock Market using Machine Learning**

Time series forecasting and analysis of NEPSE market data using classical ML models and deep learning approaches.

*Repository: [Stock-Forecasting-NEPSE](https://github.com/sajan-ft9/stock-forecasting-nepse)*
