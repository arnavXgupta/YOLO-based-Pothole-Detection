# Pothole Detection using YOLOv8  

This project uses **YOLOv8** for real-time pothole detection, drawing bounding boxes around all detected potholes. The trained model achieves **over 98% accuracy**, making it highly reliable for road damage detection applications.  

The repository also includes the **`best.pt`** trained weights file, so you can run detections right away without retraining.  

## Features  
- Real-time pothole detection  
- Bounding boxes for each detected pothole  
- Lightweight and fast YOLOv8 model  
- Achieves **98%+ accuracy** on test data  
- Includes **`best.pt`** trained weights in the repo  

## Dataset  
You can download the dataset used for training here:  
[📂 Pothole Dataset (Google Drive)](https://drive.google.com/drive/folders/1kTu8gWb5u3HKFw1akapM1RWcpfROsBm7?usp=sharing)  

## Installation & Usage  
```bash
# Clone the repository
git clone https://github.com/yourusername/pothole-detection-yolov8.git
cd pothole-detection-yolov8

# Install dependencies
pip install ultralytics

# Run detection using included best.pt
python pothole_yolov8.py --source path_to_images_or_video --weights best.pt
