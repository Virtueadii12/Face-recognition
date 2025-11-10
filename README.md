# Face-recognition
This project detects and recognizes faces in real time using your system’s webcam. It uses OpenCV for video capture and image processing, and face_recognition (built on deep learning models) for identifying known faces.

🎥 Real-Time Face Recognition using Python & OpenCV

🧠 Project Overview

This project performs real-time face detection and recognition using a webcam feed.
It uses OpenCV for live video capture and image processing, and face_recognition for identifying known faces based on deep learning encodings.
The system detects faces in a video stream and matches them against stored images, displaying the person’s name on the screen.

⚙️ How It Works

Loads known faces from the images/ folder.
Encodes each face into a 128-dimensional feature vector.
Captures live video using the webcam.
Compares each detected face in the video to the known encodings.
Displays a bounding box and name label around recognized faces.

🧩 Tech Stack

Python 3.x
OpenCV → Video streaming and image handling
face_recognition → Deep learning–based face detection and encoding
NumPy → Mathematical operations on arrays

📂 Folder Structure

Face_Recognition_Project/
│
├── images/                   # Known faces (e.g. Aditya.jpg)
├── face_recognition_app.py    # Main Python script
├── requirements.txt           # Dependencies
└── README.md                  # Project documentation

🧾 Installation Guide
1️⃣ Clone the Repository
git clone https://github.com/<your-username>/Face_Recognition_Project.git
cd Face_Recognition_Project
2️⃣ Install Required Libraries
pip install -r requirements.txt
If face_recognition gives an error on Windows, install CMake and Visual Studio Build Tools.
3️⃣ Run the Project
python face_recognition_app.py
Press ‘q’ (or ‘a’) to close the webcam window.

🧰 Requirements
opencv-python
face_recognition
numpy
You can directly install them using:
pip install opencv-python face_recognition numpy

📸 Output Example
✅ Opens webcam feed in real-time
✅ Detects faces and draws bounding boxes
✅ Recognizes and displays known names
✅ “Unknown” label for unrecognized faces

🚀 Features
Real-time face detection & recognition
Multiple known faces supported
Easily add new faces by placing their photos in the images/ folder
Extendable for attendance marking or security monitoring

🧠 Key Concepts
Face Encoding: Converts facial features into 128D vectors.
Face Comparison: Calculates Euclidean distance between encodings.
Real-Time Processing: Continuously analyzes webcam frames via OpenCV.

💼 Use Cases
Smart Attendance Systems
Door Lock Authentication
AI Security Cameras
Face-based Access Control

👤 Author
Aditya Singh
🎓 B.Tech CSE (AI & ML) | RIT Roorkee
📧 adityaasas@gmail.com
🔗 LinkedIn
🌟 GitHub Tags
#Python #OpenCV #FaceRecognition #AI #ComputerVision #MachineLearning
