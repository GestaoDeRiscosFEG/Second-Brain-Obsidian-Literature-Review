type: tool  
name: "Maslach Burnout Inventory - General Survey"  
acronym: "MBI-GS"  
aliases: ["MBI-GS", "Maslach Burnout Inventory", "MBI"]  
category: scale  
nature: validated  
remote_specific: false  
origin: not-reported  
original_reference: not-reported  
dimensions: ["emotional exhaustion", "depersonalization", "professional accomplishment"]  
items:  
risk_categories: ["[[Psychosocial Risks]]"]  
work_modality: [remote, hybrid, telework, on-site]  
original_language: en  
access: restricted  
tags: []

---

# MBI-GS

## Description

Burnout assessment instrument, originally developed for health and human services professionals and later adapted for general use (General Survey). Assesses three dimensions: emotional exhaustion, depersonalization (cynicism), and professional accomplishment.

## Origin and development

Not reported in the extraction.

## What it measures

- Emotional exhaustion: feeling of physical and mental exhaustion
    
- Depersonalization (cynicism): emotional detachment and negative attitudes toward work
    
- Professional accomplishment: perception of competence and achievement at work
    
- Score in each dimension (no single total score)
    

## How it is applied

Self-administered questionnaire with Likert scales (usually 7 points, from "never" to "daily"). The full version has 22 items; the MBI-GS version has 16 items. Can be applied in person or online.

## Articles that used it

dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Monstadt et al. (2026)]]: Used to assess burnout in a German population-based study with supervised machine learning.
    

## Advantages and limitations

**Advantages:** Gold standard instrument for burnout, validated internationally, covers three dimensions, allows comparison between studies.

**Limitations:** Restricted access (requires license); does not capture all aspects of exhaustion; may overlap with depression.

## Applicability to SMEs and remote or hybrid work