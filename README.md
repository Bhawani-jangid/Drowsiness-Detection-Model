Certainly! Here's a description for your GitHub repository file:

---

# Drowsiness and Age Detection System

This Python project implements a drowsiness and age detection system using a combination of OpenCV for face and eye detection, TensorFlow Keras models for predicting drowsiness and age, and a graphical user interface (GUI) built with Tkinter. The system can detect whether a person is drowsy or awake based on real-time video or images, and it can also estimate their age group.

### Features:
- **Drowsiness Detection**: Detects whether the person is drowsy or awake by analyzing the state of their eyes using a trained CNN model.
- **Age Detection**: Estimates the age group of the detected face using a separate age prediction model.
- **Real-time Detection**: Capable of processing frames from both live webcam feed and uploaded video files.
- **Alarm System**: Plays an alarm sound if drowsiness is detected.
- **Zoom Functionality**: Users can zoom in or out on the displayed image using the mouse scroll wheel.
- **GUI**: The application is equipped with an interactive GUI that allows users to upload images or videos, view real-time detection results, and adjust zoom levels.

### Dependencies:
- `OpenCV`: For face and eye detection.
- `TensorFlow Keras`: For loading and running pre-trained models for drowsiness and age detection.
- `Pygame`: For playing alarm sounds when drowsiness is detected.
- `Pillow`: For handling image conversions within Tkinter.
- `Tkinter`: For creating the GUI and handling user interactions.

### Files:
- **alarm.wav**: The alarm sound file that plays when drowsiness is detected.
- **haarcascade_frontalface_default.xml**: The pre-trained Haar Cascade model used for detecting faces.
- **haarcascade_eye.xml**: The pre-trained Haar Cascade model used for detecting eyes.
- **model.keras**: The trained Keras model for detecting drowsiness.
- **best_model.keras**: The trained Keras model for age group detection.

### How to Use:
1. Clone the repository to your local machine.
2. Install the required dependencies (`opencv`, `tensorflow`, `pygame`, `pillow`, `tkinter`).
3. Run the Python script to open the GUI.
4. Use the buttons in the GUI to upload images, use the webcam, or upload video files.
5. The system will display the detection results (Awake/Drowsy) and age group for each detected face in the input image or video.
6. Adjust the zoom level using the mouse scroll wheel to view details on the image or video.

---

### DATASET :
[Kaggle](https://www.kaggle.com/datasets/tauilabdelilah/mrl-eye-dataset), [MRL Eye Dataset](http://mrl.cs.vsb.cz/eyedataset)

Also check main and master for .keras file 
