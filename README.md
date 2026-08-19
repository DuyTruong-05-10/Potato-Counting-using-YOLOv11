# 🥔 Potato Detection, Tracking & Counting System
AI-based potato detection and counting system using YOLOv11 and OpenCV on a conveyor belt.

## 🎥  Demo Video

<p align="center">
  <a href="https://youtu.be/Dv8af0bsMFQ">
    <img src="https://img.shields.io/badge/▶%20Watch-Demo-red?style=for-the-badge" />
  </a>
</p>


## 📌 Overview

An Industrial Computer Vision system for automatic potato detection, multi-object tracking, and real-time counting from video streams.

The system uses YOLO for object detection and a custom tracking algorithm to maintain a unique ID for each potato across consecutive frames. Detected objects are continuously tracked and counted when they pass the defined counting region.

Key Features :'
 - Potato Detection — Detect potatoes using YOLO
 - Object Tracking — Assign and maintain a unique ID for each potato
 - Automatic Counting — Count each potato only once
 - Video Processing — Process potato streams frame by frame
 - Industrial Vision Approach — Designed with object detection, tracking, and counting as separate processing stages
