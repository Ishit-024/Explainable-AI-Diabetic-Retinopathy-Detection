# 🧠 Explainable AI for Diabetic Retinopathy Detection

An Explainable AI-based framework for **early detection and severity grading of Diabetic Retinopathy (DR)** using retinal fundus images.

This system integrates **deep learning segmentation, vascular biomarker extraction, and interpretable machine learning models** to support transparent clinical decision-making.

---

# 🚀 Key Features

• Retinal Vessel Segmentation using **U-Net with ResNet34 Encoder**

• Vascular Biomarker Extraction
- Vessel Density
- Tortuosity
- Bifurcation Count
- Average Vessel Width

• DR Severity Prediction using **Gradient Boosting Regressor**

• Multimodal Prediction
- Retinal image features
- HbA1c clinical parameter

• Explainable AI
- Random Forest Feature Importance
- GradCAM Visualization

---

# 🧠 Model Pipeline

Fundus Image  
↓  
Preprocessing (CLAHE, ROI Masking, Denoising)  
↓  
U-Net + ResNet34 Vessel Segmentation  
↓  
Vascular Biomarker Extraction  
↓  
Gradient Boosting Regressor  
↓  
Explainable AI (GradCAM + Feature Importance)

---

# 📊 Results

| Metric | Value |
|------|------|
| Dice Score (Segmentation) | 0.79 |
| Classification Accuracy | 95.74% |
| Quadratic Weighted Kappa | 0.981 |

---


# ⚙️ Tech Stack

Python  
PyTorch  
OpenCV  
Scikit-Learn  
Segmentation Models PyTorch  
NumPy  
Matplotlib  

---

