# Face-Recognition-Attendace-
# Face Recognition-Based Attendance System  

## Overview  
This project is a Python-based application that automates attendance marking using face recognition technology. Built with OpenCV for image processing and Tkinter for a graphical user interface (GUI), the system is designed to be user-friendly, secure, and efficient for classrooms, offices, or other environments requiring attendance tracking.

---

## Features  
1. *User Registration*: Capture and store facial images of users for training.  
2. *Face Recognition*: Identify registered users and mark attendance in real-time.  
3. *Attendance Logging*: Store attendance records with details such as ID, name, date, and time in a CSV file.  
4. *Password Protection*: Secure sensitive operations like training and attendance logs.  
5. *Graphical User Interface (GUI)*: Intuitive interface for user interactions using Tkinter.

---

## Technologies Used  
- *Programming Language*: Python  
- *Libraries*:  
  - OpenCV (Face Detection and Recognition)  
  - Tkinter (Graphical User Interface)  
  - Pandas (Data Handling)  
- *File Formats*:  
  - CSV (Attendance Logs and User Data)  

---

## Folder Structure  
```plaintext
FaceRecognitionAttendanceSystem/
├── TrainingImage/                # Directory to store captured images during registration
├── TrainingImageLabel/           # Directory for storing the trained model
├── Attendance/                   # Directory for attendance log CSV files
├── Code/
│   ├── main.py                   # Main script to run the application
│   ├── helpers.py                # Helper functions for processing
│   ├── training.py               # Script to train the face recognition model
│   ├── attendance.py             # Script to track and log attendance
├── README.md                     # Project documentation
