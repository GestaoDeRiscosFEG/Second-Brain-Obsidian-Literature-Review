type: tool  
name: "Fatigue Questionnaire"  
acronym: "FQ"  
aliases: ["FQ", "Fatigue Questionnaire", "Chalder Fatigue Scale"]  
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

# FQ

## Description

Fatigue questionnaire, also known as Chalder Fatigue Scale, assessing physical and mental fatigue. Used in the composite fatigue assessment by Alroomi and Mohamed (2022).

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

**Advantages:** Validated, distinguishes physical and mental fatigue.

**Limitations:** Self-report; may overlap with other fatigue scales.

## Applicability to SMEs and remote or hybrid work