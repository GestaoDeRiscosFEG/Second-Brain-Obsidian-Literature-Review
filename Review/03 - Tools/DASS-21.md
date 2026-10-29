type: tool  
name: "Depression Anxiety Stress Scales - 21 items"  
acronym: "DASS-21"  
aliases: ["DASS-21", "DASS", "Depression Anxiety Stress Scales"]  
category: scale  
nature: validated  
remote_specific: false  
origin: not-reported  
original_reference: not-reported  
dimensions: ["depression", "anxiety", "stress"]  
items: 21  
risk_categories: ["[[Psychosocial Risks]]"]  
work_modality: [remote, hybrid, telework, on-site]  
original_language: en  
access: open  
tags: []

---

# DASS-21

## Description

Set of three self-report scales to measure negative emotional states: depression, anxiety, and stress. The short version (DASS-21) has 21 items and is the most used in occupational contexts due to its brevity.

## Origin and development

Not reported in the extraction.

## What it measures

- Depression: depressed mood, hopelessness, devaluation of life
    
- Anxiety: autonomic arousal, fear, panic
    
- Stress: tension, irritability, difficulty relaxing
    
- Separate score for each subscale
    

## How it is applied

4-point Likert scale (0 = did not apply to me at all to 3 = applied to me very much or most of the time). The DASS-21 takes about 5 to 10 minutes. Can be applied in person or online.

## Articles that used it

```dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Andel et al. (2021)]]: Depression subscale (7 items) used to assess weekly depressive symptoms.
    

## Advantages and limitations

**Advantages:** Assesses three dimensions separately, validated, short version available, allows longitudinal follow-up.

**Limitations:** Does not replace clinical diagnosis; may overlap between subscales; does not capture all aspects of mental health.

## Applicability to SMEs and remote or hybrid work