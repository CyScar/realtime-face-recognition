# Real-Time Face Recognition Code for Google Colab with Custom Data Generation using Webcam

This repository provides a complete guide and code implementation for real-time face recognition using Google Colab and webcam, including custom data generation, model training, live video stream setup, real-time testing, and saving predicted frames as images.

## Introduction
Face recognition is a popular application of computer vision and deep learning. This project aims to provide an easy-to-follow implementation of real-time face recognition using a custom dataset generated from a webcam. The code is designed to run smoothly on Google Colab, allowing users to leverage its free GPU resources.

## Getting Started
Clone this repository to your Google Colab workspace.
Open the notebook Face_detection_and_recognition.ipynb to get started.

## Data Collection
Follow the instructions in the notebook to create a custom face dataset.
Use the webcam to capture face images for different individuals, and store them in separate folders within the dataset directory.

<img width="965" alt="Screenshot 2023-07-24 at 5 35 35 PM" src="https://github.com/CyScar/realtime-face-recognition/assets/58580745/c15e0085-ac98-4c0b-a03b-a3edc0dcf3f4">

<img width="217" alt="Screenshot 2023-07-24 at 5 37 07 PM" src="https://github.com/CyScar/realtime-face-recognition/assets/58580745/64a1e725-9f77-4e73-bd52-844dc3d9cf58">

## Model Training 
Train the face recognition model on the custom dataset as instructed in the notebook.

## Live Video Stream Setup
Set up a live video stream from your webcam directly into the Colab notebook using the code provided in the notebook.
Ensure that the webcam is accessible to the Colab runtime.

## Real-Time Testing
Perform real-time face recognition on the live video stream as explained in the notebook.
The predicted frames will be displayed with recognized faces highlighted in a green box whereas the unrecognized faces will be highlighted in a red box.

## Saving Predicted Frames
The notebook includes code to save each predicted frame containing recognized faces as images.
The images will be saved in the Output directory.

## Conclusion
Congratulations! You have successfully implemented a real-time face recognition system using Google Colab, custom data generation, and a webcam. Feel free to explore further optimizations and enhancements to adapt the project to your specific use cases.


