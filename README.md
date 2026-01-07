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

### 📂 Data Setup (Crucial Step)
Since the dataset is large, it is not included in this repository. Please follow these steps to set up the data:

1.  **Download:** Go to [Kaggle PlantVillage Dataset](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset) and download the archive.
2.  **Extract:** Unzip the downloaded file.
3.  **Organize:** Move the extracted `PlantVillage` folder into the `data/raw/` directory of this project.
    * *Correct Path:* `YourProject/data/raw/PlantVillage/`
    * Inside this folder, you should see subfolders like `Tomato___Bacterial_spot`, `Pepper__bell___healthy`, etc.

## 🛠 Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/PlantVillage-DeepLearning-System.git](https://github.com/YOUR_USERNAME/PlantVillage-DeepLearning-System.git)
   cd PlantVillage-DeepLearning-System
