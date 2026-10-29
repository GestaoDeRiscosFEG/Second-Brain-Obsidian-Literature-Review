type: tool  
name: "Rapid Health Impact Assessment"  
acronym: "HIA"  
aliases: ["HIA", "Rapid HIA", "Health Impact Assessment", "Rapid Health Impact Assessment", "Avaliação Rápida de Impacto na Saúde"]  
category: method  
nature: validated  
remote_specific: false  
origin: not-reported  
original_reference: not-reported  
dimensions: ["screening", "scoping", "appraisal", "reporting", "monitoring/evaluation"]  
items:  
risk_categories: ["[[Ergonomic Risks]]", "[[Physical Risks]]", "[[Psychosocial Risks]]", "[[Organizational Risks]]"]  
work_modality: [remote, hybrid, telework, on-site]  
original_language: en  
access: open  
tags: []

---

# HIA

## Description

Structured methodology to assess the potential effects of policies, programs, or organizational changes on population health. The rapid version is applied in crisis contexts, with short deadlines and limited resources.

## Origin and development

Not reported in the extraction.

## What it measures

- Screening: identify whether HIA is necessary
    
- Scoping: define what will be assessed
    
- Appraisal: identify and prioritize health effects
    
- Reporting: communicate results and recommendations
    
- Monitoring/Evaluation: follow up implementation and review recommendations
    

## How it is applied

Structured methodology in 5 steps. Can be applied to organizational changes (e.g., introduction of telework), health policies, or interventions. The rapid version prioritizes short-term effects and countermeasures.

## Articles that used it

dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Nagata et al. (2021)]]: Rapid HIA to assess the effects of emergency telework in Japan during the COVID-19 pandemic.
    

## Advantages and limitations

**Advantages:** Systematic approach, identifies positive and negative effects, guides countermeasures, applicable in crisis contexts.

**Limitations:** Rapid version may not capture all effects; requires expertise; depends on technical consensus.

## Applicability to SMEs and remote or hybrid work