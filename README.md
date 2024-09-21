# Speech Emotion Recognition using Deep Learning

## Project Overview

This project aims to develop a deep learning model to recognize emotions from speech audio recordings. The project uses Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) models to classify emotions such as happiness, sadness, anger, and fear from speech data. Additionally, the project explores an extension for scam detection through voice analysis.

### Key Features
- **Datasets**: RAVDESS, CREMA-D, TESS, and SAVEE, covering emotions like happiness, sadness, anger, fear, and neutral.
- **Data Augmentation**: Techniques such as noise injection, pitch shifting, and stretching were used to increase the variety of training data.
- **Modeling**: CNN and LSTM architectures were implemented, with CNN achieving the highest accuracy.

### Results
- **CNN Model Accuracy**: 96.15%
- **LSTM Model Accuracy**: 85.7%
- **Evaluation Metrics**: F1-score, Precision, Recall, and ROC & AUC curves were used to assess model performance.

### Tools & Frameworks
- **TensorFlow** and **Keras** were used for building the deep learning models.
- **MFCCs** and other audio features were extracted for feature representation.

## Conclusion
The CNN model demonstrated superior performance in recognizing emotions, achieving high accuracy and robust evaluation metrics. This project contributes to the field of Speech Emotion Recognition (SER) and has practical applications in areas such as virtual assistants and mental health monitoring.
