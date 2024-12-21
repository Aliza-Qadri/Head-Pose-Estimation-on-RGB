# **Head Pose Estimation and Facial Expression Detection**

## **Project Overview**

This project processes input data in the form of videos and images to perform advanced analysis on human faces. It comprises two primary functionalities:

1. **Head Pose Estimation:**
   - The input (video or image) is split into individual frames.
   - Faces are detected in each frame.
   - Facial landmarks are identified on the detected faces.
   - Values of **yaw**, **pitch**, and **roll** are computed based on the landmarks.
   - Using these values, the **head pose** is accurately estimated.

2. **Facial Expression Detection:**
   - In the second part of the code, the project identifies and categorizes **facial expressions** from the input images.

## **Key Features**
- Accepts videos or images as input.
- Utilizes facial landmark detection to compute orientation and pose.
- Provides real-time or batch processing for head pose estimation.
- Detects various facial expressions in the second phase of the analysis.

## **Technologies Used**
- Python
- OpenCV
- MediaPipe
- NumPy

## **Usage**
1. Upload a video or image file as input.
2. Run the program to process the input and extract frames.
3. View the computed **yaw, pitch, and roll** values for each detected face to understand the head pose.
4. Check for detected **facial expressions** in the second part of the output.

## **Code File Access**
I have uploaded the code files to Google Drive. You can access them through the following link:
https://colab.research.google.com/drive/1w1RNVaJ0MdRXJ98WW-OhsRSJmxzIGyEd?usp=sharing


Feel free to download or explore the code!



---

Let me know if you'd like any further adjustments!
