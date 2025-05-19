# AI-Based-Smart-Attendance-System


An AI-powered smart attendance system that uses facial recognition to automatically detect and mark attendance from a live webcam feed. This lightweight solution eliminates the need for manual attendance and enhances accuracy in classroom or lab environments.

---

## Project Overview

This project implements a face recognition-based attendance system using pre-trained deep learning models. The system captures live webcam input, identifies registered individuals, and logs attendance with timestamps.

Key features include:

- Real-time face recognition using webcam  
- Automatic attendance logging to a CSV file  
- Uses pre-saved reference images of students/staff  
- Lightweight, no internet dependency, fast inference  

---

## Methodology

- Collection of face images for known individuals  
- Encoding of known faces using FaceNet or face_recognition (based on dlib)  
- Live video stream processing with OpenCV  
- Matching detected faces with known encodings  
- Attendance marking with date and time in CSV format  

---

## Technologies Used

- Python, OpenCV  
- face_recognition (dlib-based face encoding)  
- NumPy, Pandas  
- Webcam for input  

---

## Results

- High accuracy in face recognition under normal lighting  
- Quick response time suitable for classroom deployment  
- Attendance data securely stored in CSV format  

---

## Future Work

- Integrate with audio verification for dual-mode authentication  
- Build a GUI for easier usability and visualization  
- Store attendance data in cloud or database systems  
- Add spoof detection for increased security  

---

## Contact

Aleena Roy  
Email: aleenapallippadavil@gmail.com  
LinkedIn: [linkedin.com/in/aleena-roy-113b40230](https://www.linkedin.com/in/aleena-roy-113b40230)
