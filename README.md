# 🧠 Brain Tumor Classification using Deep Learning & Explainable AI

## 📌 Project Overview
This project focuses on classifying brain tumor MRI images into four categories:
- Glioma
- Meningioma
- No Tumor
- Pituitary Tumor

We compare multiple deep learning models and use Explainable AI (Grad-CAM) to interpret predictions.

---

## 🚀 Models Used
- Custom CNN (from scratch)
- ResNet50 (Transfer Learning)
- MobileNetV2 (Transfer Learning)

---

## 🧪 Techniques Used
- Image preprocessing (224x224 resizing, normalization)
- Data augmentation
- Transfer learning
- Fine-tuning
- Grad-CAM for explainability

---

## 📊 Results Summary

| Model | Accuracy | Observation |
|------|---------|-------------|
| CNN | ~85% | Basic performance, more misclassification |
| ResNet50 | ~93% | Best performance, stable predictions |
| MobileNetV2 | ~87% | Fast but slightly less accurate |

---

## 🔍 Explainable AI (Grad-CAM)

Grad-CAM was used to visualize model attention:

- CNN → scattered focus
- ResNet50 → strong tumor-focused regions
- MobileNetV2 → moderate distributed focus

---

## 📷 Sample Outputs

- Accuracy/Loss Graphs
- Confusion Matrix
- Grad-CAM Visualizations
- Final Model Comparison Plot

---

## 🛠️ Tech Stack
- Python
- TensorFlow / Keras
- OpenCV
- Matplotlib
- NumPy
- Scikit-learn

---

## 📁 Project Structure
brain_tumor_comparison_all/
│
├── dataset/
├── notebooks/
├── results/
│   ├──CNN/
│   ├──GradCam/
│   ├──MobileNetV2
│   ├──ResNet50/
│   ├──ClassificationMetrics/
│   ├──classificationReport/
│   ├──confusionMatrix/
│   ├──mobilenetTrainingPlot/
└── README.md
---

## 📈 Key Highlights
- Multi-model deep learning comparison
- Medical image classification
- Explainable AI using Grad-CAM
- Confusion matrix + classification report analysis

---

## 🎯 Future Improvements
- Deploy as web app (Streamlit)
- Real-time MRI prediction system
- Integration with hospital diagnostic tools

---

## 👩‍💻 Author
Student Project – Deep Learning & Medical Imaging

---

## ⭐ If you like this project
Give a star ⭐ to support