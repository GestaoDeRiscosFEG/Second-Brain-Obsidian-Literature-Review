type: tool  
name: "Multidimensional Fatigue Inventory"  
acronym: "MFI"  
aliases: ["MFI", "Multidimensional Fatigue Inventory"]  
category: scale  
nature: validated  
remote_specific: false  
origin: not-reported  
original_reference: not-reported  
dimensions: ["general fatigue", "physical fatigue", "mental fatigue", "reduced motivation", "reduced activity"]  
items:  
risk_categories: ["[[Psychosocial Risks]]", "[[Cognitive Risks]]", "[[Physical Risks]]"]  
work_modality: [remote, telework, on-site]  
original_language: en  
access: open  
tags: []

---

# MFI

## Description

Multidimensional inventory to assess fatigue across different dimensions, including general fatigue, physical fatigue, mental fatigue, reduced motivation, and reduced activity. Used in the composite fatigue assessment by Alroomi and Mohamed (2022).

## Origin and development

Not reported in the extraction.

## What it measures

- General fatigue
    
- Physical fatigue
    
- Mental fatigue
    
- Reduced motivation
    
- Reduced activity
    

## How it is applied

Self-administered questionnaire with 5-point Likert scale (1 = not at all to 5 = very high). Number of items not reported in the extraction.

## Articles that used it

dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Alroomi and Mohamed (2022)]]: Used as part of a 14-item composite measure to assess physical and mental fatigue dimensions among isolated oil and gas workers.
    

## Advantages and limitations

**Advantages:** Multidimensional, validated, captures different aspects of fatigue.

**Limitations:** Self-report; may overlap with other fatigue scales; number of items not reported.

## Applicability to SMEs and remote or hybrid work