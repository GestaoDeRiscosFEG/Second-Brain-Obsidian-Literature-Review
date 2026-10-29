type: tool  
name: "Brief Job Stress Questionnaire"  
acronym: "BJSQ"  
aliases: ["BJSQ", "Brief Job Stress Questionnaire"]  
category: questionnaire  
nature: validated  
remote_specific: false  
origin: not-reported  
original_reference: not-reported  
dimensions: ["job stressors", "stress reactions", "social support", "job satisfaction"]  
items: 57  
risk_categories: ["[[Psychosocial Risks]]", "[[Organizational Risks]]"]  
work_modality: [remote, hybrid, telework, on-site]  
original_language: ja  
access: open  
tags: []

---

# BJSQ

## Description

Standardized Japanese questionnaire for occupational stress assessment, developed to evaluate job stressors, stress reactions, social support, and job satisfaction. Widely used in Japanese workplaces for mental health screening.

## Origin and development

Not reported in the extraction.

## What it measures

- Job stressors
    
- Stress reactions
    
- Social support
    
- Job satisfaction
    

## How it is applied

Self-administered questionnaire with 57 items. Takes about 10 to 15 minutes. Can be applied in person or online.

## Articles that used it

```dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Wada et al. (2025)]]: Used to assess occupational stress in Japanese teleworkers as part of the TELEWORK study protocol.
    

## Advantages and limitations

**Advantages:** Validated, comprehensive, widely used in Japan.

**Limitations:** Developed for the Japanese context; long version may be burdensome; requires adaptation for other cultures.

## Applicability to SMEs and remote or hybrid work