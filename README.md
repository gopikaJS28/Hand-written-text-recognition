Handwritten IAM Text Recognition

This project focuses on recognizing handwritten text using the IAM dataset. The implementation is based on deep learning models utilizing TensorFlow and Keras.

📌 Features

Preprocessing of IAM dataset for text recognition
Model training using CNNs and RNNs for sequence learning
CTC (Connectionist Temporal Classification) loss for sequence alignment
Evaluation metrics for performance assessment

Dataset

The IAM dataset consists of handwritten English text samples. You can download it from IAM Dataset Website.

📈 Model Architecture

The model consists of:

CNN layers for feature extraction
Bidirectional LSTM for sequence modeling
CTC loss for aligning predictions with ground truth

📜 Results

The model is evaluated using CER (Character Error Rate) and WER (Word Error Rate). Performance improves with additional training and data augmentation.
