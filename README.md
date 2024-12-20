# YOLO_Image_Reco

A lightweight Flask-based API for object detection using the YOLOv5 model. This project allows you to upload images via a web interface or API and run object detection to identify objects in the image with bounding boxes and confidence scores. It also includes a frontend for easy interaction.

---

## Features
- Object detection using YOLOv5
- Flask-based REST API
- Docker support for easy deployment
- Frontend interface for uploading images
- Detailed logging and error handling




---

## Requirements
Ensure you have the following installed:
- Python 3.8 or above
- pip

---

## Setup and Installation

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/yolo_image_reco.git
cd yolo_image_reco

pip install -r requirements.txt

python app.py

curl -X POST -F "file=@path_to_image.jpg" http://127.0.0.1:5000/detect
