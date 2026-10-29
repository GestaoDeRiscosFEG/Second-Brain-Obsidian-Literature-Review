type: tool  
name: "TRT_Pose / ResNet18"  
acronym: "TRT_Pose"  
aliases: ["TRT_Pose", "ResNet18", "TRT Pose"]  
category: software  
nature: developed-in-study  
remote_specific: true  
origin: "Piñero-Fuentes et al. (2021)"  
original_reference: not-reported  
dimensions: ["neck inclination", "shoulder alignment", "left arm abduction", "right arm abduction"]  
items:  
risk_categories: ["[[Ergonomic Risks]]"]  
work_modality: [remote, telework]  
original_language: en  
access: not-reported  
tags: []

---

# TRT_Pose

## Description

Posture detection system based on computer vision and deep learning, developed to identify inadequate postures of neck, shoulders, and arms in real time, providing recommendations to the worker to prevent work-related musculoskeletal disorders in telework.

## Origin and development

Developed by Piñero-Fuentes et al. (2021), adapted from the NVIDIA TRT_Pose repository. Uses a ResNet18 convolutional neural network optimized with TensorRT and Torch2TRT.

## What it measures

- Neck inclination
    
- Shoulder alignment
    
- Left arm abduction
    
- Right arm abduction
    
- 18 joint keypoints of the human skeleton
    
- Classification into 4 risk ranges (healthy, low, medium, high)
    

## How it is applied

Processes webcam video in real time. Can run on specialized hardware such as Jetson Xavier NX. Provides alerts and recommendations to the worker.

## Articles that used it

dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Piñero-Fuentes et al. (2021)]]: System developed and tested for postural detection in telework, achieving 84.1% overall accuracy.
    

## Advantages and limitations

**Advantages:** Real time, no body-worn sensors, low energy consumption, accuracy above 80%.

**Limitations:** Tested in laboratory with limited dataset; requires specialized hardware; privacy concerns (camera).

## Applicability to SMEs and remote or hybrid work