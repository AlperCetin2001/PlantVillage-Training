# 🌿 PlantVillage: Agricultural Disease Detection System via Transfer Learning

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Academic_Research-purple)

## 📌 Abstract
This project presents an end-to-end Deep Learning framework for the automated detection of plant diseases using the **PlantVillage dataset**. By leveraging **Transfer Learning** with the **MobileNetV2** architecture, we aim to provide a lightweight, high-accuracy solution suitable for mobile deployment in resource-constrained agricultural environments. The system identifies 38 distinct classes across 14 crop species, addressing the critical challenge of global food security through early disease diagnosis.

## 🚀 Key Features
- **Architecture:** MobileNetV2 (Pre-trained on ImageNet) with custom classification head.
- **Data Engineering:** Robust data splitting (Train/Val/Test) to prevent data leakage.
- **Performance:** Optimized for inference speed (Low Latency) and high accuracy.
- **Reproducibility:** Structured according to strict Data Science standards.

## 📂 Dataset
The model is trained on the **PlantVillage dataset**, utilizing 54,303 labeled images.
- **Source:** [Kaggle - PlantVillage Dataset](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset)
- **Classes:** 38 (Disease vs. Healthy)
- **Preprocessing:** Rescaling, Augmentation, and Split-folders logic.

## 🛠 Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/PlantVillage-DeepLearning-System.git](https://github.com/YOUR_USERNAME/PlantVillage-DeepLearning-System.git)
   cd PlantVillage-DeepLearning-System
