# Speech Emotion Recognition (SER) App using CNN
A web application for recognizing emotions from speech using a TensorFlow Lite model, designed for microcontrollers like the Arduino Nano BLE33. The app is trained on the RAVDESS dataset and can identify seven different emotions.
# Features
* Audio Upload: Upload .wav files for emotion recognition.
* Real-time Recording: Record and analyze audio in real-time.
* Feature Extraction: Extracts features such as Zero Crossing Rate (ZCR), Root Mean Square Energy (RMSE), and Mel-Frequency Cepstral Coefficients (MFCCs).
* Data Augmentation: Enhances feature extraction using noise addition and pitch shifting.
* Emotion Prediction: Standardizes features and uses a pre-trained TensorFlow model to predict emotions.
# Recognized Emotions
* Angry😡
* Disgust😖
* Fear😱
* Happy😊
* Neutral😐
* Sad😥
* Surprise😮
# How to Use
* Upload an Audio File: Click the "Upload file for Speech Emotion Recognition" button and select a .wav file.
* Record Audio: Click the "Start Recording for Emotion Prediction" button to record a new audio sample.
* View Results: The predicted emotion will be displayed after analysis.
# Installation
* 1.Clone the repository:
```
function test() {
  console.log("This code will have a copy button to the right of it");
}
```

git clone https://github.com/ompathak23/SER-App.git
cd SER-App
* 2.Install the required dependencies:
##
pip install -r requirements.txt
Run the application:

streamlit run app.py
