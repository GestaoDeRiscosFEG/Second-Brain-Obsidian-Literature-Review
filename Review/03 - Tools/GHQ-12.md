type: tool  
name: "General Health Questionnaire - 12 items"  
acronym: "GHQ-12"  
aliases: ["GHQ-12", "General Health Questionnaire", "GHQ"]  
category: scale  
nature: validated  
remote_specific: false  
origin: not-reported  
original_reference: not-reported  
dimensions: ["psychological distress", "general mental health"]  
items: 12  
risk_categories: ["[[Psychosocial Risks]]"]  
work_modality: [remote, hybrid, telework, on-site]  
original_language: en  
access: open  
tags: []

---

# GHQ-12

## Description

Screening instrument for psychological distress and general mental health. The 12-item version is widely used in occupational health research to detect minor psychiatric disorders.

## Origin and development

Not reported in the extraction.

## What it measures

- Psychological distress
    
- General mental health
    
- Symptoms of anxiety and depression
    
- Social dysfunction
    

## How it is applied

Self-administered questionnaire with 12 items. Takes about 3 to 5 minutes. Can be applied in person or online.

## Articles that used it

dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Biggs et al. (2025)]]: Used to assess psychological distress in construction workers before and after a holistic psychosocial intervention.
    

## Advantages and limitations

**Advantages:** Brief, validated, widely used, allows comparison between studies.

**Limitations:** Does not replace clinical diagnosis; may not capture specific occupational stressors; does not distinguish between anxiety and depression.

## Applicability to SMEs and remote or hybrid work