type: tool  
name: "24-hour Holter ECG / Heart Rate Variability"  
acronym: "24-h Holter ECG / HRV"  
aliases: ["24-h Holter ECG", "Holter ECG", "HRV", "Heart Rate Variability"]  
category: equipment  
nature: validated  
remote_specific: false  
origin: not-reported  
original_reference: not-reported  
dimensions: ["cardiac autonomic profile", "heart rate variability"]  
items:  
risk_categories: ["[[Physical Risks]]", "[[Psychosocial Risks]]"]  
work_modality: [remote, on-site, comparative]  
original_language: en  
access: not-reported  
tags: []

---

# 24-h Holter ECG / HRV

## Description

24-hour electrocardiography for analysis of cardiac autonomic modulation and heart rate variability. Used to assess physiological stress responses during remote and in-office work.

## Origin and development

Not reported in the extraction.

## What it measures

- Cardiac autonomic profile (CAP)
    
- Heart rate variability (HRV)
    

## How it is applied

Holter device worn for 24 hours, recording continuous ECG. Analysis of heart rate variability indices.

## Articles that used it

dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Perego et al. (2024)]]: Used to assess cardiac autonomic profile during remote and in-office work.
    

## Advantages and limitations

**Advantages:** Objective physiological measurement, continuous recording.

**Limitations:** Requires equipment and specialized analysis; may be uncomfortable for participants.

## Applicability to SMEs and remote or hybrid work