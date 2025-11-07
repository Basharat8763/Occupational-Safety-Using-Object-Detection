# Occupational-Safety-Using-Object-Detection
## Overview  
This project focuses on **workplace safety** by detecting whether individuals follow essential Personal Protective Equipment (PPE) requirements such as wearing helmets, vests, and masks.  
Using **YOLOv8-based object detection**, the system acts as a real-time safety compliance and training tool for industrial environments — preventing accidents, promoting worker well-being, and fostering a culture of safety and productivity.

---

## Objectives  
- Detect PPE items such as helmets, masks, and vests in real-time.   
- Provide visual feedback for training and awareness.   
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

