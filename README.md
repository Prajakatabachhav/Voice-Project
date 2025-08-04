# Emotion Recognition from Audio Using Deep Learning
This project focuses on emotion recognition from audio files, leveraging a deep learning model built using TensorFlow and Keras. The process involves extracting advanced audio features such as MFCC, chroma, spectral contrast, and zero-crossing rate, followed by classification using a fully connected neural network.

# Key Steps:
Feature Extraction: The system extracts Mel-frequency cepstral coefficients (MFCC), chroma, spectral contrast, and zero-crossing rate from audio files to capture essential acoustic features.

# Preprocessing: Features are scaled and encoded, preparing the data for the model.

# Model Training: A fully connected neural network (FCNN) is trained on the extracted features to classify emotions from speech.

# Evaluation: The model is evaluated on a separate test dataset, achieving an accuracy of 80.66%.

# Results:
Test Accuracy: 80.66%

# Confusion Matrix: The model performs well across various emotion categories, with particularly high precision and recall for several emotions like 'IEO', 'TSI', and 'WSI'.

# Technologies Used:
Python

Librosa (for audio processing)

TensorFlow / Keras (for model building and training)

Scikit-learn (for data preprocessing and evaluation)

