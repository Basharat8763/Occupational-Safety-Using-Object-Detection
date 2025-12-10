# Occupational Safety and Training Using Object Detection

## Overview
This project presents an object detection–based system designed to improve occupational safety in industrial and construction environments. The system identifies essential Personal Protective Equipment (PPE) such as helmets, vests, and masks in real time.  

Using the YOLOv8 deep learning model, the application enables automated monitoring of worker safety compliance, minimizes manual supervision errors, and supports training through real-time visual feedback. The goal is to enhance workplace safety standards and prevent avoidable accidents.

---

## Objectives
- Detect PPE equipment (helmet, mask, vest) in real time.
- Identify non-compliant individuals in a live video stream.
- Provide clear visual indicators for safety violations.
- Demonstrate practical application of computer vision using YOLOv8.
- Support safety training and compliance awareness.

---

## Features
- Real-time object detection using a live camera feed.
- Detection of multiple PPE classes simultaneously.
- Color-coded bounding box indicators:
  - Green: PPE compliant
  - Red: Safety violation
  - Blue: Worker detected
- High detection accuracy based on YOLOv8 model performance.
- Can be adapted for different workplace setups and industries.
- Modular implementation for easy integration and scalability.

---

## Tech Stack

| Category | Tools / Frameworks |
|---------|---------------------|
| Programming Language | Python |
| Deep Learning Framework | PyTorch, Ultralytics YOLOv8 |
| Computer Vision Libraries | OpenCV, cvzone |
| Dataset | PPE Detection Dataset (approx. 6000 labeled images from Roboflow) |
| Development Tools | PyCharm, Google Colab |

---

## Project Structure
<img width="473" height="603" alt="image" src="https://github.com/user-attachments/assets/a530a447-31e1-4557-bc8b-ab2e4f94a120" />

---

## How It Works
1. The trained YOLOv8 model loads into the detection script.
2. The live video stream is captured frame by frame.
3. Each frame is passed through the model for inference.
4. PPE items are identified and marked with bounding boxes.
5. The system highlights violations and compliance using color-coded labels.
6. The output is displayed to the user in real time.

---

## Results
- Model trained for 50 epochs using PPE detection dataset.
- Achieved strong detection performance across all PPE classes.
- Clear differentiation between worker, compliant PPE, and violations.
- Real-time inference achieved with minimal latency.
- Demonstrated successful detection in multiple test videos.

Screenshots, training graphs, and video outputs will be added soon.

---

## Future Improvements
- Train on larger datasets and more diverse environments.
- Integrate ID tracking for repeated safety violations.
- Add automated alert system for instant notifications.
- Deploy on edge devices such as Jetson Nano or Raspberry Pi.
- Add a web dashboard for real-time analytics and reporting.
- Integrate IoT-based alarm systems for on-site alerts.

---

## License
This project is intended for academic and research purposes.

---

## Status
Initial repository created.  
Source files, datasets, and trained model checkpoints will be uploaded soon.

