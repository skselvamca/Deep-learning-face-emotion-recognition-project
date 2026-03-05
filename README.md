# Real-Time Face Emotion Recognition using Deep Learning

## Project Overview
This project implements a deep learning-based system to recognize human emotions from facial expressions in real time. A Convolutional Neural Network (CNN) model is trained on facial images to classify emotions such as Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral.

The trained model is integrated with OpenCV to detect faces from a webcam and predict emotions in real time.

---

## Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Deep Learning (CNN)

---

## Project Workflow
1. Dataset preprocessing
2. Image normalization and resizing
3. CNN model training
4. Model evaluation
5. Real-time emotion detection using webcam

---

## Project Structure

Face-Emotion-Recognition
│
├── Dataset
├── preprocess.ipynb
├── train.ipynb
├── detect_emotion.ipynb
├── emotion_model.h5
├── requirements.txt
└── README.md

---

## Installation

Clone the repository:

git clone https://github.com/yourusername/Face-Emotion-Recognition.git

Navigate to the project folder:

cd Face-Emotion-Recognition

Install required libraries:

pip install -r requirements.txt

---

## How to Run

Step 1 – Preprocess Dataset  
Run preprocess.ipynb

Step 2 – Train Model  
Run train.ipynb  
This will generate emotion_model.h5

Step 3 – Real-Time Emotion Detection  
Run detect_emotion.ipynb  
The webcam will open and detect facial emotions.

---

## Emotions Detected
- Angry
- Disgust
- Fear
- Happy
- Sad
- Surprise
- Neutral

---

## Applications
- Human Computer Interaction
- Mental Health Monitoring
- Smart Surveillance
- Emotion-based AI systems

---

## Author
Selvakumar
