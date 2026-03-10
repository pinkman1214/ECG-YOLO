
# ECG-YOLO
# Edge-Enhanced and Context-Guided Detection of Steel Surface Defects

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
Official PyTorch implementation of the paper:

**Edge-Enhanced and Context-Guided Detection of Steel Surface Defects**  
Zhentao Hu , Jing Yan , Fei Niu, Wei Hou  
School of Artificial Intelligence, Henan University  

---
## 🛠️ Environment and Dependencies

This project was developed and evaluated under the following environment settings [cite: cas Configuration
* **OS:** Windows
* **CPU:** Intel Core i7-11700K
* **GPU:** NVIDIA GeForce RTX 3090 (24 GB VRAM)

### Software Dependencies
* **Python:** 3.9
* **PyTorch:** 1.12.1
* **CUDA:** 11.6 [cite: cas-sc-sample.pdfend using Conda to manage your environment. You can set it up quickly with the following commands:

## 📌 Highlights

- 🎯 **Specialized for Steel Surface Defect Detection**  
  Addresses blurred defect edges, multi-scale variations, and interference from complex textured backgrounds.

  - 🧩 **Modular and Lightweight Architecture**  
    Includes three novel modules: `EFEConv`, `CGDown`, and `GCEDet`.

- ⚡ **State-of-the-Art Performance**  
  Achieves **79.6% mAP** on NEU-DET and **67.8% mAP** on GC10-DET.

---

## 📁 Project Structure

```plaintext
ECG-YOLO/
├── docker/               
├── docs/             
├── examples/            
├── tests/
├── ultralytics/
├── train.py             
├── dataset.yaml              
├── modocs.yaml     
├── README.md           
└── LICENSE              

