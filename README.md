# **Car Detection and Counting using YOLOv8 and SORT**

## **Overview**
- **Developed** a real-time object detection and tracking system to monitor and count cars in traffic video feeds.
- **Leveraged** YOLOv8 for accurate object detection and **SORT (Simple Online and Realtime Tracking)** for tracking across frames.
- **Optimized** for minimal latency and high detection accuracy in dynamic environments.

## **Key Features**
- **YOLOv8-Based Detection**  
  - Fine-tuned on a **custom dataset** specifically for car detection.
- **Custom Data Annotation**  
  - Curated video frames and manually annotated bounding boxes to improve model accuracy.
- **Real-Time Tracking with SORT**  
  - Integrated **SORT** for consistent object tracking across frames using Kalman filtering and the Hungarian algorithm.
- **OpenCV-Powered Pipeline**  
  - Handled video capture, preprocessing, and real-time visualization using OpenCV.

## **Tech Stack**
- **YOLOv8** (Ultralytics)
- **Python**
- **OpenCV**
- **NumPy**
- **SORT (Kalman Filter + Hungarian Algorithm)**

## **Highlights**
- **Real-time inference speed** on standard GPUs.
- **Robust tracking** even under occlusion or heavy traffic.
- **Modular architecture** for easy model or tracker replacement.

## **Applications**
- **Traffic surveillance systems**
- **Automated toll booths**
- **Smart parking management**
- **Vehicle flow analysis**

