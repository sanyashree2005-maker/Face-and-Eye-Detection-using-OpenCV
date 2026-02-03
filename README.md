👁️ Face & Eye Detection using OpenCV

 Project Overview

This project implements real-time face and eye detection using classical computer vision techniques.
It was developed as part of a Computer Vision coursework to understand object detection using Haar Cascade classifiers and image preprocessing pipelines.

The system detects human faces from images/video streams and further identifies eye regions within detected faces.

🎯 Objectives

* To understand the fundamentals of object detection in computer vision
* To implement face detection using Haar Cascades
* To perform eye detection within facial regions
* To explore the role of image preprocessing (grayscale conversion, scaling, ROI selection)
* To build a real-time detection pipeline using OpenCV

📝 Project Description

The project uses Haar Cascade Classifiers, a machine learning–based approach where a cascade function is trained using positive and negative image samples.

 Workflow:

1. Image Acquisition

   * Input image or live video feed via webcam

2. Preprocessing

   * Conversion of images from RGB to grayscale
   * Noise reduction for better detection accuracy

3. Face Detection

   * Haar Cascade face classifier scans the image at multiple scales
   * Bounding boxes are drawn around detected faces

4. Eye Detection

   * Eye detection is performed only inside the detected face region
   * This reduces false positives and improves efficiency

5. Visualization

   * Rectangles drawn around faces and eyes in real-time

🛠️ Technologies Used

* Python
* OpenCV
* NumPy
* Jupyter Notebook

 📊 Results

* Successfully detects human faces in real-time
* Accurately detects eyes within facial regions
* Works efficiently under good lighting conditions
  
 ⚠️ Limitations

* Performance decreases in low-light conditions
* Haar Cascades may struggle with extreme head poses
* Less robust compared to deep learning–based detectors (CNNs)

🚀 Future Improvements

* Replace Haar Cascades with CNN-based detectors (e.g., MTCNN, YOLO)
* Improve robustness under varying lighting conditions
* Extend detection to facial landmarks and expressions


