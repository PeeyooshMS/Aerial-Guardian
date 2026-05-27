# Aerial-Guardian
Lightweight drone-based person detection and multi-object tracking pipeline using YOLOv8n, ByteTrack-style tracking, motion compensation, trajectory tails, and FPS reporting for the Aerial Guardian challenge.
# The Aerial Guardian: Drone-Based Person Detection and Tracking

This repository contains a lightweight computer-vision pipeline for detecting and tracking persons from moving drone footage. The solution uses a YOLOv8n-based detector, ByteTrack-style multi-object tracking, global motion compensation, and trajectory-tail visualization. The pipeline generates an annotated output video with bounding boxes, unique tracking IDs, trajectory trails, and FPS metrics.

GitHub topics/tags
computer-vision
object-detection
multi-object-tracking
yolov8
bytetrack
drone-video
visdrone
opencv
python
edge-ai

## Project Summary

The objective of this project is to detect and track multiple persons from aerial drone footage. The pipeline is designed to handle small object sizes, moving-camera noise, and ID switching. It provides an output video with bounding boxes, unique ID labels, trajectory tails, and FPS reporting. The solution is lightweight and can be adapted for edge deployment using ONNX or TensorRT.
