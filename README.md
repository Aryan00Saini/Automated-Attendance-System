# 👤 Automated Attendance System

An AI-powered, touchless attendance management system that uses **Facial Recognition** to mark attendance automatically in real time. The system eliminates manual logging by identifying individuals through a webcam and securely recording their attendance with timestamps.

---

## 🚀 Key Features

- **Real-Time Face Recognition**  
  Detects and recognizes faces instantly from a live video feed.

- **Automated Attendance Logging**  
  Marks attendance automatically and stores records with accurate timestamps in CSV files.

- **High Accuracy with Deep Learning**  
  Uses pre-trained facial recognition models to reduce false matches and prevent proxy attendance.

- **Optimized Performance**  
  Caches facial encodings to ensure fast execution with low CPU overhead.

---

## 🛠️ Getting Started

### Prerequisites

- Python 3.8 or higher  
- A working webcam  
- C++ Compiler (required for `dlib`)  

---

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Aryan00Saini/Automated-Attendance-System.git
```

2️⃣ Navigate to the Project Directory
```bash
cd Automated-Attendance-System
```

3️⃣ Install Required Dependencies
```bash
pip install opencv-python face_recognition numpy pandas
```

---


🚦 How to Run
Start the attendance system by running:
```bash
python main.py
```

---


📂 Project Structure
```plaintext
Automated-Attendance-System/
├── Training_Images/        # Stored images used for face recognition
├── Attendance_Logs/        # Generated CSV files containing attendance records
├── main.py                 # Main script to run the system
├── encodings.pickle        # Cached facial encodings for faster recognition
└── README.md               # Project documentation
```

---

## 📌 Notes

- Ensure clear and well-lit face images are placed in the `Training_Images` folder for accurate recognition.
- Attendance logs are generated automatically for each session and saved as CSV files.
- The system is suitable for classrooms, offices, and other controlled environments.
