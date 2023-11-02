# REAL TIME FACIAL EMOTION RECOGNIZER
Real-time facial emotion recognition is a technology that uses computer vision and deep learning to analyze a person's facial expressions in real-time and determine their emotional state. 
## Overview
The Real-Time Facial Emotion Recognition System is a Python-based project that utilizes computer vision and deep learning techniques to perform real-time emotion detection from live video streams captured by a camera source. A CNN model is trained to recognize a range of 7 emotions, including 'Angry', 'Disgust', 'Fear', 'Happy', 'Neutral', 'Sad', and 'Surprise'. 
## Workflow
1. It all starts with training a CNN model.
2. The dataset used to train and test the model is [DATASET](https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset "DATASET").
3. You can downlaod the dataset or directly use the dataset in [KAGGLE](https://kaggle.com) if you want to perform any changes in `real-time-facial-emotion-classification-cnn-using-keras.ipynb` file. 
4. The trained model generated will be in .h5 format. Here the emotion detection model is `model.h5` file.
5. The system employs the Haar Cascade Classifier, loaded from the `haarcascade_frontalface_default.xml` file, to detect faces in the video frames.
6. The code continuously captures video frames from the camera source, making real-time processing possible.
7. The detected faces are passed through the emotion detection model to classify the emotion, and the corresponding emotion label is overlaid on the video frame.

## Prerequisites
* Python
* TensorFlow
* Keras
* OpenCV
* Pandas
* Numpy
* Seaborn
* Matplotlib
## Usage
1. You can start by cloning the project repository to your local system or by downloading the zip file and extracting it in your working folder.
2. Ensure you have the pre-trained emotion detection model (model.h5) and the Haar Cascade Classifier XML file (haarcascade_frontalface_default.xml) placed in the project directory. These models are essential for the system to function.
3. Execute the Python script `main.py` to start the real-time facial emotion recognition system. 
