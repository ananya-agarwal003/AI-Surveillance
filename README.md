# AI-Surveillance System

Real-time face recognition system that detects unauthorized individuals 
from live video and sends instant alerts via Telegram and Email.

## Features
- Real-time face detection using HOG algorithm
- 128-D ResNet-34 face encodings for recognition
- MOG2 background subtraction — triggers only on motion
- Multi-channel alerts: Telegram Bot + Gmail SMTP
- Cooldown logic to prevent alert flooding

## Tech Stack
Python, OpenCV, dlib, face_recognition, Telegram Bot API, SMTP

## How to Run
pip install opencv-python dlib face_recognition
python main.py
