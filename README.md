# PRODIGY_ML_03
# 🐾 Cats vs Dogs Classification using SVM

This project implements a *Support Vector Machine (SVM)* to classify images of cats and dogs from the Kaggle dataset.  
The model extracts features from images (using resizing and HOG feature extraction), scales them, and trains an SVM classifier.  
Finally, predictions can be generated in the required Kaggle submission.csv format.

---

## 📂 Dataset

We use the *Dogs vs Cats dataset* from Kaggle:  

👉 [Download Dataset](https://www.kaggle.com/c/dogs-vs-cats/data)  

⚠ Note: You need a Kaggle account and must *accept the competition rules* before downloading.  

*Dataset structure after extraction:*
Hand Gesture Recognition using CNN (LeapGestRecog Dataset)
This project implements a hand gesture recognition system using deep learning (CNN with transfer learning).
It uses the LeapGestRecog dataset consisting of 200,000 images across 10 different gesture classes, collected using a Leap Motion Controller.

📂 Dataset
Dataset Name: LeapGestRecog
Classes (10 Gestures):
Palm
L
Fist
Fist Moved
Thumb
Index
OK
Palm Moved
C
Down
👉 Download here: LeapGestRecog Dataset on Kaggle

🚀 Features
Preprocessing pipeline with TensorFlow & Keras
CNN-based model with transfer learning (e.g., MobileNetV2 / EfficientNet)
Fine-tuning last layers for improved accuracy
Training, validation, and prediction support
Achieved ~35%+ accuracy after fine-tuning (can be improved with more epochs & augmentation)
📦 Requirements
Install dependencies:

pip install tensorflow keras opencv-python matplotlib numpy
