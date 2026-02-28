# MultimedAI

## AI-Based Multimodal Radiology Analysis with ICD-11 and Ayurvedic Mapping

---

## Overview

MultimedAI is an AI-driven medical imaging platform developed during my internship under the Ministry of AYUSH. The system analyzes multiple radiology modalities, including MRI, CT scans, and X-rays, to generate automated diagnostic predictions.

In addition to pathology detection, the platform maps findings to:

- ICD-11 disease classification codes  
- Corresponding Ayurvedic diagnostic interpretations  

The objective of the project is to bridge modern AI-based radiology with standardized medical coding and traditional healthcare frameworks.

Due to institutional policies, the full source code and trained model weights are not publicly available. A demonstration video is provided in this repository.

---

## System Architecture

- Brain MRI Tumor Segmentation Module  
- CT Scan Analysis Module  
- X-ray Abnormality Detection Module  
- ICD-11 Mapping Engine  
- Ayurvedic Correlation Engine  

---

## Brain MRI Module (My Contribution)

### Objective

To detect and segment tumor regions in MRI scans and classify them into:

- Glioma  
- Meningioma  
- Pituitary Tumor  
- No Tumor  

### Model Details

- Architecture: YOLOv8-Seg  
- Framework: PyTorch  
- Dataset: Brain Tumor Segmentation (Roboflow Universe)  
- Task: 4-class semantic segmentation  

### Performance

- Validation Accuracy: ~83%  
- Strong segmentation overlap for tumor regions  
- Stable training convergence  

The output is further mapped to relevant ICD-11 codes and Ayurvedic diagnostic correlations.

---

## CT and X-Ray Modules

The CT module performs abnormality detection and lesion localization, while the X-ray module focuses on fracture detection and structural abnormalities.

Both modules integrate with the same diagnostic mapping pipeline to generate standardized disease coding and traditional medical interpretations.

---

## ICD-11 and Ayurvedic Mapping

After inference, detected findings are mapped to:

- ICD-11 classification codes for structured clinical reporting  
- Ayurvedic diagnostic equivalents to support integrative healthcare perspectives  

This dual mapping framework enables compatibility with modern digital health systems while maintaining alignment with traditional medical knowledge.

---

## Technology Stack

- Python  
- PyTorch  
- YOLOv8 (Ultralytics)  
- OpenCV  
- NumPy  
- Roboflow  

---

## Demo Video

[Download / Watch Demo Video](./MultimedAI_Demo.mp4)

---

## Code Availability

This project was developed under the Ministry of AYUSH Internship Program. Due to institutional data-sharing restrictions:

- Full source code is not publicly available  
- Trained model weights are not shared  
- Demonstration video illustrates system functionality  

---

## Author

Harshita Tiwari  
Machine Learning | Medical Imaging | AI in Healthcare  

Contributed specifically to the Brain MRI tumor segmentation model development, training pipeline, performance optimization, and diagnostic mapping integration.
