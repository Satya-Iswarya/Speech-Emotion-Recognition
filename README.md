# 🎙️ Speech Emotion Recognition using LSTM-RNN

## 📌 Project Overview
This project focuses on recognizing human emotions from speech using the **RAVDESS dataset**.  
The model leverages **Long Short-Term Memory (LSTM-RNN)** architecture to capture temporal audio features, enabling accurate classification of emotions such as happiness, anger, sadness, and fear.  
It aims to enhance **human–computer interaction** by enabling machines to understand the emotional context of human speech.

---

## 🚀 Features
- Emotion detection from audio signals  
- LSTM-RNN–based deep learning model  
- Streamlit web interface for easy testing and deployment  
- Visualization of training accuracy and loss  
- Supports multiple emotions from the RAVDESS dataset  

---

## 🧠 Model Performance
- **Dataset:** RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)  
- **Model Accuracy:** ~65% on test data  
- **Emotions Classified:** Happy, Angry, Sad, Fear, Neutral, and others  

## RAVDESS File Naming Convention
Each filename provides information about the audio: `Modality-VocalChannel-Emotion-Intensity-Statement-Repetition-Actor.wav`
Example: `03-01-01-01-01-01-01.wav`
* `03`: Audio-only
* `01`: Speech
* `01`: **Emotion** (we'll primarily use this)
* `01`: Emotional intensity (01=normal, 02=strong)
* `01`: Statement (01="Kids are talking by the door", 02="Dogs are sitting by the door")
* `01`: Repetition (01=1st, 02=2nd)
* `01`: Actor (01-24. Odd numbers are male, even are female)

**Emotion Codes:**
 01 = neutral, 02 = calm, 03 = happy, 04 = sad, 05 = angry, 06 = fearful, 07 = disgust, 08 = surprised
---

## 🧩 Tech Stack
- **Programming Language:** Python  
- **Libraries & Frameworks:** TensorFlow/Keras, Librosa, NumPy, Pandas, Matplotlib  
- **Frontend:** Streamlit  
- **Development Environment:** VS Code / Google Colab  

---
