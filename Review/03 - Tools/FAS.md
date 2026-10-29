type: tool  
name: "Fatigue Assessment Scale"  
acronym: "FAS"  
aliases: ["FAS", "Fatigue Assessment Scale"]  
category: scale  
nature: validated  
remote_specific: false  
origin: not-reported  
original_reference: not-reported  
dimensions: ["physical fatigue", "mental fatigue"]  
items:  
risk_categories: ["[[Psychosocial Risks]]", "[[Cognitive Risks]]", "[[Physical Risks]]"]  
work_modality: [remote, telework, on-site]  
original_language: en  
access: open  
tags: []

---

# FAS

## Description

Fatigue assessment scale used to measure physical and mental fatigue. Part of the composite fatigue measure used by Alroomi and Mohamed (2022).

## Origin and development

Not reported in the extraction.

## What it measures

- Physical fatigue
    
- Mental fatigue
    

## How it is applied

Self-administered questionnaire. Number of items not reported in the extraction.

## Articles that used it

dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Alroomi and Mohamed (2022)]]: Used as part of a 14-item composite measure to assess physical and mental fatigue dimensions among isolated oil and gas workers.
    

## Advantages and limitations

**Advantages:** Validated, covers physical and mental dimensions.

**Limitations:** Self-report; may overlap with other fatigue scales.

## Applicability to SMEs and remote or hybrid work