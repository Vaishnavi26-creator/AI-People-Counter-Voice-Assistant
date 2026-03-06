# AI People Counter with Voice Assistance

## 📌 Project Description

This project is a **real-time AI-based people detection and counting system** that uses a laptop camera to detect humans and announce the number of people detected using voice output.

The system uses the **YOLOv8 deep learning model** for object detection and provides **audio feedback** such as:

* "1 person detected"
* "2 people detected"
* "3 people detected"

This project demonstrates the integration of **Computer Vision, Deep Learning, and Text-to-Speech technology**.

---

# 🎯 Features

* Real-time object detection using **YOLOv8**
* Detects **only humans**
* **Counts number of people** in the camera frame
* **Voice announcement** when number of people changes
* Displays **live camera feed with bounding boxes**
* Displays **people count on screen**

---

# 🛠 Technologies Used

| Technology           | Purpose                         |
| -------------------- | ------------------------------- |
| Python               | Programming language            |
| OpenCV               | Camera input & image processing |
| YOLOv8 (Ultralytics) | Object detection model          |
| PyTorch              | Deep learning backend           |
| pyttsx3              | Text-to-speech system           |

---

# 📂 Project Structure

```
Live_Object_Explorer
│
├── object_detection_live.py
├── camera_test.py
├── README.md
```

---

# ⚙️ Installation

### 1️⃣ Install Python

Install **Python 3.11+**

---

### 2️⃣ Install Required Libraries

Run these commands in terminal:

```
pip install opencv-python
pip install ultralytics
pip install pyttsx3
```

---

# ▶️ Running the Project

Run the following command:

```
python object_detection_live.py
```

---

# 🎥 How It Works

1️⃣ Webcam captures live video
2️⃣ Each frame is processed using YOLOv8
3️⃣ System detects **people in the frame**
4️⃣ Number of detected people is counted
5️⃣ Voice assistant announces the count

Example:

```
"2 people detected"
```

---

# 🧠 Key Concepts Used

* Real-time computer vision
* Deep learning inference
* Object detection using YOLOv8
* Bounding box visualization
* Text-to-speech integration

---

# 🚀 Future Improvements

* Distance estimation for detected people
* Direction guidance (left/right)
* Mobile camera support
* Custom object training
* Obstacle detection for visually impaired users

---

# 👩‍💻 Author

**Vaishnavi Chalke**
B.Tech Computer Science Student
