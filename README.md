# train_yolov3_colab
# YOLOv3 Training on Colab with Darknet

This repository provides a ready-to-run Colab setup to train YOLOv3 using Darknet framework, optimized for Google Colab.

## Features
- Train YOLOv3 on Google Colab GPU (12GB RAM)
- Directly use files from Google Drive
- Precompiled Darknet to reduce runtime load times
- Utilities to display, upload, and download files
- Automatic backup of trained weights every 100 iterations

## Folder Structure

## Setup Instructions

1. Open `train_yolov3_colab.ipynb` in Google Colab
2. Change runtime type to **GPU**
3. Mount your Google Drive (this repo must be synced)
4. Install cuDNN version matching Colab's CUDA (v10.0 for default)
5. Compile Darknet on first run (precompiled saved to Drive)
6. Copy dataset to VM (optional but recommended)
7. Start training

## References
- YOLOv3 original website: [https://pjreddie.com/darknet/yolo/](https://pjreddie.com/darknet/yolo/)
- AlexeyAB Darknet GitHub: [https://github.com/AlexeyAB/darknet](https://github.com/AlexeyAB/darknet)
- Inspired by Ivan Goncharov and David Ibañez notebooks

## Notes
- Keep your browser open to prevent Colab from idling (90 minutes idle, 12 hours max runtime)
- Backup your weights regularly
- Paths in config files must be carefully set
