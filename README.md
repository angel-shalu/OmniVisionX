# 🤖 OmniVisionX – Multi-Model AI Vision Analyzer

OmniVisionX is an advanced **AI-powered computer vision application** built using **Python, Streamlit, and YOLOv8**.  
It enables **real-time multi-model analysis** including object detection, segmentation, pose estimation, tracking, and counting on **images, videos, and live webcam streams**.

---

## 🚀 Key Features

- 🔍 Object Detection (YOLOv8)
- 🧩 Image Segmentation
- 🧍 Pose Estimation
- 🎯 Object Tracking
- 🔢 Object Counting
- 🖼️ Image upload & analysis
- 🎞️ Video upload & processing
- 📷 Real-time webcam detection
- ⚙️ Adjustable confidence threshold
- ⬇️ Download processed images & videos
- 🎨 Modern, responsive Streamlit UI

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit** – Web interface
- **YOLOv8 (Ultralytics)** – Deep learning models
- **OpenCV** – Image & video processing
- **NumPy** – Numerical operations
- **Pillow (PIL)** – Image handling

---

## 📂 Project Structure

```bash
├── app.py                   # Main Streamlit application
├── yolov8n.pt               # YOLOv8 detection model
├── yolov8n-seg.pt           # YOLOv8 segmentation model
├── yolov8n-pose.pt          # YOLOv8 pose estimation model
├── processed_output_multi.mp4  # Output video (generated)
├── requirements.txt         # Project dependencies
└── README.md                # Documentation

# Installation & Setup
# 1️⃣ Clone the Repository
git clone https://github.com/your-username/OmniVisionX.git
cd OmniVisionX

# 2️⃣ Create a Virtual Environment (Recommended)
python -m venv venv
source venv/bin/activate        # Linux / macOS
venv\Scripts\activate           # Windows

# 3️⃣ Install Dependencies
pip install -r requirements.txt


requirements.txt

streamlit
ultralytics
opencv-python
numpy
pillow

# ▶️ Run the Application
streamlit run app.py


Open in your browser:

http://localhost:8501

# 🧠 How It Works

Select one or more YOLOv8 models from the sidebar

Choose input type: Image, Video, or Webcam

Adjust confidence threshold

Run multi-model inference

View results and download outputs

# ⚠️ Notes & Limitations

Webcam mode works only in local execution

Video processing speed depends on system performance

GPU support is recommended for faster inference

# 🌟 Future Enhancements

🚀 GPU / ONNX / TensorRT optimization

📊 Analytics dashboard

☁️ Cloud deployment (Streamlit Cloud / AWS)

📦 Docker support

📈 Model performance comparison

# 👩‍💻 Author

Shalini Kumari
📧 Email: shalinikumari8789@gmail.com

💻 GitHub: https://github.com/angel-shalu

Live Demo: https://fvlkav9lyw6j8jrubujsog.streamlit.app/
