# Face Recognition System

This project is a Python-based face recognition system that uses a pre-trained model to recognize faces in both uploaded images and live webcam feeds. It also logs attendance with timestamps for each recognized face in a CSV file.

## Features
- **Upload Image Recognition**: Upload an image to recognize known faces.
- **Live Webcam Recognition**: Start a live video feed to recognize faces in real-time.
- **Attendance Logging**: Logs the names and timestamps of recognized faces into `attendance_list.csv`.

## Installation
To get started, clone this repository and install the dependencies listed below.

### Prerequisites
1. **Python 3.x**
2. **Libraries**:
   ```bash
   pip install face_recognition numpy opencv-python pillow
Note: face_recognition depends on dlib, which may require additional installation steps on some systems.

####Update Paths:

Place your known face images in a folder and update the file paths in load_known_faces() function in main.py.

Interacting with the Application:

Upload Image: Upload an image file (.jpg or .png) to recognize faces.
Live Recognition: Open live webcam recognition to recognize faces in real-time.
Exit: Close the application by pressing the "Exit" button or 'q' in the live recognition window.

