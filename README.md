# 👤 Automated Attendance System using Facial Recognition

A touchless, AI-powered solution for tracking attendance in real-time. Built between October and December 2024 to eliminate manual logging and prevent proxy attendance.

---

## 🚀 Key Features
* **Real-Time Detection:** Identifies faces instantly via webcam stream.
* **Automated Logging:** Saves data with timestamps directly to CSV/Excel.
* **Accuracy:** Uses HOG and Deep Learning models for high-precision matching.
* **Efficiency:** Pre-computes facial encodings for faster identification.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Computer Vision:** OpenCV
* **ML Libraries:** Face_Recognition, Dlib, NumPy
* **Data Handling:** CSV / Pandas

---

## 🏗️ How it Works

1. **Input:** Captures video frames from the camera.
2. **Process:** Detects landmarks and converts them into a 128-dimensional vector.
3. **Compare:** Matches the vector against the database of registered students.
4. **Action:** Logs the name and time if a match is found.

---

## 💻 Installation & Setup

```bash
# Clone the repository
git clone [https://github.com/Aryan00Saini/Automated-Attendance-System.git](https://github.com/Aryan00Saini/Automated-Attendance-System.git)

# Navigate to the project folder
cd Automated-Attendance-System

# Install required libraries
pip install opencv-python face_recognition numpy
