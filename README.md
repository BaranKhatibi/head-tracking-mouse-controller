# Head Tracking Mouse Controller

A real-time computer vision project that lets you move the mouse cursor using head movement.

This project uses your laptop webcam and OpenCV’s Haar cascade face detector to track your face, then translates that movement into cursor control with PyAutoGUI. An offset zone is used so small movements don’t affect the cursor, making the control more stable.

It’s a simple hands-free interaction experiment that shows how basic face tracking can be used for human-computer interaction.

## Tech Used

- Python
- OpenCV
- NumPy
- PyAutoGUI

## Project structure

main.py
requirements.txt
haarcascade_frontalface_default.xml
README.md
