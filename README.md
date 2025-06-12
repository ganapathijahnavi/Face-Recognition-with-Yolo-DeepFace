# Human Detection and Face Recognition Using YOLOv8 and DeepFace
    # Requirements to install 
    !pip install ultralytics deepface matplotlib opencv-python-headless numpy
Face recognition is a task of identifying or verifying a person's identity by analyzing and comparing facial features from images or videos.This project combines the power of "YOLOv8" for human detection and "DeepFace" for facial recognition to identify individuals in an image. It detects people using YOLO and then recognizes faces by comparing them with a database of known individuals using DeepFace.

## 🚀 Features
-  Human detection using YOLOv8 ('ultralytics')
-   Face recognition using DeepFace (ArcFace, VGG-Face, etc.)
-   Face database support
-   Draws bounding boxes with names and accuracy
-   Supports multiple people in one image
-   Outputs annotated image with recognition results

 ## 🚀 Workflow
1. Load Input Image - An image containing one or more people is loaded.
2. Person Detection with YOLOv8 - Uses the YOLO model to detect human bounding boxes (class 0).
3. Face Extraction with DeepFace - Extracts faces from each person box using RetinaFace or other detectors.
4. Face Recognition - Compares the extracted face with a database of known faces.
5. Labeling - Each person is labeled with name and recognition accuracy, or marked as "Unknown".
6. Display Results - Annotated image is displayed with names and bounding boxes.

## 🚀 Tech Stack
Tool/Library                    Purpose                        
Python                        Programming language          
OpenCV                        Image processing               
YOLOv8 (Ultralytics)          Object detection             
DeepFace                      Face detection and recognition 
Matplotlib                    Image visualization            
NumPy                         Array and numerical operations 

## 🚀 Applications:
Attendance systems in schools or offices.
Security surveillance and intruder detection.
Smart photo organization based on identity.
Personalized marketing or retail surveillance.

## 📍More about YOLOv8 and DeepFace:

YOLOv8 -- YOLOv8 (You Only Look Once, version 8) is the latest and most advanced version of the YOLO (real-time object detection) family developed by Ultralytics. It is PyTorch-based Which can easy to train and fine-tune. It's a powerful, fast, and highly accurate model for tasks like:
1.Object Detection
2.Instance Segmentation
3.Image Classification
4.Pose Estimation
5.Tracking (video streams)

DeepFace -- DeepFace is an open-source Python library for face recognition, face verification, and facial attribute analysis (like age, gender, emotion, race). It includes  Face Recognition, Face Verification, Facial Attributes, Multiple Models, Face Detectors as its features. It supports models like VGG-Face, Facenet, ArcFace, DeepFace, SFace, Dlib. It Uses detectors like OpenCV, RetinaFace, MTCNN, SSD, and more.

🙋‍♀️Author-->
Jahnavi Durga Ganapathi, 
Feel free to connect or contribute!
