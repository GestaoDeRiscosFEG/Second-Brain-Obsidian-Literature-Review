type: tool  
name: "Patient Health Questionnaire-9"  
acronym: "PHQ-9"  
aliases: ["PHQ-9", "Patient Health Questionnaire-9", "PHQ-9 Item 9"]  
category: scale  
nature: validated  
remote_specific: false  
origin: not-reported  
original_reference: not-reported  
dimensions: ["depressive symptoms", "suicidal ideation (item 9)", "depression severity"]  
items: 9  
risk_categories: ["[[Psychosocial Risks]]"]  
work_modality: [remote, hybrid, telework, on-site]  
original_language: en  
access: open  
tags: []

---

# PHQ-9

## Description

Screening and severity assessment instrument for depressive symptoms, based on DSM-IV diagnostic criteria for major depressive episode. Item 9 specifically assesses suicidal ideation and self-harm.

## Origin and development

Developed by Kroenke, Spitzer, and Williams (2001). It is a version of PRIME-MD adapted for self-administration. Validated in several populations and contexts.

## What it measures

- 9 items corresponding to diagnostic criteria for major depression
    
- Frequency of symptoms in the last 2 weeks (scale 0 to 3)
    
- Total score from 0 to 27 (severity: minimal, mild, moderate, moderately severe, severe)
    
- Item 9: thoughts of death or self-harm (suicidal ideation screener)
    

## How it is applied

Self-administered questionnaire with 9 items on a 4-point Likert scale (0 = never to 3 = nearly every day). Can be applied in person or online.

## Articles that used it

dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Monstadt et al. (2026)]]: Used for mental health assessment in a German population-based study.
    
- [[Niedhammer et al. (2024)]]: Item 9 used to assess suicidal ideation in the last 14 days.
    

## Advantages and limitations

**Advantages:** Brief, low cost, validated, sensitive for screening, allows longitudinal follow-up.

**Limitations:** Does not replace clinical diagnosis; may overestimate or underestimate prevalence; does not capture all aspects of mental health.

## Applicability to SMEs and remote or hybrid work