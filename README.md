

# 🎯 Face Recognition–Based Attendance System (Python & OpenCV)

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![Python 3.9](https://img.shields.io/badge/python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/)

A **Face Recognition–based Attendance Management System** built using **Python and OpenCV**.
This project automatically records attendance by recognizing faces through a webcam and stores attendance data subject-wise in CSV format.

---

## 🚀 Features

* Face registration with **ID and Name**
* Automatic face detection using webcam
* Model training using captured images
* Real-time face recognition
* Subject-wise attendance management
* Attendance stored in **CSV files**
* Tabular attendance view
* Simple and user-friendly GUI

---

## 🛠️ Technologies Used

* Python 3.9
* OpenCV
* NumPy
* Pandas
* Tkinter
* Haar Cascade Classifier

---

## 📁 Project Structure

```
Attendance-Management-System/
│
├── TrainingImage/          # Stores captured face images
├── TrainingImageLabel/     # Trained model files
├── Attendance/             # Subject-wise CSV attendance
│
├── attendance.py           # Main UI & control file
├── automaticAttendance.py # Face recognition logic
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation & Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/Attendance-Management-system-using-face-recognition.git
cd Attendance-Management-system-using-face-recognition
```

### Step 2: Install Required Packages

```bash
pip install -r requirements.txt
```

### Step 3: Create Required Folder

Create a folder named **TrainingImage** inside the project directory.

### Step 4: Configure Paths

Open the following files and update paths according to your system:

* `attendance.py`
* `automaticAttendance.py`

### Step 5: Run the Project

```bash
python attendance.py
```

---

## 🔄 Project Workflow

1. **Register New Student**

   * Enter Student ID and Name
   * Click **Take Image**
   * System captures up to **50 face images** (configurable)

2. **Train Images**

   * Converts face images into numeric data
   * Trains the recognition model
   * More images → better accuracy

3. **Automatic Attendance**

   * Enter subject name
   * System detects face in real time
   * Attendance is marked automatically

4. **Attendance Storage**

   * Separate `.csv` file for each subject
   * Date and time included

5. **View Attendance**

   * Display attendance in a **tabular format**

---

## 🖼️ Screenshots

### 🔹 Simple UI

![Image](https://user-images.githubusercontent.com/37211676/58502148-97ec2a00-81a3-11e9-963e-674b9c3e05dc.png)

![Image](https://user-images.githubusercontent.com/37211676/58502149-97ec2a00-81a3-11e9-9658-8968da396c2e.png)

### 🔹 Capturing Face Images

![Image](https://media.geeksforgeeks.org/wp-content/uploads/20250501131504627869/FACE-DETECTION.webp)

![Image](https://cdn.hashnode.com/res/hashnode/image/upload/v1621060838206/4Gvr_5QHM.png)

### 🔹 Automatic Attendance

![Image](https://www.lystloc.com/blog/wp-content/uploads/2023/12/blog-%E2%80%93-462-1.webp)

![Image](https://www.lystloc.com/blog/wp-content/uploads/2022/11/ezgif.com-gif-maker-6.webp)

### 🔹 Attendance in Tabular Format

![Image](https://i.sstatic.net/nmTNr.png)

![Image](https://www.datacourses.com/wp-content/uploads/2019/08/Screen-Shot-2019-08-21-at-3.54.29-PM-1024x448.png)

---

## 📌 Notes

* Ensure proper lighting while capturing images
* Webcam must be connected
* Same face should not be registered with multiple IDs

---

## 🌟 Future Improvements

* Cloud database integration
* Admin & user login system
* Mobile app support
* Masked face recognition
* Accuracy optimization using deep learning

---

## ❤️ Support

If you find this project useful:

* ⭐ Star the repository
* 🍴 Fork it
* 🛠️ Contribute to make it better

**Happy Coding! 🚀**
