# 👁️ OcuScan AI – Explainable Multi-Disease Eye Diagnosis System

OcuScan AI is an AI-powered ophthalmology diagnostic system that performs multi-disease eye classification using retinal fundus images with Explainable AI (XAI) support through Grad-CAM visualization.

The system leverages EfficientNet-B0, transfer learning, and deep learning optimization techniques to detect multiple ocular diseases from retinal fundus images using the ODIR-5K dataset.

🌐 **Live Demo:**  
https://akshararathore23-ocular-disease-diagnosis.hf.space/

---

# 📌 About The Project

OcuScan AI is designed to assist in the early detection of retinal diseases through automated analysis of retinal fundus images.

Unlike traditional single-disease classification systems, this project supports multi-class ocular disease diagnosis and provides explainable predictions using Grad-CAM heatmaps.

The system is capable of detecting:

- Normal
- Diabetes
- Glaucoma
- Cataract
- Age-related Macular Degeneration (AMD)
- Hypertension
- Myopia
- Other retinal abnormalities

The project combines:

- Deep Learning
- Transfer Learning
- Explainable AI
- Medical Image Processing
- Real-time Prediction

---

# ✨ Features

✅ Multi-disease retinal image classification  
✅ Explainable AI using Grad-CAM heatmaps  
✅ EfficientNet-B0 transfer learning architecture  
✅ Image preprocessing and augmentation pipeline  
✅ Weighted loss handling for class imbalance  
✅ Real-time disease prediction  
✅ Confidence score generation  
✅ User-friendly web interface  
✅ Hugging Face deployment support  
✅ Scalable and modular architecture  

---

# 🧠 Tech Stack

## Languages
- Python

## Frameworks & Libraries
- PyTorch
- Torchvision
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- PIL
- Gradio

## Deep Learning Concepts
- CNN
- Transfer Learning
- EfficientNet-B0
- Grad-CAM
- Weighted BCE Loss
- Label Smoothing
- Data Augmentation

## Tools & Platforms
- Kaggle
- Google Colab
- Hugging Face Spaces
- GitHub

---

# 📂 Dataset

## ODIR-5K Dataset

The project uses the ODIR-5K (Ocular Disease Intelligent Recognition) dataset containing retinal fundus images for multiple eye diseases.

## Disease Categories

| Label | Disease |
|------|------|
| N | Normal |
| D | Diabetes |
| G | Glaucoma |
| C | Cataract |
| A | AMD |
| H | Hypertension |
| M | Myopia |
| O | Others |

---

# 🔍 Image Preprocessing

The preprocessing pipeline includes:

- Center Cropping
- Image Resizing (224×224)
- Image Normalization
- Random Rotations
- Horizontal Flips
- Vertical Flips
- Color Jittering

These preprocessing techniques improve model robustness and generalization on real-world retinal images.

---

# 🧠 Model Architecture

## Backbone
EfficientNet-B0

## Transfer Learning Strategy
- Pretrained ImageNet weights
- Initial layers frozen
- Fine-tuning on deeper layers

## Custom Classification Head
- Dropout Layers
- Fully Connected Layers
- ReLU Activation
- Final 8-Class Output Layer

---

# ⚙️ Training Configuration

| Parameter | Value |
|------|------|
| Optimizer | Adam |
| Learning Rate | 1e-4 |
| Batch Size | 32 |
| Loss Function | Weighted BCE |
| LR Scheduler | ReduceLROnPlateau |
| Label Smoothing | 0.1 |
| Epochs | 30 |

---

# 📊 Performance

## Best Validation Accuracy
**62.46%**

## Strong Performance Classes
- Cataract
- Myopia
- Diabetes

## Challenges
- Minority class prediction
- Hypertension classification
- Dataset imbalance

The project demonstrates promising results for real-world ophthalmic screening systems.

---

# 🔥 Explainable AI (Grad-CAM)

The project integrates Gradient-weighted Class Activation Mapping (Grad-CAM) to provide visual explanations for predictions.

Grad-CAM helps:

- Highlight pathological retinal regions
- Improve trust in AI predictions
- Assist clinicians in diagnosis verification
- Reduce black-box limitations

The generated heatmaps focus on:
- Optic Disc
- Macula
- Retinal Lesions
- Disease-specific abnormalities

---

# 🌐 Live Demo

## OcuScan AI Web Application
🔗 https://akshararathore23-ocular-disease-diagnosis.hf.space/

Users can:

- Upload retinal fundus images
- Receive disease predictions
- View confidence scores
- Generate Grad-CAM heatmaps

---

# 📷 Workflow

### Step 1
Upload retinal fundus image

### Step 2
Preprocessing pipeline executes

### Step 3
EfficientNet-B0 predicts disease class

### Step 4
Grad-CAM generates heatmap visualization

### Step 5
Final diagnosis and confidence scores displayed

---

# 📈 Future Improvements

- Vision Transformer (ViT) integration
- Ensemble learning models
- Larger medical datasets
- OCT scan integration
- Mobile application deployment
- Clinical report generation
- Real-time hospital integration
- Multi-label disease prediction

---

# 📚 References

- EfficientNet: Rethinking Model Scaling for CNNs
- Grad-CAM: Visual Explanations from Deep Networks
- ODIR-5K Dataset
- PyTorch Documentation
- WHO Vision Reports

---

# 👩‍💻 Author

## Akshara Rathore

B.Tech – Artificial Intelligence and Data Science  
Madhav Institute of Technology & Science, Gwalior

### Connect With Me

- GitHub: https://github.com/ItsAksharaRathore
- LinkedIn: https://linkedin.com/in/itsAksharaRathore
- Hugging Face Demo:
  https://akshararathore23-ocular-disease-diagnosis.hf.space/

---

# ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub.
