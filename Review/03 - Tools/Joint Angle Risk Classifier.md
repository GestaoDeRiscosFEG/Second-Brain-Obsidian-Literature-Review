type: tool  
name: "Joint Angle Risk Classifier"  
acronym: "Joint Angle Risk Classifier"  
aliases: ["Joint Angle Risk Classifier", "Classificador de Ângulos Articulares"]  
category: method  
nature: developed-in-study  
remote_specific: true  
origin: "Piñero-Fuentes et al. (2021)"  
original_reference: not-reported  
dimensions: ["neck inclination", "shoulder alignment", "arm abduction"]  
items:  
risk_categories: ["[[Ergonomic Risks]]"]  
work_modality: [remote, telework]  
original_language: en  
access: not-reported  
tags: []

---

# Joint Angle Risk Classifier

## Description

Algorithm that calculates joint angles in real time through the atan2 function for 4 parameters (neck inclination, shoulder alignment, and left and right arm abduction) and classifies them into 4 risk ranges (Range 0: healthy/very low; Range 1: low; Range 2: medium; Range 3: high/unsafe).

## Origin and development

Developed by Piñero-Fuentes et al. (2021) based on Chaffin et al. and Woodson et al. ergonomic guidelines.

## What it measures

- Neck inclination
    
- Shoulder alignment
    
- Left arm abduction
    
- Right arm abduction
    
- 4-level risk classification per parameter
    

## How it is applied

Runs in real time integrated with the TRT_Pose system, using video frames from the webcam.

## Articles that used it

dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Piñero-Fuentes et al. (2021)]]: Algorithm integrated into the posture detection system to classify joint angles into risk ranges.
    

## Advantages and limitations

**Advantages:** Real time, based on established ergonomic guidelines, provides actionable feedback.

**Limitations:** Limited to 4 parameters; does not evaluate the spine, which requires more than a single straight segment.

## Applicability to SMEs and remote or hybrid work