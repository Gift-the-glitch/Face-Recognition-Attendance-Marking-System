# Face-Recognition-Attendance-Marking-System
Face Recognition System  A Python-based face recognition app using OpenCV and face_recognition to identify faces in images and real-time video. It logs recognized faces with timestamps, useful for attendance tracking. Features a simple tkinter GUI for image uploads, live recognition, and result display.

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
