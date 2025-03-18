# Pedestrian-Detection

This Python script detects pedestrians in video feeds using two methods:

HOG Descriptor: Green bounding boxes (default pedestrian detector).

Haar Cascade: Blue bounding boxes (haarcascade_fullbody.xml required).

Key Features:
Works with video files/webcam input (press 0 to switch to webcam live feed).

Real-time processing with frame resizing for efficiency.

Usage:
Install dependencies: pip install opencv-python imutils

Download haarcascade_fullbody.xml and update the file path in the script.

Run the code. Press q to exit or 0 for webcam mode.

👉 Tip: Adjust video_source variable to your video file path.
