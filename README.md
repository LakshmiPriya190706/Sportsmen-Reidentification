# Sportsmen-Reidentification
# 🏃 Real-Time Sportsmen Detection and Re-Identification Using YOLOv11 and DeepSORT

This project implements a real-time computer vision system for detecting and re-identifying sportsmen in video footage. It combines the power of **YOLOv11** for object detection with **DeepSORT** for identity tracking, enabling persistent player tracking throughout a sports video—even as players leave and re-enter the frame.

---

## 📌 Features

- ⚡ Real-time object detection using YOLOv11
- 🔁 Player re-identification using DeepSORT
- 🎥 Video frame-by-frame processing
- 🧠 Custom-trained YOLO model (`best.pt`) support
- 📦 Output tracked video with player IDs
- 📈 Ideal for sports analytics, broadcast enhancement, and post-match reviews

---

## 🛠️ Installation

Used [Google Colab](https://colab.research.google.com/) for easiest setup, or install locally with:

```bash
pip install ultralytics opencv-python deep_sort_realtime ffmpeg-python

📁 My-project/
├── best.pt                   
├── sportsmen.mp4           
├── tracked_output.avi     
├── tracked_output.mp4      
├── README.md            

Implementation:
1.Open Colab notebook.
2.Upload best.pt and video (15sec_input_720p.mp4).
3.Run the following steps:
Load model,
Process each video frame,
Track with DeepSORT.
4.Export and visualize tracked_output.mp4
Requirements:
Python ≥ 3.8
*ultralytics
*opencv-python
*deep_sort_realtime
*ffmpeg-python
