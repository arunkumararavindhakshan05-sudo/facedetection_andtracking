# 👤 Real-Time Face Detection & Tracking using OpenCV

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

A real-time **face detection and tracking** system built with Python and OpenCV using the **Haar Cascade Classifier**. The system detects faces from a live webcam feed and tracks them continuously with bounding boxes.

---

## 📸 Demo

```
[Live Webcam Feed]
  → Each frame scanned using Haar Cascade
  → Detected face(s) highlighted with rectangle
  → Tracking updates in real-time as face moves
```

---

## ⚙️ How It Works

1. **Haar Cascade Classifier** — Uses OpenCV's pre-trained `haarcascade_frontalface_default.xml` model
2. **Grayscale Conversion** — Each frame is converted to grayscale for faster processing
3. **Multi-Scale Detection** — Scans the image at multiple scales to detect faces of different sizes
4. **Bounding Box** — Draws a rectangle around each detected face
5. **Real-Time Loop** — Continuously processes frames from the webcam

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python 3.x | Core programming language |
| OpenCV | Face detection using Haar Cascade |
| Haar Cascade XML | Pre-trained face detection model |

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/arunkumararavindhakshan05-sudo/facedetection_andtracking.git
cd facedetection_andtracking

# Install dependencies
pip install opencv-python
```

---

## ▶️ Usage

```bash
python face_detection.py
```

**Controls:**
- Press **`Q`** — Quit the camera feed

---

## 📁 Project Structure

```
facedetection_andtracking/
│
├── face_detection.py                    # Main script
├── haarcascade_frontalface_default.xml  # Pre-trained model
└── README.md
```

---

## 🔮 Future Improvements

- [ ] Add eye and smile detection
- [ ] Count number of faces detected
- [ ] Add confidence score display
- [ ] Save snapshots when a face is detected

---

## 👤 Author

**Arunkumar Aravindhakshan**
🔗 [LinkedIn](https://linkedin.com/in/arunkumar-aravindhakshan) | [GitHub](https://github.com/arunkumararavindhakshan05-sudo)
