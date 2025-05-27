# Realtime Object Detection 🚗🚌📦

This project performs real-time object detection on video streams using **YOLO (You Only Look Once)** and **OpenCV** in Python. It identifies common objects such as cars, buses, people, and more with bounding boxes and labels.

## 🔍 Features

- Real-time detection on video feed or saved video (`.mp4`)
- Uses YOLOv3 or YOLOv4 model for high accuracy
- Labels objects like `Car`, `Bus`, `Person`, etc.
- Displays FPS (frames per second) on screen
- Detection labels are shown **outside** the bounding boxes

## 🧠 Technologies Used

- Python 3
- OpenCV
- YOLO (Darknet)
- NumPy

## 📁 Directory Structure

├── weights/ # YOLO pre-trained weights
├── cfg/ # YOLO config files
├── coco.names # Class labels
├── Mumbai Traffic.mp4 # Sample input video
├── Realtime Object Detection.ipynb # Main detection script
└── README.md # Project documentation

✅ TODO

 Add live webcam support
 Add object tracking (e.g., SORT or Deep SORT)
 Export detections to a CSV file

Feel free to ⭐ this repo if you find it useful!

---

Let me know if you'd like a `requirements.txt`, license file, or sample GIF/screenshot help.
