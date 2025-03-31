# 🛒 **Shoplift-Tracker**  

**AI-powered real-time shoplifting detection system using YOLO and OpenCV**  

<p align="center">
  <img src="HACK LOGO TEAM.jpg" alt="Emotion Analysis" width="300" hight = 100>
</p>

---

## 🚀 **Overview**
Shoplift-Tracker is a computer vision-based system that detects and tracks shoplifting activities in real-time using **YOLO object detection** and **OpenCV**. It processes video streams to identify suspicious behavior and alerts store owners or security personnel.  

---

## 📌 **Features**
✅ Real-time shoplifting detection  
✅ Uses **YOLO** for object recognition  
✅ Tracks people and detects suspicious behavior  
✅ Displays visual indicators with confidence scores  
✅ Customizable parameters for fine-tuning detection  
✅ Supports both live camera feeds and video files  

---

## 📥 **Installation**

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Shoplift-Tracker.git
   cd Shoplift-Tracker
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv .venv
   .venv\Scripts\activate  # On Windows
   source .venv/bin/activate  # On macOS/Linux
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

---

## 🎥 **Usage**

1. **Activate the virtual environment**
   ```bash
   .venv\Scripts\activate  # Windows
   source .venv/bin/activate  # macOS/Linux
   ```

2. **Run the detection system**
   ```bash
   python shoplifting_detection.py
   ```

3. The system will:
   - Process video input from the specified source
   - Detect and track individuals
   - Classify behavior as normal or suspicious
   - Display real-time alerts

---

## 📂 **Project Structure**
```
Shoplift-Tracker/
├── config/
│   └── parameters.py
├── video/
│   └── input_video.mp4
├── configs/
│   └── shoplifting_weights.pt
├── requirements.txt
├── shoplifting_detection.py
└── README.md
```

---

## 🤝 **Contributing**
Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

---

## 🙏 **Acknowledgments**
- **Ultralytics** for YOLO implementation
- **OpenCV community** for image processing support
- Special thanks to our team members:
  - **Snehal Ranade**
  - **Samruddhi Ahire**
  - **Tejas Borkar**
  - **Sarthak Bidve**
  - **Akshad Makhana**

