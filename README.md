# Object-Detection-using-Yolo
This repository demonstrates the use of the YOLOv5 model for object detection on sample images using PyTorch and OpenCV in a Google Colab environment. The code leverages the pretrained YOLOv5x model for detecting and rendering objects in images.

Features:

    YOLOv5 Pretrained Model: Uses the yolov5x variant, known for its high accuracy.
    Image Visualization: Displays the input images and the corresponding detection results using OpenCV's cv2_imshow.
    Effortless Inference: Processes multiple images to showcase the model's object detection capabilities.

How It Works:

    Downloads the YOLOv5 model weights (yolov5s.pt).
    Loads the pretrained yolov5x model via PyTorch Hub.
    Reads images from the local directory (Image.jpg, Image 2.jpg, and Traffic Image.jpg).
    Performs object detection on each image and visualizes the results with bounding boxes and labels.

Requirements:

    Google Colab environment
    Python packages: torch, opencv-python, matplotlib
    Internet connection for downloading YOLOv5 model weights and dependencies.

Quick Start:

    Clone the repository or copy the code into a Colab notebook.
    Upload the images (Image.jpg, Image 2.jpg, Traffic Image.jpg) to the specified paths in Colab.
    Run the notebook to see the object detection results.

Output:

The notebook displays:

    Input images.
    Detected objects with bounding boxes and labels rendered on the images.

Acknowledgments:

This project utilizes the Ultralytics YOLOv5 library for state-of-the-art object detection.
