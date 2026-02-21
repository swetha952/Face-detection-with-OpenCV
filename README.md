# Face Detection using OpenCV

## 📌 Project Description

This project performs **real-time face detection** using your webcam.
It uses **OpenCV** and a pre-trained **Haar Cascade Classifier** to detect human faces and draw rectangles around them.

---

## 🚀 Features

* Detects faces in real-time
* Draws green rectangles around detected faces
* Displays number of faces detected in terminal
* Press `ESC` to exit

---

## 🛠️ Technologies Used

* Python
* OpenCV (`cv2`)
* Haar Cascade XML Classifier

---

## 📂 Project Structure

```
Face-Detection/
│
├── face_detection.py
├── haarcascade_frontalface_default.xml
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Install Python (if not installed)

Download from: [https://www.python.org/](https://www.python.org/)

### 2️⃣ Install OpenCV

Open terminal in VS Code and run:

```bash
python -m pip install opencv-python
```

### 3️⃣ Download Haar Cascade File

Download:
`haarcascade_frontalface_default.xml`

You can get it from the official OpenCV GitHub repository.

Place it in the same folder as your Python file.

---

## ▶️ How to Run

```bash
python face_detection.py
```

Your webcam will open and start detecting faces.

Press `ESC` key to close the window.

---

## 🧠 How It Works

1. Loads Haar Cascade classifier.
2. Captures video from webcam.
3. Converts frame to grayscale.
4. Detects faces using `detectMultiScale()`.
5. Draws rectangles around faces.
6. Displays face count in terminal.

---

## 📸 Output

* A window showing webcam feed
* Green rectangles around detected faces
* Face count printed in terminal

---
