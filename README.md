
# Face Recognition Attendance System using ESP32-CAM

This project is a real-time face recognition–based attendance system built using Python and ESP32-CAM.It automates the process of recording attendance by capturing live images via the ESP32-CAM and identifying registered individuals using facial recognition techniques. It prevents proxy attendance in classrooms or offices.

##  Project Overview

-  Capture frames via ESP32-CAM over Wi-Fi
-  Recognize faces using the `face_recognition` Python library
-  Automatically mark attendance in a `.csv` file
-  Image folder stores reference face images

##  Requirements

### Hardware
- ESP32-CAM (AI-Thinker)
- Micro USB cable
- MICRO-SD Card (Upto 4GB)
- External 5V power supply (recommended)

### Software
- Arduino IDE
- Python 3.10 or higher
- Python libraries:
  ```bash
  pip install opencv-python face_recognition pandas numpy
  
### Setup Instructions
- Arduino IDE
- Python `3.10.11` or lower
- Upload the `CameraWebServer` sketch to your ESP32-CAM.
- Note the IP address shown in the Serial Monitor (e.g., http://192.168.xx).
- Update your Python script with the correct `camera_url`.
- Place reference face images in the `image_folder`.


