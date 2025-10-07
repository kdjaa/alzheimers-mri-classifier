
# 🧠 Alzheimer's MRI Classifier
---

### 🧩 Overview
This project applies transfer learning to classify brain MRI scans into four categories: NonDemented, VeryMildDemented, MildDemented, and ModerateDemented.

### ⚙️ Model & Techniques
- Base model: **DenseNet121 / EfficientNet / ResNet50** 
- Data preprocessing and augmentation.
- Class balancing using data augmentation.

### 📊 Results
- Validation Accuracy: **99%**
- Confusion Matrix & Accuracy/Loss curves included in notebook

### 📂 Dataset
- [Kaggle – medical-scan-classification-dataset](https://www.kaggle.com/datasets/arjunbasandrai/medical-scan-classification-dataset)

### 🚀 How to Run
```bash
git clone https://github.com/kdjaa/alzheimers-mri-classifier.git
cd alzheimers-mri-classifier
pip install -r requirements.txt
jupyter notebook
