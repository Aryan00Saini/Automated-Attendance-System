👤 Automated Attendance System
A touchless, AI-powered solution for tracking attendance in real-time using Facial Recognition. This system replaces manual logging by identifying individuals via a webcam and recording their presence automatically.

🚀 Key Features
Real-Time Identification: Instantly detects and recognizes faces from a live video stream.

Automatic Logging: Records attendance with precise timestamps directly into CSV files.

Deep Learning Accuracy: Leverages high-precision models to minimize errors and prevent "proxy" attendance.

Optimized Performance: Uses cached facial encodings to ensure fast recognition without high CPU load.

🛠️ Getting Started
Prerequisites
Python 3.8 or higher

A functional webcam

C++ Compiler (required for the dlib library)

1. Clone the repository
Bash
git clone https://github.com/Aryan00Saini/Automated-Attendance-System.git
2. Navigate to the project folder
Bash
cd Automated-Attendance-System
3. Install required libraries
Bash
pip install opencv-python face_recognition numpy pandas
🚦 How to Run
To start the attendance tracking system, execute the primary script:

Bash
python main.py
📂 Project Structure
Plaintext
├── Training_Images/       # Database of student photos for recognition
├── Attendance_Logs/       # Automatically generated CSV attendance sheets
├── main.py                # Primary script to run the recognition system
├── encodings.pickle       # Cached facial data for fast processing
└── README.md              # Project documentation and setup guide
