# Speech Emotion Recognition (SER) App using CNN
A web application for recognizing emotions from speech using a TensorFlow Lite model, designed for microcontrollers like the Arduino Nano BLE33. The app is trained on the RAVDESS dataset and can identify seven different emotions.
# Features
* Audio Upload: Upload .wav files for emotion recognition.
* Real-time Recording: Record and analyze audio in real-time.
* Feature Extraction: Extracts features such as Zero Crossing Rate (ZCR), Root Mean Square Energy (RMSE), and Mel-Frequency Cepstral Coefficients (MFCCs).
* Data Augmentation: Enhances feature extraction using noise addition and pitch shifting.
* Emotion Prediction: Standardizes features and uses a pre-trained TensorFlow model to predict emotions.
# Recognized Emotions
* Angry
