type: tool  
name: "Work Productivity and Activity Impairment Questionnaire"  
acronym: "WPAI"  
aliases: ["WPAI", "Work Productivity and Activity Impairment", "WPAI Questionnaire"]  
category: questionnaire  
nature: validated  
remote_specific: false  
origin: not-reported  
original_reference: not-reported  
dimensions: ["absenteeism", "presenteeism", "work productivity", "daily activity impairment"]  
items: 6  
risk_categories: ["[[Psychosocial Risks]]", "[[Organizational Risks]]"]  
work_modality: [remote, hybrid, telework, on-site]  
original_language: en  
access: open  
tags: []

---

# WPAI

## Description

Questionnaire to assess the impact of health problems on work productivity and daily activities. Assesses absenteeism (lost days), presenteeism (reduced productivity at work), and impairment in regular activities.

## Origin and development

Not reported in the extraction.

## What it measures

- Absenteeism: work hours lost due to health problems
    
- Presenteeism: reduced productivity at work due to health problems
    
- Impairment in regular activities: impact on non-work daily activities
    
- Score expressed as percentages of impairment
    

## How it is applied

Self-administered questionnaire with 6 items. Takes about 2 to 3 minutes. Can be applied in person or online.

## Articles that used it

dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Wada et al. (2025)]]: Used as a presenteeism measure in a cluster randomized controlled trial protocol.
    

## Advantages and limitations

**Advantages:** Brief, validated, quantifies the economic impact of health problems, allows cost calculation.

**Limitations:** Self-report; may have recall bias; does not capture all aspects of productivity.

## Applicability to SMEs and remote or hybrid work