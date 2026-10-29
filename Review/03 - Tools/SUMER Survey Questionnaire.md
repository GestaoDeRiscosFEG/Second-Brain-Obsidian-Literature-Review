type: tool  
name: "SUMER Survey Questionnaire"  
acronym: "SUMER"  
aliases: ["SUMER", "SUMER Survey", "SUMER Survey Questionnaire", "Questionário SUMER", "Enquête SUMER"]  
category: questionnaire  
nature: validated  
remote_specific: false  
origin: not-reported  
original_reference: not-reported  
dimensions: ["medical questionnaire", "self-administered work conditions questionnaire"]  
items:  
risk_categories: ["[[Psychosocial Risks]]", "[[Organizational Risks]]", "[[Physical Risks]]"]  
work_modality: [remote, telework, on-site]  
original_language: fr  
access: not-reported  
tags: []

---

# SUMER

## Description

National French survey protocol composed of a medical questionnaire and a self-administered work conditions questionnaire. Used to assess occupational exposures and their associations with health outcomes in a nationally representative sample of salaried workers in France.

## Origin and development

Not reported in the extraction. Conducted by DARES (Directorate for Research, Studies and Statistics of the French Ministry of Labour).

## What it measures

- Occupational exposures (psychosocial, physical, biomechanical, chemical, biological)
    
- Work conditions
    
- Health outcomes
    
- Medical data
    

## How it is applied

Composed of two parts: a medical questionnaire administered by an occupational physician and a self-administered work conditions questionnaire. Applied at the population level in France.

## Articles that used it

dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Niedhammer et al. (2024)]]: Used as the national French survey protocol to examine associations between psychosocial work exposures and suicidal ideation in a nationally representative sample of 25,977 employees.
    

## Advantages and limitations

**Advantages:** Nationally representative sample, comprehensive set of occupational exposures, combines medical and self-reported data.

**Limitations:** Specific to the French context; cross-sectional design; may not capture emerging risks (e.g., digital surveillance, telework-specific hazards).

## Applicability to SMEs and remote or hybrid work