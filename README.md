# Surgeon's Eye: Surgical Assistance and Guidance System

## Overview

**Surgeon's Eye** is an advanced computer-assisted surgical guidance system that leverages deep learning models to assist minimally invasive surgical procedures. It enhances surgeons' abilities by providing:
- **Real-time Visual Question Answering**
- **Surgical Workflow Recognition**
- **Accurate Tool and Anatomy Segmentation**

## Dataset Description

The dataset supports multi-task learning for three specific surgical procedures:

### **Ophthalmology (Cataract Surgery)**
- **Video Duration:** ~14 hours (1,263,116 frames)
- **Annotations:** Over 3,000 frames annotated for surgical phases and instrument segmentation.

### **Laparoscopic Cholecystectomy**
- **Videos:** 80 videos totaling over 70 hours.
- **Annotations:**  
  - 8,000 images annotated for tool instance segmentation.
  - Workflow phases categorized into 7 distinct phases with 1,000+ images per phase.

### **Laparoscopic Hysterectomy**
- **Dataset:** 21 complete procedure videos (~700 hours).
- **Annotations:**  
  - 1,800 frames annotated for instrument and anatomy segmentation.
  - Workflow phases classified into 7 distinct phases.

## Models Implemented

### **YOLOv8**
- **Purpose:** Surgical workflow recognition, tool detection, and segmentation.
- **Accuracy for Tool Detection:** 91.8%
- **Phase Detection Accuracy:** 92%

### **MedViViT Transformer**
- **Purpose:** Transformer-based model for spatio-temporal understanding and workflow recognition.
- **Accuracy:** 83.77%
- **Loss:** 0.40%

## Contributions

- **Developed the comprehensive Surgeon's Eye dataset** for multi-task surgical automation.
- **Implemented and evaluated** deep learning models (YOLOv8 & MedViViT Transformer) for real-time surgical assistance.
- **Provided benchmarks and detailed annotations** to advance research in surgical AI and practical applications.

---
