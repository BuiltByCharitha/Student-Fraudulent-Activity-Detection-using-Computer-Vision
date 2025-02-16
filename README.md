# Cellphone and Book Detection in Video Feed

This project involves real-time video analysis for detecting cellphones and books using a standard laptop camera. It combines face recognition with object detection and provides warnings if certain objects are detected in the video feed.

### Features:
- **Face Detection:** Detects faces using dlib's 68-point face model.
- **Cellphone Detection:** Detects cellphones in the video feed using MobileNet SSD.
- **Book Detection:** Detects books in the video feed using MobileNet SSD.
- **Warning Alerts:** Displays warning alerts when multiple faces, cellphones, or books are detected.

### Requirements:
- Python 3.x
- OpenCV
- dlib
- NumPy

### Installation:
1. Install the required libraries:
   ```bash
   pip install opencv-python opencv-python-headless dlib numpy

### Acknowledgements:
Special thanks to [MostafaHassan1/J6_Hackathon_Nadara](https://github.com/MostafaHassan1/J6_Hackathon_Nadara) for providing the reference code for the object detection part. The inspiration from their work was used to implement the object detection model in this project.
