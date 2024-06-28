# Facial-Emotion-Detection

* This project is about Emotion Detection using VGG-16. OpenCV is also used to implement real-time emotion detection using the trained model. It can detect the following emotions: angry, happy, sad, surprise, fear, disgust, neutral.

* Tensorflow libraries are used to implement model training using the device's GPU rather than the CPU. This significantly decreases the training time. The IDE used is JupyterLab.

# Dataset used

* Dataset: https://www.kaggle.com/ashishpatel26/facial-expression-recognitionferchallenge  

The data set is FER2013 which is an open-source data set that was made publicly available for a Kaggle competition. 
It consists of 48 X 48-pixel grayscale images of human faces. 
There are seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral) present in the dataset.


# Face-emotion-recognition.ipynb

* This is the Jupyter Notebook file used in Dataset Cleaning,Model Training/Testing and importing the finished model.

# model.h5 and model.json

* These two are the imported model(model.json) and model weights(model.h5)

# face_emotion_recognition.py

* This is the python format of the Jupyter notebook code

# real-time-detection.py

* This is the python script that is responsible for loading the trained model and implementing a real-time emotion detection with the use of OpenCV.
* The face will be recognized and a bounding box will be displayed around the face, signifying the current emotion of the user in real-time.