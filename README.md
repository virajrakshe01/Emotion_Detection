# Face_Emotion_Recognition_Machine_Learning
# Emotion Detection Project

This project aims to develop a real-time emotion detection system using machine learning algorithms. The system identifies the predominant emotion in each frame captured from the webcam.
## Overview
This project utilizes a pre-trained deep learning model to detect and classify facial emotions in real-time. The model is trained on the FER-2013 dataset and can recognize seven different emotions: angry, disgust, fear, happy, neutral, sad, and surprise.

## Installation
To set up the project on your local machine, follow these steps:

1. Clone the repository or download and unzip it:
2.  Create a virtual environment:
3.  Activate the virtual environment:
4.   Install the required packages:- pip install tensorflow opencv-python.
   
## Usage
To use the emotion detection model, follow these steps:

1. Ensure your webcam is connected and working.

   The system will open a window displaying the webcam feed with detected faces and their corresponding emotions.

4. Press 'q' to quit the application.

## Model Description
The model used in this project is a Convolutional Neural Network (CNN) trained on the FER-2013 dataset. The key components are:

- **Haar Cascade**: Used for face detection.
- **Pre-trained CNN**: Used for emotion classification.

The emotion labels are:
- 0: angry
- 1: disgust
- 2: fear
- 3: happy
- 4: neutral
- 5: sad
- 6: surprise

   
