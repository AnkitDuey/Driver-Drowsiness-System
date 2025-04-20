# Driver Drowsiness Detection System

This project is a **real-time Driver Drowsiness Detection System** using computer vision techniques. It leverages **dlib**, **OpenCV**, and **Python** to monitor the driver's eye aspect ratio (EAR) and triggers an alarm if signs of drowsiness are detected.

## Features
- Real-time video stream analysis using webcam
- Eye Aspect Ratio (EAR) calculation to detect blinking and prolonged eye closure
- Alarm sound triggered when drowsiness is detected
- Visual display of eye contours and EAR value on video frame

## Requirements

- Python 3.x
- dlib
- OpenCV
- scipy
- imutils
- pygame

Install dependencies using pip:

```bash
pip install opencv-python dlib scipy imutils pygame
```

##  How to Run

1. Clone this repository or download the files.
2. Ensure you have the following files in your directory:
   - `Drowsiness_detection.py`
   - `shape_predictor_68_face_landmarks.dat` (download from [dlib model](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2))
   - `loud_alarm.wav` (or any .wav file for alarm sound)
3. Run the script:

```bash
python Drowsiness_detection.py --shape-predictor shape_predictor_68_face_landmarks.dat --alarm loud_alarm.wav
```

> Press `q` to quit the program.

##  Output

- A window displaying webcam feed with drawn eye contours
- Display of EAR value
- "Drowsiness Alert!" message with an alarm sound if EAR drops below threshold

##  GitHub Repository

[Visit the Project Repository](https://github.com/AnkitDuey/Driver-Drowsiness-System)

---
**Developed by:** Nikhil Jivraj Arethiya, Ankit Anil Dubey, Rohan Vasant Dhatrak, Aryan Anil Itkepelliwar