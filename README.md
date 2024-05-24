Overview
This project demonstrates a simple image recognition system using OpenCV, leveraging a pre-trained deep learning model. The primary objective is to detect and classify objects in an input image. We use the MobileNet SSD (Single Shot Detector) model, a popular choice for real-time object detection due to its efficiency and accuracy.

Objectives
Object Detection: Identify and locate objects within an image.
Object Classification: Classify detected objects into predefined categories.
Visualization: Display the image with bounding boxes around detected objects, along with labels and confidence scores.

Components
OpenCV: An open-source computer vision and machine learning software library that provides tools for image processing, computer vision, and machine learning.
MobileNet SSD Model: A pre-trained deep learning model for object detection that balances accuracy and computational efficiency.

Steps
Setup Environment: Install necessary libraries and download model files.
Load Pre-trained Model: Use OpenCV's cv2.dnn module to load the MobileNet SSD model.
Process Input Image: Load and preprocess the input image for detection.
Perform Detection: Use the model to detect and classify objects in the image.
Display Results: Draw bounding boxes around detected objects and display the image.
