# headcursor_virtualmouse
# HeadCursor – Head Controlled Mouse Using Computer Vision

HeadCursor is a Python-based computer vision project that allows users to control the system mouse cursor using **head movements** captured through a webcam.  
The project demonstrates **hands-free human–computer interaction** using facial landmark detection and real-time cursor mapping.

## Project Overview

This project uses a live camera feed to detect facial landmarks and track head movement.  
The detected motion is translated into cursor movement on the screen, enabling touch-free control without any external hardware.

## How It Works

1. Webcam captures live video feed  
2. MediaPipe Face Mesh detects facial landmarks  
3. Head movement is calculated using landmark positions  
4. Cursor position is updated in real time using PyAutoGUI  
5. Smoothing is applied for stable cursor movement  

## Technologies Used

- Python  
- OpenCV  
- MediaPipe (Face Mesh)  
- PyAutoGUI  
- NumPy  

## System Requirements

- Python 3.8 or above  
- Working webcam  
- Windows / Linux / macOS  

## Installation

Install the required dependencies using pip:
pip install opencv-python mediapipe pyautogui numpy

How to Run
Save the provided Python code file (for example: headcursor.py)
Open a terminal or command prompt in the project folder
Run the program:
python headcursor.py

Usage Instructions
Sit in front of the webcam with your face clearly visible
Keep your head centered for better accuracy
Move your head left or right to move the cursor horizontally
Move your head up or down to move the cursor vertically
Ensure good lighting conditions for optimal performance

