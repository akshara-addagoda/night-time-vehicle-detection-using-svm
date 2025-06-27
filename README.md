# night-time-vehicle-detection-using-svm
🚗 Night-Time Vehicle Detection Using SVM  A computer vision project that detects vehicles in night-time traffic scenes using image processing and a Linear SVM classifier. Includes optional YOLOv3 for enhanced detection in images and videos.
# Night-Time Vehicle Detection Using SVM

This project focuses on detecting vehicles in night-time traffic images and videos using image processing techniques and a Linear Support Vector Machine (SVM) classifier. It also includes an option to use YOLOv3 for enhanced object detection.

## Features
- Detect vehicles in night-time conditions
- Image processing using OpenCV
- Linear SVM classifier for detection
- YOLOv3 support for real-time object detection
- Works with images and video input

## Requirements
- Python 3.x
- OpenCV
- NumPy

## Usage

### Image Detection
```bash
python Traffic_Scence_image_detection.py --image path/to/image.jpg --yolo path/to/yolo-coco
Video Detection
bash
Copy
Edit
python Traffic_Scence_video_detection.py --video path/to/video.mp4 --yolo path/to/yolo-coco
Replace path/to/yolo-coco with the folder containing yolov3.weights, yolov3.cfg, and coco.names.

Folder Structure
css
Copy
Edit
.
├── Source Code/
│   ├── Traffic_Scence_image_detection.py
│   ├── Traffic_Scence_video_detection.py
├── yolo-coco/
│   ├── yolov3.weights
│   ├── yolov3.cfg
│   └── coco.names
├── images/
├── videos/
└── README.md
Author
Akshara Addagoda
GitHub: @akshara-addagoda
