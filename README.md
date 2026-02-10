Automated Attendance System
A real-time facial recognition application built with Python that automates attendance logging. The system detects faces via a webcam, compares them against a database of known individuals, and logs the name and timestamp of recognized persons into a CSV file.

🚀 Features
Real-time Detection: Uses a live camera feed to identify individuals instantly.

Automated Logging: Saves attendance with precise timestamps in Attendance.csv.

Accuracy: Utilizes the face_recognition library's deep learning models for high verification accuracy.

Duplicate Prevention: The system checks the CSV and only logs a person once per session.

🛠️ Tech Stack
Language: Python

Libraries: * OpenCV: For image processing and webcam integration.

face_recognition: For face encoding and distance comparison.

NumPy: For optimized array operations.

OS & Datetime: For file handling and time tracking.


Gemini said
To help you stand out for that Amazon SDE internship, a professional README should explain the "how" and "why" behind your code. Since your code uses OpenCV and Face Recognition libraries to log attendance into a CSV, here is a structured layout you can copy and paste into your README.md file.

Automated Attendance System
A real-time facial recognition application built with Python that automates attendance logging. The system detects faces via a webcam, compares them against a database of known individuals, and logs the name and timestamp of recognized persons into a CSV file.

🚀 Features
Real-time Detection: Uses a live camera feed to identify individuals instantly.

Automated Logging: Saves attendance with precise timestamps in Attendance.csv.

Accuracy: Utilizes the face_recognition library's deep learning models for high verification accuracy.

Duplicate Prevention: The system checks the CSV and only logs a person once per session.

🛠️ Tech Stack
Language: Python

Libraries: * OpenCV: For image processing and webcam integration.

face_recognition: For face encoding and distance comparison.

NumPy: For optimized array operations.

OS & Datetime: For file handling and time tracking.

📂 Project Structure

Plaintext
├── faces/               # Folder containing reference images (e.g., Aryan.jpg)
├── Attendance.py        # Main application script
├── Attendance.csv       # Log file (generated automatically)
└── README.md            # Project documentation

⚙️ Installation & Setup
Clone the repository:

Bash
git clone https://github.com/Aryan00Saini/Automated-Attendance-System.git
Install dependencies:

Bash
pip install opencv-python numpy face-recognition
Prepare the database:

Place clear images of people in the faces/ folder.

Name the files according to the person (e.g., Aryan_Saini.jpg).

Run the application:

Bash
python Attendance.py
📝 How It Works
Encoding: On startup, the system scans the faces/ folder and generates a 128-dimension encoding for each image.

Recognition: It captures frames from the webcam and compares live face encodings against the known database using Euclidean distance.

Verification: If a match is found (lowest distance), the system marks the person as "Present" and writes their name to the CSV if they aren't already listed.

🛡️ Future Improvements
SQL Integration: Moving from CSV to a database like MySQL/PostgreSQL for better scalability.

Web Dashboard: A React.js frontend to visualize attendance records.

Anti-Spoofing: Implementing liveness detection to prevent photos from being used to trick the system.
