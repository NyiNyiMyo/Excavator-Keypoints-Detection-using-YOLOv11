# Excavator Keypoints Detection using YOLOv11

[![python](https://img.shields.io/badge/Python-3.11-3776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org)
[![pytorch](https://img.shields.io/badge/PyTorch-2.6.0-EE4C2C.svg?style=flat&logo=pytorch)](https://pytorch.org)
![Static Badge](https://img.shields.io/badge/Keypoints-Detection-cyan)
![Static Badge](https://img.shields.io/badge/Ultralytics-darkblue)

This repository contains keypoints detection project focused on **Robotic like Machine, Excavator** with **6 keypoints** using **YOLOv11**.

<img src="https://github.com/user-attachments/assets/50ca0ba4-0865-4ad2-9bbc-8504e3346e3d" width="270">
<img src="https://github.com/user-attachments/assets/d8f2ac1a-b6ad-485f-af0b-446296962e7e" width="270">
<img src="https://github.com/user-attachments/assets/a83d85c0-8e46-493c-822f-511d336198d3" width="270">

<img src="https://github.com/user-attachments/assets/50ca0ba4-0865-4ad2-9bbc-8504e3346e3d" width="270">
<img src="https://github.com/user-attachments/assets/d8f2ac1a-b6ad-485f-af0b-446296962e7e" width="270">
<img src="https://github.com/user-attachments/assets/a83d85c0-8e46-493c-822f-511d336198d3" width="270">

<img src="https://github.com/user-attachments/assets/07e7490c-244a-4a2f-b97b-4c36ad376c9d" width="270">
<img src="https://github.com/user-attachments/assets/b5acf516-7003-40b2-a660-002ecdbdedd7" width="270">
<img src="https://github.com/user-attachments/assets/1d0568bc-3399-4a88-9bc4-5f289f884a02" width="270">

<img src="https://github.com/user-attachments/assets/07e7490c-244a-4a2f-b97b-4c36ad376c9d" width="270">
<img src="https://github.com/user-attachments/assets/b5acf516-7003-40b2-a660-002ecdbdedd7" width="270">
<img src="https://github.com/user-attachments/assets/1d0568bc-3399-4a88-9bc4-5f289f884a02" width="270">

---

## 🧭 Dataset Overview

Total train images: 642 / Total val images: 54

✅ keypoint_names = [ 'bucket', 'hinge1', 'hinge2', 'driver_seat', 'rear', 'b_hinge' ]  
✅ skeleton = [ (1,6), (2,3), (3,4), (4,5), (6,2) ] 

---

## 🏗️ Model Architecture

- 🦾 Model: **YOLOv11**
- 🦾 Type: **Bottom-up**
- 🦾 Weight: **"yolo11l-pose.pt"**
- 🦾 Framework: **PyTorch + Ultralytics**
- 🦾 Input Size: **640**
- 🦾 Trained Epochs: **100**

---
