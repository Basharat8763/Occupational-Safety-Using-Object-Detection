# Occupational-Safety-Using-Object-Detection
## Overview  
This project focuses on **workplace safety** by detecting whether individuals follow essential Personal Protective Equipment (PPE) requirements such as wearing helmets, vests, and masks.  
Using **YOLOv8-based object detection**, the system acts as a real-time safety compliance and training tool for industrial environments — preventing accidents, promoting worker well-being, and fostering a culture of safety and productivity.

---

## Objectives  
- Detect PPE items such as helmets, masks, and vests in real-time.  
- Monitor and alert for missing or non-compliant safety equipment.  
- Provide visual feedback for training and awareness.  
- Demonstrate AI’s application in occupational safety monitoring.  

---

## Features  
- Real-time object detection with live video feed.  
- Detection of multiple PPE classes simultaneously.  
- Color-coded bounding boxes for visual clarity:  
  - 🟩 Compliant  
  - 🟥 Violation  
  - 🟦 Worker  
- High-speed inference using **YOLOv8**.  
- Easily extendable for different industrial environments.  

---

## Tech Stack  
| Category | Tools / Frameworks |
|-----------|-------------------|
| **Programming Language** | Python |
| **Framework** | PyTorch / Ultralytics YOLOv8 |
| **Libraries** | OpenCV, cvzone |
| **Dataset** | PPE Detection Dataset (~6000 labeled images from Roboflow) |
| **IDE / Tools** | PyCharm, Google Colab |

---

## Project Structure
occupational-safety-object-detection/
├── data/
│ ├── train/ # training images & labels
│ ├── valid/ # validation set
│ ├── test/ # test samples
│ ├── data.yaml # YOLO dataset configuration
├── models/ # trained weights (.pt)
├── source_files/ # main Python scripts / notebooks
├── output/ # model logs & checkpoints
├── results/ # inference results, screenshots
├── assets/ # project assets / images
└── README.md
<img width="651" height="451" alt="image" src="https://github.com/user-attachments/assets/63bf4ba3-25e0-40ab-8955-93c1488a5152" />


yaml
Copy code

---

## How to Run  
```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/occupational-safety-object-detection.git
cd occupational-safety-object-detection

# (Optional) create and activate a virtual environment
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run detection
python source_files/detect.py --weights models/best.pt --source 0
