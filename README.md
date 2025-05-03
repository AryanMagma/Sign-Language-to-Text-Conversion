# 🧠 Sign-Language-to-Text Conversion using Deep Learning

## 📌 Overview
Sign language is a vital means of communication for the deaf and hard-of-hearing community. This project builds a deep learning model that translates American Sign Language (ASL) finger-spelling gestures into readable text. Using Convolutional Neural Networks (CNNs) and hand landmark detection with MediaPipe, the system detects static ASL signs from images or video frames and converts them to both text and speech.

## 🎯 Motivation
Communication barriers between hearing and non-hearing individuals often require human translators, which are not always accessible. This project explores the use of deep learning and computer vision to create an automated, real-time, and scalable solution for ASL interpretation.

## 🎯 Objectives
- Collect and preprocess a dataset of ASL alphabet signs.
- Detect hand landmarks using **MediaPipe**.
- Train a **CNN** model for static ASL sign classification.
- Convert recognized signs into **text** and **speech**.
- Optimize the system for real-time performance and high accuracy.

## 🔁 Project Workflow

### 1. Data Collection & Preprocessing
- Collected ASL alphabet images (A–Z) from open datasets.
- Resized, normalized, and augmented the data for model training.

### 2. Hand Landmark Detection
- Used **MediaPipe** to extract 21 hand landmarks.
- Converted landmarks into structured feature vectors.

### 3. Model Building
- Built and trained a **CNN** using **TensorFlow/Keras**.
- Validated the model using classification metrics.

### 4. Integration & Conversion
- Connected the trained model with real-time webcam input.
- Displayed detected letter as **text**.
- Used **pyttsx3** to convert recognized text into **speech**.

### 5. Evaluation
- Achieved **95%+ accuracy** on the validation set.
- Real-time predictions with latency <1s per frame.

## 🛠️ Tech Stack

- **Languages:** Python  
- **Libraries/Frameworks:**  
  - TensorFlow, Keras, OpenCV  
  - MediaPipe  
  - NumPy, Pandas, Matplotlib  
  - pyttsx3 (text-to-speech)  
- **Tools:**  
  - Jupyter Notebook  
  - Google Colab  
  - Visual Studio Code  

## 👤 Author
**Aryan Singh**

## 🙏 Credits
- [ASL Alphabet Dataset (Kaggle / Open Source)](https://www.kaggle.com/datasets/grassknoted/asl-alphabet)
- [MediaPipe by Google](https://mediapipe.dev/)
- [TensorFlow](https://www.tensorflow.org/)
- Python community for open-source tools and documentation

