type: tool  
name: "Job Content Questionnaire"  
acronym: "JCQ"  
aliases: ["JCQ", "Job Content Questionnaire"]  
category: questionnaire  
nature: validated  
remote_specific: false  
origin: "Karasek et al. (1998)"  
original_reference: not-reported  
dimensions: ["psychological demand", "decision latitude", "social support"]  
items:  
risk_categories: ["[[Psychosocial Risks]]", "[[Organizational Risks]]"]  
work_modality: [remote, hybrid, telework, on-site]  
original_language: en  
access: open  
tags: []

---

# JCQ

## Description

Questionnaire based on Karasek's Demand-Control Model, one of the most influential theoretical models in occupational stress research. Assesses the interaction between psychological demands of work and decision latitude (control), in addition to social support from supervisors and colleagues.

## Origin and development

Developed by Karasek et al. (1998). The French version was validated by Niedhammer (2002). Widely used in epidemiological occupational health studies in several countries.

## What it measures

- Psychological demand: mental load, time pressure, work volume
    
- Decision latitude (control): autonomy, skill use, decision authority
    
- Social support: support from supervisors and colleagues
    
- Job strain (high demand): combination of high demand and low control
    
- Iso-strain: combination of high demand and low social support
    

## How it is applied

Self-administered questionnaire with Likert scales (usually 4 points). The full version has about 49 items, but short versions exist. Can be applied in person or online.

## Articles that used it

dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Cropley et al. (2023)]]: Work autonomy scale (3 items adapted from the JCQ) used to assess autonomy in remote workers.
    
- [[Niedhammer et al. (2024)]]: JCQ used to measure psychological demand, decision latitude, and social support in the French SUMER study.
    

## Advantages and limitations

**Advantages:** Solid theoretical basis, validated in several contexts, allows international comparison, identifies risk groups.

**Limitations:** Short versions may lose sensitivity; does not capture emerging risks (e.g., technostress, digital surveillance); requires adaptation for remote work contexts.

## Applicability to SMEs and remote or hybrid work