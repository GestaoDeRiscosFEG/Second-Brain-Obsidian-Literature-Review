type: tool  
name: "MSD Assessment Tool"  
acronym: "MSD Assessment Tool"  
aliases: ["MSD Assessment Tool", "MSD"]  
category: questionnaire  
nature: validated  
remote_specific: false  
origin: not-reported  
original_reference: not-reported  
dimensions: ["frequency of discomfort", "intensity of discomfort", "14 anatomical regions"]  
items:  
risk_categories: ["[[Ergonomic Risks]]", "[[Physical Risks]]"]  
work_modality: [remote, hybrid, telework, on-site]  
original_language: en  
access: open  
tags: []

---

# MSD Assessment Tool

## Description

Self-report questionnaire to assess frequency and intensity of musculoskeletal discomfort in 14 anatomical regions, including eyes. Developed for screening work-related musculoskeletal disorders.

## Origin and development

Developed and validated by Marley and Kumar (1996). Used by Chim and Chen (2023) in the context of telework in Hong Kong during the COVID-19 pandemic.

## What it measures

- Frequency of discomfort (scale of 0 to 3: never to almost every day)
    
- Intensity of discomfort (scale of 0 to 10)
    
- 14 anatomical regions (including eyes)
    
- Allows identification of pain patterns and most affected areas
    

## How it is applied

Self-administered questionnaire. Can be applied in person or online. Used for ergonomic diagnosis and follow-up of interventions.

## Articles that used it

dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Chim and Chen (2023)]]: Used to assess the prevalence of musculoskeletal discomfort in teleworkers and its association with workstation setup.
    

## Advantages and limitations

**Advantages:** Covers 14 anatomical regions, assesses frequency and intensity, allows comparison between studies, validated.

**Limitations:** Self-report; does not replace clinical assessment; adapted versions may compromise comparability.

## Applicability to SMEs and remote or hybrid work