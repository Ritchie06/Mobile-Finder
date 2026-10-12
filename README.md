# 📱 PhoneFinder — Real-Time Phone Detection System

A computer vision project that detects mobile phones in images and live camera feeds using TensorFlow and EfficientDet D1, with a simple interactive web interface.

## ✨ Features

- 📷 **Live Camera Detection** — Detect phones in real time using your camera.
- 🖼️ **Image Upload** — Upload an image and analyze it for mobile phones.
- 🎯 **Confidence Threshold** — Adjust the minimum detection confidence.
- 📊 **Detection Statistics** — View detected objects, confidence scores, and processing time.
- 🔍 **Bounding Boxes** — Visualize detected phones directly on the image.
- 🎨 **Interactive UI** — Clean interface with detection status and activity logs.

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Backend | Python, Flask, Flask-CORS |
| AI Model | TensorFlow, EfficientDet D1 |
| Image Processing | OpenCV, NumPy |
| Deployment / Tunneling | Google Colab, ngrok |

## ⚙️ How It Works

1. The user starts the live camera or uploads an image.
2. The frontend sends the image or camera frame to the Flask backend.
3. EfficientDet D1 analyzes the input and identifies objects.
4. Confidence filtering and Non-Maximum Suppression (NMS) help refine detections.
5. The results are returned with bounding boxes, labels, and confidence scores.
6. The interface displays the detection results and statistics.

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Google Colab with GPU runtime recommended
- A modern web browser with camera access
- An ngrok account and authentication token

### Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/Ritchie06/PhoneFinder.git
   cd PhoneFinder
   ```

2. Start the backend notebook in Google Colab with GPU enabled.

3. Configure your ngrok authentication token securely using Colab Secrets or environment variables.

4. Run the backend and copy the generated public API URL.

5. Update the `API` constant in the frontend JavaScript with the active backend URL.

6. Open the frontend through a local web server or suitable web hosting service.

7. Allow camera access or upload an image to start detecting phones.

## 📂 Project Structure

```text
PhoneFinder/
├── index.html          # Frontend interface
├── backend.ipynb       # Backend notebook (if included)
└── README.md            # Project documentation
```

## 🎯 Learning Outcomes

- Applied deep learning to an object detection task.
- Integrated a TensorFlow model with a Flask REST API.
- Connected a web interface to a Python backend.
- Explored image preprocessing, confidence thresholds, and NMS.
- Built an interactive interface for visualizing detection results.

## 🔮 Future Improvements

- Improve detection performance under different lighting conditions.
- Deploy the backend to a persistent hosting platform.
- Add support for video file uploads.
- Evaluate model accuracy using a labeled test dataset.

## 👩‍💻 Author

**Ritchie Tanya**  
AI & Data Science Graduate | AI & Machine Learning Enthusiast

- GitHub: Ritchie06(https://github.com/Ritchie06)

---

*Built to turn computer vision concepts into a practical, interactive application.* 🚀
