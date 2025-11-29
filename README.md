# Brain Tumor Detection using MobileNetV2

An automated medical imaging diagnostic tool that detects and classifies brain tumors from MRI scans using Deep Learning.

## 📊 Performance

Accuracy: 82% 

Architecture: Transfer Learning with MobileNetV2 (Pre-trained on ImageNet)

Classes: Glioma, Meningioma, Pituitary, No Tumor

## 🧠 Model Architecture Used Transfer Learning to leverage the feature extraction capabilities of MobileNetV2.

Base: MobileNetV2 (Frozen weights)

Head: Custom Dense layers with Dropout (0.2) to prevent overfitting.

Optimization: Adam Optimizer with categorical cross-entropy loss.

## 🛠️ Tech Stack

Python

TensorFlow / Keras

OpenCV

NumPy & Matplotlib

## 🚀 How to Run

Clone the repository.

Install dependencies: pip install -r requirements.txt

Open mri_tumor_detection.ipynb in Jupyter or Google Colab.
