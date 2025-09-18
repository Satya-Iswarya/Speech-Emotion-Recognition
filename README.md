# Speech Emotion Recognition using MLPClassifier (TESS Dataset)
# Project Overview
This Jupyter Notebook details the process of building a Speech Emotion Recognition (SER) system. We will leverage the TESS (Toronto Emotional Speech Set) dataset to train a Multi-Layer Perceptron (MLP) Classifier to identify various emotions from spoken audio.

# Objective
The primary objective of this project is to accurately classify human emotions from speech signals, demonstrating fundamental skills in audio processing, feature engineering, and supervised machine learning.

# Key Technologies Used
Python: The primary programming language.

Jupyter Notebook: For interactive development and documentation.

Librosa: For audio loading and advanced feature extraction (MFCCs, Chroma, Mel Spectrogram, etc.).

Scikit-learn: For machine learning model (MLPClassifier), data splitting, and evaluation metrics.

NumPy & Pandas: For efficient data manipulation.

Matplotlib & Seaborn: For data visualization and presenting results.

# Dataset
We will be using the TESS (Toronto Emotional Speech Set) dataset.

# Download Link: 
TESS Dataset on Kaggle (You'll need a Kaggle account to download, which is free).
# Dataset Structure: 
After downloading TESS_Toronto_emotional_speech_set_data.zip and unzipping, you'll find folders for each emotion (e.g., OAF_fear, YAF_sad). The file names encode the speaker (OAF/YAF) and the emotion.
Unzip Location: Place the unzipped TESS_Toronto_emotional_speech_set_data (or rename it to just TESS for simplicity) folder in the same directory as this notebook.
# TESS File Naming Convention
Each filename directly contains the emotion label. Example: OAF_base_sad.wav
OAF: Speaker code (Older Adult Female)
base: Base word
sad: Emotion (e.g., angry, disgust, fearful, happy, ps (pleasant surprise), sad, neutral)fearful
07 = disgust
08 = surprised
