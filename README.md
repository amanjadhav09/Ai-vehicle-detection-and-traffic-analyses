# AI-Based Traffic Monitoring Dashboard

## Overview
The AI-Based Traffic Monitoring Dashboard is a real-time vehicle detection and tracking system developed using Python, Streamlit, YOLOv8, OpenCV, and DeepSORT.  
The project analyzes traffic videos, detects multiple vehicles, tracks their movement, and provides traffic monitoring insights through an interactive dashboard.

---

## Features
- Real-time vehicle detection
- Vehicle tracking using DeepSORT
- Traffic video processing
- Vehicle counting
- Lane activity monitoring
- Interactive Streamlit dashboard
- Upload and analyze traffic videos
- AI-powered object detection using YOLOv8

---

## Technologies Used
- Python
- Streamlit
- YOLOv8 (Ultralytics)
- OpenCV
- DeepSORT
- NumPy
- Pandas
- Scikit-learn
- PyTorch
- Matplotlib
- Seaborn

---

## Project Structure

```bash
traffic_project/
│
├── original_traffic_dashboard.py
├── requirements.txt
├── yolov8n.pt
└── venv/
```

---

## Installation

### 1. Clone or Download Project

Download the project files into your system.

---

### 2. Create Virtual Environment

```bash
python -m venv venv
```

---

### 3. Activate Virtual Environment

#### Mac/Linux

```bash
source venv/bin/activate
```

#### Windows

```bash
venv\Scripts\activate
```

---

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Additional Package Installation

If any module errors occur, install the missing packages manually.

### Install OpenCV

```bash
pip install opencv-python
```

### Install Ultralytics

```bash
pip install ultralytics
```

### Install DeepSORT

```bash
pip install deep-sort-realtime==1.3.2
```

---

## Running the Project

Run the Streamlit dashboard using:

```bash
python -m streamlit run original_traffic_dashboard.py
```

After running the command, open:

```bash
http://localhost:8501
```

in your browser.

---

## How It Works

1. User uploads a traffic video.
2. YOLOv8 detects vehicles frame by frame.
3. DeepSORT tracks detected vehicles uniquely.
4. OpenCV processes video frames.
5. Streamlit displays the processed output on dashboard.
6. Traffic statistics and vehicle analytics are generated.

---

## Advantages
- Real-time traffic monitoring
- Accurate vehicle detection
- Automatic traffic analysis
- Easy-to-use dashboard
- Supports smart city applications
- Reduces manual monitoring

---

## Applications
- Smart traffic systems
- Highway surveillance
- Vehicle monitoring
- Traffic management systems
- Smart city projects
- Traffic violation analysis

---

## Future Enhancements
- Speed estimation
- Accident detection
- License plate recognition
- Traffic signal automation
- Cloud-based monitoring

---

## Author
Developed as an AI-based traffic monitoring project using computer vision and machine learning technologies.

---

## License
This project is for educational and academic purposes.
