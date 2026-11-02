# Deep Learning PR 3 – Computer Vision

## Project Overview
This project focuses on implementing different Computer Vision and Deep Learning techniques using Python and OpenCV. It covers image processing, morphological operations, bitwise operations, image histograms, face detection using YuNet, and object detection using YOLOv8.

The project also combines multiple techniques into an integrated detection pipeline and compares their performance using processing time and FPS.


# project explanation video
https://drive.google.com/file/d/1cQG09GYN5mnsGEYZQqqovdrpBfXgWxAI/view?usp=drive_link
## Objectives
- Understand basic image processing techniques.
- Apply morphological operations to binary images.
- Perform bitwise operations using image masks.
- Analyze grayscale and RGB image histograms.
- Detect faces using the YuNet face detection model.
- Detect objects using the YOLOv8 model.
- Build an integrated face and object detection pipeline.
- Compare detection performance using FPS and processing time.

## Tasks Covered

### Task 1: Morphological Operations
- Image loading and preprocessing.
- Image thresholding and binarization.
- Erosion and dilation.
- Opening and closing operations.
- Comparison of rectangular, elliptical, and cross-shaped kernels.
- Noise removal using morphological operations.

### Task 2: Bitwise Operations and Image Histograms
- Creation of circular and rectangular masks.
- Bitwise AND, OR, XOR, and NOT operations.
- Mask-based image overlay.
- Grayscale and RGB histogram visualization.
- Brightness and contrast adjustment.

### Task 3: Face Detection Using YuNet
- Loading the pretrained YuNet ONNX model.
- Face detection on static images.
- Drawing face bounding boxes and facial landmarks.
- Displaying confidence scores.
- Real-time webcam face detection.
- Confidence threshold comparison.
- Face blurring for basic privacy protection.

### Task 4: Object Detection Using YOLOv8
- Loading the pretrained YOLOv8 model.
- Object detection on multiple images.
- Displaying bounding boxes, labels, and confidence scores.
- Real-time webcam object detection.
- Comparing confidence and IoU thresholds.
- Counting detected objects by class.
- Visualizing object detection statistics.

### Task 5: Integrated Pipeline and Performance Comparison
- Combining YuNet and YOLOv8 detection.
- Real-time face and object detection.
- Applying morphological preprocessing.
- Comparing original and processed images.
- Benchmarking YuNet-only, YOLO-only, and combined detection.
- Measuring processing time and FPS over 100 webcam frames.
- Generating comparison tables, charts, and CSV reports.

## Technologies and Libraries

| Technology | Purpose |
|---|---|
| Python | Programming language |
| OpenCV | Image processing and computer vision |
| NumPy | Numerical operations |
| Matplotlib | Image and graph visualization |
| Pandas | Data handling and comparison tables |
| Ultralytics YOLOv8 | Object detection |
| YuNet | Face detection |
| ONNX | Pretrained face detection model format |

## Project Structure

```text
PR3_Deep_Learning/
│
├── CV_PR3.ipynb
│
├── data/
│   └── images/
│       ├── lena.jpg
│       ├── baboon.jpg
│       ├── coins.png
│       ├── face1.jpg
│       ├── face2.jpg
│       ├── face3.jpg
│       ├── objects1.jpg
│       ├── objects2.jpg
│       └── objects3.jpg
│
├── models/
│   └── face_detection_yunet_2023mar.onnx
│
└── README.md
```

Make sure the image files and YuNet ONNX model are placed in their respective folders before running the notebook. Webcam-based tasks require a working camera and access to it from the local environment.

## Applications
- Face recognition and face detection systems.
- Smart surveillance systems.
- Real-time object detection.
- Image enhancement and preprocessing.
- Privacy protection through face blurring.
- Automated visual monitoring.

## Key Learnings
- Practical understanding of image processing using OpenCV.
- Working with pretrained deep learning models.
- Understanding face and object detection.
- Comparing detection thresholds and model performance.
- Building an integrated computer vision pipeline.
- Measuring model performance using processing time and FPS.


## Author
**Daksh Hasaji**

Computer Engineering Student | AI & ML Enthusiast

---

*This project was completed as part of Deep Learning Practical Assignment 3.*
