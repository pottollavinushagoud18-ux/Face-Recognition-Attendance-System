# 📘 Face Recognition Based Attendance System

Automated Attendance Tracking using Computer Vision

### **Team Members**

* **Vinusha Goud Pottolla** (Roll ID: 00941796)
* **Veerendra Nadh Matsa** (Roll ID: 00946012)
* **Lakshmidhar Yadlapalli** (Roll ID: 00964282)

**Course:** DSCI-6612-02
**Professor:** *Vahid Behzadan*

---

## 🔍 Problem Statement

Traditional attendance systems face several issues:

* Manual process is slow and error-prone
* Proxy attendance is common
* Difficult to manage stored paper records
* Wastes 5–10 minutes of class time
* No digital backup or automated reporting

---

## 💡 Proposed Solution

This project presents a **Face Recognition-based Attendance System**, designed to automate the process using computer vision.

**Key Benefits:**

✔ Real-time face detection & recognition
✔ Attendance marked in 2–3 seconds
✔ Prevents proxy attendance
✔ Saves attendance in CSV/Excel
✔ High accuracy and time-saving system

---

## 🧰 Technology Stack

### **Languages & Libraries**

* Python 3.8
* OpenCV
* `face_recognition`
* NumPy
* Pandas
* Pillow
* Tkinter (GUI)

### **Algorithms Used**

* Haar Cascade — Face Detection
* LBPH — Face Recognition

---

## 🌟 Features

### ✔ Student Registration

* Capture **200 images per student**
* Automatically stores and organizes dataset

### ✔ Model Training

* Uses LBPH algorithm
* Generates trained model file (`training.yml`)

### ✔ Real-Time Recognition

* Detects and identifies faces via webcam
* Displays ID and name on screen

### ✔ Auto Attendance

* Logs ID, Name, Date, and Time
* Saves data into CSV file automatically

### ✔ Attendance Reports

* Generates Excel/CSV reports
* Easy view and download option

---

## 🖥️ GUI Overview

The GUI (Tkinter) includes:

| Button                   | Description                        |
| ------------------------ | ---------------------------------- |
| **Take Images**          | Capture 200 images of a student    |
| **Train Images**         | Train model using captured images  |
| **Automatic Attendance** | Live recognition + auto attendance |
| **View Attendance**      | Opens attendance files             |

---

## 🧑‍🎓 Registration Workflow

1. Open the application
2. Enter **Student Name** and **Student ID**
3. Click **Take Images**
4. System captures the required dataset
5. Click **Train Images**
6. Student added successfully

⏳ Takes about **2–3 minutes** per student

---

## ⏱️ Attendance Workflow

1. Click **Automatic Attendance**
2. System opens the camera
3. Detects and recognizes face
4. Attendance automatically logged and saved

⏱️ Recognition time: **~2–3 seconds per student**

---

## 📊 Evaluation & Results

| Metric                           | Value          |
| -------------------------------- | -------------- |
| **Recognition Accuracy**         | 92%            |
| **Average Time per Recognition** | 2.5s           |
| **False Positive Rate**          | 5%             |
| **Improvement Over Manual**      | 80% faster     |
| **Testing Group Size**           | 20–30 students |

---

## 📁 Project Structure

```
├── dataset/
├── TrainingImage/
├── Attendance/
├── training.yml
├── haarcascade_frontalface_default.xml
├── main.py
├── train.py
├── take_images.py
└── requirements.txt
```

---

## 🚀 Conclusion

The Face Recognition Attendance System:

✔ Reduces manual workload
✔ Improves speed & accuracy
✔ Provides secure & digital attendance logs
✔ Offers a user-friendly GUI

### **Future Enhancements**

* Mobile app integration
* Multi-face recognition
* Cloud-based storage
* Attendance analytics dashboard

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-repo/FaceAttendanceSystem.git
cd FaceAttendanceSystem
```

### 2. Install required libraries

```bash
pip install -r requirements.txt
```

### 3. Run the application

```bash
python main.py
```

---

## 📜 License

Academic project for *DSCI-6612-02*.
