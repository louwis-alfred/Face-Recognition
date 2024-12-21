# Face Recognition and Video Recording

This project demonstrates a simple face and body detection system using Python and OpenCV. It detects faces and bodies in real-time using a webcam and starts recording video when a face or body is detected. The recording stops automatically after no detection is observed for a few seconds.

## Features

- **Real-Time Face and Body Detection**: Utilizes Haar cascades from OpenCV to detect faces and bodies in video frames.
- **Automated Video Recording**: Starts recording when a face or body is detected and stops recording after a specified duration of no detection.
- **User-Friendly Output**: Saves recorded videos with timestamps for easy reference.
- **Customizable Settings**: Adjustable detection and recording parameters.

## Prerequisites

Before running this project, ensure you have the following installed:

- Python 3.x
- OpenCV (`cv2`) library

You can install OpenCV using pip:

```bash
pip install opencv-python
