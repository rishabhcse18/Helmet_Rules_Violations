Monitoring Traffic Rule Violations at Traffic Squares Using Computer Vision
This project is a computer vision-based system designed to detect and report traffic rule violations at intersections, focusing on ensuring helmet compliance and traffic safety. The system leverages advanced object detection and classification techniques for real-time monitoring.

Features
Helmet Detection: Identifies motorcyclists without helmets using a custom CNN.
Object Detection: Detects vehicles, pedestrians, and motorcyclists using YOLOv8.
Real-Time Analysis: Processes images for immediate violation detection.
Scalable Framework: Designed for diverse urban traffic conditions.
Methodology
Dataset Collection:

Images from Kaggle and Roboflow, with diverse lighting and traffic conditions.
~3800 images split into training, validation, and test sets.
Preprocessing:

Noise reduction, normalization, and data augmentation techniques (e.g., flipping, rotation, cropping).
Model Training:

YOLOv8 for object detection.
Custom CNN for binary classification (helmet/no helmet).
Evaluation Metrics:

Accuracy, Precision, Recall, and F1 Score.
Technologies Used
Python
TensorFlow / PyTorch
YOLOv8
OpenCV
NVIDIA GPU for model training
Results
Training Accuracy: 93.39%
Validation Accuracy: 79.50% (under real-world conditions)

Challenges
Occlusions and overlapping objects in dense traffic.
Low visibility in foggy and nighttime conditions.
Limited dataset diversity affecting real-world generalization.
Future Work
Expand dataset to include more diverse traffic scenarios.
Incorporate temporal context to address occlusions.
Optimize models for deployment on edge devices.
