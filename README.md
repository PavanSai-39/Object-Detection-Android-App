# Object_Detection-Android-App

## Description

This Android application is designed to perform live object detection using the YOLOv8 deep learning model. YOLOv8 is known for its real-time object detection capabilities, and this app brings that functionality to Android devices.

## Prerequisites
- Make sure you have Anaconda and Android Studio installed.
- Make sure you have cuda and cudnn installed. (so that you can do training, or you can use the google colab)
- Download your Custom Dataset (My Dataset - https://universe.roboflow.com/leo-ueno/people-detection-o4rdr)

## Getting Started

To use this repository for any custom YOLOv8 Object detection model, follow these steps:

- Train yolov8 model on custom dataset and export it in .tflite format. (train_custom_model.ipynb )
- Clone this repository to your local machine using git clone https://github.com/PavanSai-39/Object_Detection-Android-App.git
- Put your .tflite model and .txt labels file inside the assets folder
- Rename paths of your model and labels file in Constants.kt file
- Build and Run the app on Android Studio (Make sure Developer options and USB Debugging is enabled to run the app on Mobile Devices)
