type: tool  
name: "Cyber Risk Behavior Index"  
acronym: "Cyber Risk Behavior Index"  
aliases: ["Cyber Risk Behavior Index", "Cyber Risk Behavior"]  
category: scale  
nature: not-reported  
remote_specific: true  
origin: "Klein and Zwilling (2024)"  
original_reference: not-reported  
dimensions: ["cyber-risk behaviors"]  
items:  
risk_categories: ["[[Organizational Risks]]"]  
work_modality: [remote, telework]  
original_language: en  
access: not-reported  
tags: []

---

# Cyber Risk Behavior Index

## Description

Index of cyber-risk behaviors. Part of the study by Klein and Zwilling (2024) on employee cyber-defense behaviors while working from home.

## Origin and development

Not reported in the extraction.

## What it measures

- Cyber-risk behaviors
    

## How it is applied

Not reported in the extraction.

## Articles that used it

```dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Klein and Zwilling (2024)]]: Used as an index to assess cyber-risk behaviors among employees working from home.
    

## Advantages and limitations

**Advantages:** Specific to the remote work context, addresses a relevant emerging risk.

**Limitations:** Not reported in the extraction; details on items, dimensions, and validation are not available.

## Applicability to SMEs and remote or hybrid work