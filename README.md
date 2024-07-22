# YOLOv4 for Autonomous Vehicle Object Detection

This project focuses on the implementation and evaluation of YOLOv4 for real-time object detection in autonomous vehicles. It aims to enhance vehicle detection accuracy and speed, contributing to safer autonomous driving systems.

## Project Overview

Autonomous vehicles require robust object detection systems to navigate safely. YOLOv4, a state-of-the-art deep learning model, provides real-time object detection capabilities, making it suitable for this application. This project explores the trade-offs between detection speed and accuracy, particularly when incorporating object tracking.

### Key Components
- **YOLOv4 Architecture**: The backbone of the object detection system.
- **MS COCO Dataset**: Used for training the YOLOv4 model.
- **Custom Dataset**: Supplementary data collected and labeled for specific vehicle detection scenarios.
- **Cloud-based Virtual Machine**: Employed for model training and testing.

## Objectives
- Implement YOLOv4 for real-time vehicle detection.
- Evaluate the performance of YOLOv4 in terms of mean Average Precision (mAP) and frames per second (FPS).
- Explore the impact of object tracking on detection speed and accuracy.

## Methodology
1. **Data Collection and Labeling**: Gathering and annotating images for training and validation.
2. **Model Training**: Utilizing pre-trained weights and fine-tuning on the custom dataset.
3. **Performance Evaluation**: Assessing the model using metrics like mAP and FPS.

## Results
- **Detection Accuracy**: YOLOv4 achieved a mAP of up to 71.08% at an IoU threshold of 0.5.
- **Detection Speed**: The model operates at 30.8 FPS in real-time detection mode.
- **Object Tracking**: Introducing tracking capabilities reduced processing speed to 21.45 FPS, highlighting the trade-off between speed and accuracy.

## Conclusion
YOLOv4 demonstrates strong potential for real-time object detection in autonomous vehicles. However, integrating tracking capabilities necessitates further optimization to balance speed and accuracy.
