# Enhacing-fracture-detection-in-medical-imaging-using-LBP-and-YOLO

This project presents an automated bone fracture detection system using YOLOv8 integrated with Local Binary Patterns (LBP) for enhanced feature extraction from X-ray images.
The system is designed to detect and classify multiple fracture types from radiographic images with improved accuracy and generalization.

🚀 Project Overview:

Traditional fracture detection from X-rays can be time-consuming and prone to human error. This project leverages deep learning and texture-based feature extraction to assist in accurate fracture identification.
We trained a YOLOv8 object detection model on a multi-class bone fracture dataset (~10 classes) and enhanced performance using LBP preprocessing, which improves texture visibility and subtle fracture pattern recognition.

🔍 Key Features:

YOLOv8-based fracture detection
LBP preprocessing for improved texture analysis
Multi-class fracture classification
Handles rare fracture classes effectively
Improved performance in low-contrast/noisy X-ray images
Reduced overfitting through dataset balancing and augmentation

🛠️ Technologies Used:

Python
YOLOv8 (Ultralytics)
OpenCV
Local Binary Patterns (LBP)
Google Colab
Roboflow Dataset

📂 Dataset

A labeled bone fracture X-ray dataset from Roboflow Universe was used and further balanced to improve performance on underrepresented fracture classes.
