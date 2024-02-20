Hand Pose Estimation with MediaPipe (Python)
This repository contains a sample program that estimates hand pose using MediaPipe in Python. The program recognizes hand signs and finger gestures with a simple MLP (Multi-Layer Perceptron) using the detected key points.

Contents

Hand Sign Recognition Model (TFLite)
Learning Data and Notebook
Requirements
Usage
Additional Information

The sample program in this repository utilizes the power of MediaPipe for hand pose estimation. It is designed to recognize hand signs and finger gestures, leveraging a simple MLP.

Hand Sign Recognition Model (TFLite)
Included in this repository is a pre-trained hand sign recognition model in TensorFlow Lite (TFLite) format. This model is ready to be used for hand pose estimation.

Learning Data and Notebook
Learning data for hand sign recognition is provided.
A notebook is available for training and learning using the provided data.
Requirements
Ensure you have the following dependencies installed:

mediapipe 0.10.9
OpenCV 3.4.2 or Later
Tensorflow 2.3.0 or Later
tf-nightly 2.5.0.dev or later (Only when creating a TFLite for an LSTM model)
scikit-learn 0.23.2 or Later (Only if you want to display the confusion matrix)
matplotlib 3.3.2 or Later (Only if you want to display the confusion matrix)
Usage
Clone the repository:
git clone 