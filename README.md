#🧠 NeuroVision: MRI Brain Tumor Classifier
An automated medical imaging diagnostic tool that detects and classifies brain tumors from MRI scans using Deep Learning and Computer Vision.

#🚀 Project Overview
This project implements a Convolutional Neural Network (CNN) using Transfer Learning (MobileNetV2) to classify MRI scans into four distinct categories. The model aims to assist in the early detection of brain tumors by automating the analysis of medical imagery.

#📊 Performance & Results
Model Architecture: MobileNetV2 (Pre-trained on ImageNet) with a custom classifier head.

Accuracy: ~82%+ (Model is fine-tuned for medical feature extraction)

Classes Detected:

glioma_tumor

meningioma_tumor

pituitary_tumor

no_tumor

#🛠️ Tech Stack
Core: Python, TensorFlow, Keras

Data Processing: NumPy, Pandas, OpenCV

Visualization: Matplotlib

#🧠 Model Logic
Data Augmentation: Applied random flips, rotations, and zooms to prevent overfitting and handle limited medical data.

Transfer Learning: Leveraged the MobileNetV2 backbone (frozen weights) to extract high-level features.

Classification Head: Added Global Average Pooling and Dropout layers to robustly classify the 4 tumor types.

#💻 How to Run
Open the mri_tumor_detection.ipynb file in Google Colab or Jupyter Notebook.

Run the Setup/Import cells at the top to install necessary libraries.

Execute the training block to reproduce the results, or load the saved model mri_tumor_detector.keras for immediate inference.
