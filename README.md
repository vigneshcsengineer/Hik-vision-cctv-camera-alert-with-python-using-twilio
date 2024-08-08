# RTSP Camera Motion Detection with Twilio Alerts

This project is a Python script that monitors an RTSP stream from a camera for motion detection. When motion is detected, it sends an SMS alert using the Twilio API. The script processes the video stream in real-time using OpenCV and detects motion by comparing the current frame with the previous one.

## About

This script is designed to monitor a live RTSP video stream from a camera and detect any motion. Upon detecting motion, it sends an SMS notification to a specified phone number using Twilio. This setup is ideal for security systems where real-time alerts are crucial. The script captures video frames, processes them to identify motion, and alerts the user by drawing a bounding box around the detected motion and sending an SMS.

## Features

- RTSP Stream Monitoring: Connects to an RTSP camera stream for real-time video feed.
- Motion Detection: Uses frame differencing to detect motion.
- SMS Alerts: Sends an SMS alert via Twilio when motion is detected.
- Real-time Video Display: Shows the video feed and motion detection status in real-time.

## Installation

1.Clone the repository:
   ```bash
   git clone https://github.com/vigneshcsengineer/Hik-vision-cctv-camera-alert-with-python-using-twilio.git
   cd Hik-vision-cctv-camera-alert-with-python-using-twilio
2.Install Required libraries
   pip install opencv-python twilio
3.Configure Twilio credientials
4.Run the script
   python motion_detection.py

