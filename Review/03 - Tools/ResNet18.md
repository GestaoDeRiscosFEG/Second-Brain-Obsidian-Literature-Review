type: tool  
name: "ResNet18"  
acronym: "ResNet18"  
aliases: ["ResNet18", "ResNet-18", "Residual Neural Network 18"]  
category: software  
nature: validated  
remote_specific: false  
origin: not-reported  
original_reference: not-reported  
dimensions: ["18-layer convolutional neural network", "image classification", "pose estimation backbone"]  
items:  
risk_categories: ["[[Ergonomic Risks]]"]  
work_modality: [remote, telework, on-site]  
original_language: en  
access: open  
tags: []

---

# ResNet18

## Description

18-layer residual convolutional neural network architecture, used as the backbone for pose estimation in the TRT_Pose posture detection system. Estimates 18 joint keypoints of the human skeleton in real time from webcam video.

## Origin and development

Not reported in the extraction. The article by Piñero-Fuentes et al. (2021) adapted ResNet18 from the NVIDIA TRT_Pose repository, optimized with TensorRT and Torch2TRT.

## What it measures

- 18 joint keypoints of the human skeleton
    
- Posture of neck, shoulders, and arms
    
- Real-time pose estimation from video frames
    

## How it is applied

Runs on specialized hardware (e.g., Jetson Xavier NX) to process webcam video in real time. Integrated into the TRT_Pose system for posture detection and risk classification.

## Articles that used it

dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Piñero-Fuentes et al. (2021)]]: Used as the neural network backbone for the TRT_Pose posture detection system, achieving 84.1% overall accuracy.
    

## Advantages and limitations

**Advantages:** Real time, low energy consumption, open architecture, accuracy above 80%.

**Limitations:** Tested in laboratory with limited dataset; requires specialized hardware; privacy concerns (camera).

## Applicability to SMEs and remote or hybrid work