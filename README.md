# 📸 Automated Attendance System

A real-time facial recognition application built with **Python** that automates attendance logging. The system detects faces via a webcam, compares them against a database of known individuals, and logs the name and timestamp of recognized persons into a CSV file.

## 🚀 Features
* **Real-time Detection:** Uses a live camera feed to identify individuals instantly.
* **Automated Logging:** Saves attendance with precise timestamps in `Attendance.csv`.
* **High Accuracy:** Utilizes the `face_recognition` library's deep learning models for high verification accuracy.
* **Duplicate Prevention:** The system checks the CSV and only logs a person once per session.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** * `OpenCV`: For image processing and webcam integration.
    * `face_recognition`: For face encoding and distance comparison.
    * `NumPy`: For optimized array operations.
    * `OS & Datetime`: For file handling and time tracking.

## 📂 Project Structure
```plaintext
├── faces/               # Folder containing reference images (e.g., Aryan.jpg)
├── Attendance.py        # Main application script
├── Attendance.csv       # Log file (generated automatically)
└── README.md            # Project documentation

