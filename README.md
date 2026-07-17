# 👁️ Face and Eye Detection using OpenCV & Flask

## 📖 Project Overview

This project is a **real-time Face and Eye Detection Web Application** developed using **Python**, **Flask**, and **OpenCV**. It captures live video from a webcam, detects human faces and eyes using **Haar Cascade Classifiers**, and displays the processed video stream in a web browser.

The main objective of this project is to demonstrate how **Computer Vision** techniques can be integrated into a **Flask web application** to perform real-time object detection.

---

## ✨ Features

- 🎥 Real-time webcam video streaming
- 😊 Face detection using Haar Cascade Classifier
- 👁️ Eye detection within detected faces
- 🖥️ Live video displayed through a Flask web interface
- ⚡ Fast and lightweight implementation
- 🧩 Easy-to-understand project structure

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **Python** | Programming Language |
| **Flask** | Web Framework |
| **OpenCV** | Computer Vision & Image Processing |
| **Haar Cascade Classifiers** | Face and Eye Detection |
| **HTML** | User Interface |

---

## 📂 Project Structure

```text
face-eye-detection-flask/
│── Haarcascades/
│   ├── haarcascade_frontalface_default.xml
│   ├── haarcascade_eye.xml
│
│── templates/
│   ├── index.html
│   └── result.html
│
│── app.py
│── requirements.txt
│── README.md
```

---

## ⚙️ How It Works

1. The application accesses the system's webcam using **OpenCV**.
2. Each captured frame is converted into a grayscale image to improve detection performance.
3. The **Haar Cascade Face Classifier** scans the frame and detects human faces.
4. For every detected face, a **Region of Interest (ROI)** is created.
5. The **Eye Cascade Classifier** detects eyes within the face region.
6. Bounding boxes are drawn around the detected faces and eyes.
7. Flask continuously streams the processed frames to the web browser, providing a real-time detection experience.

---

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/mohini198/face-eye-detection-flask.git
```

### 2. Navigate to the Project Folder

```bash
cd face-eye-detection-flask
```

### 3. Install Required Packages

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Start the Flask server by running:

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000/
```

---

## 📸 Expected Output

- The webcam opens automatically.
- Faces are detected and highlighted with green rectangles.
- Eyes inside the detected faces are also highlighted.
- The processed video stream is displayed on the web page in real time.

---

## 🎯 Learning Outcomes

This project helped in understanding:

- Flask web development
- OpenCV image processing
- Haar Cascade classifiers
- Real-time video streaming
- Face and eye detection techniques
- Integration of Computer Vision with web applications

---

## 🔮 Future Enhancements

- Face Recognition using Deep Learning
- Smile Detection
- Blink Detection
- Emotion Recognition
- Face Mask Detection
- Image Upload Support
- Video File Detection
- Attendance Management System Integration

---

## 👩‍💻 Author

**Mohini Chauhan**  
B.Tech – Computer Science Engineering (AI & ML)

---

## 📄 License

This project is developed for educational and learning purposes. Feel free to use and modify it for academic or personal projects.
