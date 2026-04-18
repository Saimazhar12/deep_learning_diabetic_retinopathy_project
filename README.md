# 🩺👁️ Diabetic Retinopathy Detection using Deep Learning

This project implements a deep learning-based image classification system to detect **Diabetic Retinopathy (DR)** from retinal images. The model assists in early diagnosis by classifying whether a patient has DR or not.

## 📌 Project Overview

The goal of this project is to build a **binary image classifier** that identifies Diabetic Retinopathy from eye (fundus) images. A deep learning model automatically learns important features from the images and makes predictions.

## 📂 Dataset

It is organized into three main folders:

### Training Set
- DR  
- No DR  

### Validation Set
- DR  
- No DR  

### Test Set
- DR  
- No DR  

## ⚙️ Features
- Deep learning-based classification  
- Automatic labeling using folder structure  
- Image preprocessing and normalization  
- Model training with validation  
- Prediction on new/unseen images  

## 🧠 Model & Training
- **Model Type:** CNN / Pretrained Model  
- **Optimizer:** Adam  
- **Loss Function:** Binary Crossentropy  
- **Output Range:** 0 (No DR) to 1 (DR)  
- **Batch Size:** 32  
- **Epochs:** 15  

## 📊 Results
The model outputs probabilities as follows:

- **0.0 – 0.4 → No DR**  
- **0.5 – 1.0 → DR**  

It performs well on unseen data and shows good generalization.

## 🛠️ Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- OpenCV  
- Matplotlib  

## 🚀 How to Run
1. Clone the repository  
2. Install dependencies (`pip install -r requirements.txt`)  
3. Open the notebook  
4. Train the model or load a saved model  
5. Run predictions on new images  

## 📌 Conclusion
This project demonstrates how deep learning can be used for **medical image analysis**, specifically for detecting diabetic retinopathy.

**Future improvements:**
- Use transfer learning with pretrained models (e.g., InceptionV3, ResNet50)  
- Train on larger datasets  
- Fine-tune model architecture for better accuracy
