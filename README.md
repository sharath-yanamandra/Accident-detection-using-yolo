# Accident-detection-using-yolo
Here's a `README.md` file based on the content of both `accident_detection.py` and `accident.ipynb` files:

---

```markdown
# Accident Detection System

This project aims to detect road accidents using computer vision techniques. The system processes video footage to identify potential accidents, providing a foundation for real-time alerts and automated safety systems.

## 🧠 Project Overview

This project consists of:

- A Python script (`accident_detection.py`) for accident detection.
- A Jupyter notebook (`accident.ipynb`) for experimentation, visualization, and development.

The core objective is to detect sudden stops or crashes in vehicles captured in video frames using OpenCV and object tracking methods.

---

## 📁 Project Structure

```
├── accident_detection.py     # Python script for real-time accident detection from video
├── accident.ipynb            # Jupyter notebook version for development and debugging
├── README.md                 # Project overview and usage guide
```

---

## 🛠️ Features

- Vehicle detection using OpenCV and background subtraction.
- Bounding box tracking with centroid distance calculation.
- Sudden deceleration / stop detection heuristics.
- Visualization of detected accidents in video.
- Adjustable parameters for distance threshold and frame difference.

---

## ⚙️ Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/accident-detection.git
cd accident-detection
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

> Make sure you have Python 3.7+ and OpenCV installed.

---

## 🚀 Usage

### Run the Script

```bash
python accident_detection.py
```

Modify the path to the input video in `accident_detection.py` if needed.

### Run the Notebook

Open `accident.ipynb` using Jupyter:

```bash
jupyter notebook accident.ipynb
```

You can test detection on sample video clips and tweak parameters in real time.

---

## 🎛️ Parameters

Inside the script/notebook:

- `DISTANCE_THRESHOLD`: Minimum movement to consider as non-accident.
- `FRAME_DIFF_THRESHOLD`: Number of frames over which movement is monitored.

These can be tuned based on your video resolution and traffic scene complexity.

---

## 🧪 Example

Sample output of accident detection (bounding box + alert):

```
[ALERT] Accident detected at frame 1543
```

Detected vehicles are marked with red or green boxes depending on movement.

---

## 📌 Future Improvements

- Use deep learning models (e.g., YOLO, DeepSORT) for more robust tracking.
- Integrate audio or SMS alerts.
- Real-time deployment with video streams from IP cameras.
- Accident severity classification.

---

## 📄 License

MIT License. Feel free to use and modify the code.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, open an issue first to discuss your ideas.

---

## 📬 Contact

Developed by Sharath.  
For queries, reach out via GitHub or email.

```

Let me know if you’d like to generate a `requirements.txt` file as well or want to include screenshots or video samples!
