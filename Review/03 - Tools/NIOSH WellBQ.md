type: tool  
name: "NIOSH Well-Being Questionnaire"  
acronym: "NIOSH WellBQ"  
aliases: ["WellBQ", "NIOSH WellBQ", "NIOSH Well-Being Questionnaire"]  
category: questionnaire  
nature: validated  
remote_specific: false  
origin: not-reported  
original_reference: not-reported  
dimensions: ["work evaluation", "work conditions", "workplace physical environment", "workplace psychosocial environment", "health status", "health behaviors", "life evaluation"]  
items: 63  
risk_categories: ["[[Psychosocial Risks]]", "[[Organizational Risks]]"]  
work_modality: [remote, hybrid, telework, on-site]  
original_language: en  
access: open  
tags: []

---

# NIOSH WellBQ

## Description

Comprehensive questionnaire developed by the National Institute of Occupational Safety and Health (NIOSH) to assess worker wellbeing. Covers multiple dimensions of wellbeing, including physical, mental, social, and work-related.

## Origin and development

Not reported in the extraction.

## What it measures

- Work evaluation
    
- Work conditions
    
- Workplace physical environment
    
- Workplace psychosocial environment
    
- Health status
    
- Health behaviors
    
- Life evaluation
    

## How it is applied

Self-administered questionnaire with multiple items on Likert scales. 63 items. Can be applied in person or online.

## Articles that used it

dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Paluszak et al. (2025)]]: Used as a wellbeing measure in a randomized controlled trial protocol.
    

## Advantages and limitations

**Advantages:** Comprehensive, validated, covers multiple dimensions, developed by a reference institution.

**Limitations:** Extensive (may take time to complete); does not capture all aspects of wellbeing; requires adaptation to specific contexts.

## Applicability to SMEs and remote or hybrid work