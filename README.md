# Hand-Gestures
Computer Vision project: Real-time Sign Language Recognition using MNIST dataset, Mediapipe, and Deep Learning.

This project is a deep learning–based application that focuses on the recognition of American Sign Language (ASL) gestures using computer vision and neural networks. Sign language is one of the most widely used forms of communication by people who are deaf or mute, but the lack of interpreters and communication tools often creates a barrier between them and the rest of society. The purpose of this project is to build a solution that can automatically recognize hand gestures corresponding to sign language alphabets and convert them into readable text, making communication easier and more accessible.

The application uses the MNIST Sign Language dataset and a Convolutional Neural Network (CNN) model trained on the dataset to recognize alphabets A–Z (excluding J and Z, which require motion). For real-time recognition, the system integrates OpenCV and MediaPipe for live hand detection and tracking through a webcam feed. Once the hand region is detected, the trained deep learning model predicts the alphabet being signed, providing accurate and efficient gesture recognition.

To ensure usability and accessibility, two different user interfaces have been developed. The first interface is a Streamlit web application that runs directly in the browser. This makes it lightweight, easy to use, and suitable for deployment on cloud platforms where users can access it via a public URL without installing additional software. The second interface is a Tkinter desktop application, which provides an offline solution for users who want to run the project locally on their system without internet access. Both interfaces are designed to be simple, clean, and user-friendly, ensuring that even non-technical users can interact with the system without difficulty.

In addition to the software implementation, a PowerPoint presentation (PPT) is included with the project. The presentation covers the motivation behind the project, the real-world problem being solved, the methodology used, system architecture, user interface designs, results, and future scope. This makes it easier to present the project in academic or professional settings.

Project provides two user interfaces:

Streamlit App → Web-based interface (runs on browser)
Tkinter App → Desktop-based interface (Python GUI)

🚀 Features

✅ Real-time hand gesture recognition using MediaPipe & OpenCV

✅ Prediction of alphabets A–Z using trained CNN model

✅ Streamlit interface for browser-based deployment

✅ Tkinter desktop app for offline usage

✅ Clean UI with easy-to-use navigation

✅ Includes presentation slides for project explanation

Tech Stack

Python

TensorFlow / Keras (Deep Learning Model)

OpenCV (Image Processing)

MediaPipe (Hand Tracking)

Streamlit (Web UI)

Tkinter (Desktop UI)
