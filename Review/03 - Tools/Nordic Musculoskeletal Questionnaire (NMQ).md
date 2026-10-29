type: tool  
name: "Nordic Musculoskeletal Questionnaire"  
acronym: "NMQ"  
aliases: ["NMQ", "Nordic Musculoskeletal Questionnaire", "Standardized Nordic Questionnaire", "SNQ", "Kuorinka Questionnaire"]  
category: questionnaire  
nature: validated  
remote_specific: false  
origin: "Kuorinka et al. (1987)"  
original_reference: not-reported  
dimensions: ["musculoskeletal symptoms", "9 anatomical regions", "frequency", "intensity"]  
items:  
risk_categories: ["[[Ergonomic Risks]]", "[[Physical Risks]]"]  
work_modality: [remote, hybrid, telework, on-site]  
original_language: en  
access: open  
tags: []
## Description

Standardized questionnaire to identify musculoskeletal symptoms in different anatomical regions. One of the most used instruments in ergonomics and occupational health for screening MSDs and RSIs. Can be self-administered or applied by interview.

## Origin and development

Developed by Kuorinka et al. (1987). The original version covers 9 anatomical regions: neck, shoulders, elbows, wrists/hands, upper back, lower back, hips/thighs, knees, and ankles/feet. Adapted and modified versions exist, such as the Standardized Kuorinka Modified Nordic Questionnaire (SNQ).

## What it measures

- Presence of musculoskeletal symptoms in the last 12 months
    
- Presence of symptoms in the last 7 days
    
- Functional disability resulting from symptoms
    
- Frequency and intensity of pain (in some versions)
    
- 9 anatomical regions (original version)
    

## How it is applied

Usually as a self-administered questionnaire with binary questions (Yes/No) or frequency/intensity scales. Can be adapted to compare periods (before/during) or contexts (on-site/remote). Number of items varies by version: not reported in the studies.

## Articles that used it

dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Ahmed et al. (2022)]]: Adapted 17-item survey assessing anatomical pain prevalence, postural discomfort, temporal working patterns, and environmental workspace conditions.
    
- [[Fouquet et al. (2025)]]: Binary question inspired by the Nordic Questionnaire to assess low back pain before and at the end of lockdown.
    
- [[Paluszak et al. (2025)]]: NMQ with Polish adaptation by CIOP-PIB in a randomized controlled trial protocol.
    
- [[Rodríguez-Nogueira et al. (2021)]]: SNQ adapted to Spanish to compare pain in 9 body regions before and during lockdown.
    
- [[Wada et al. (2025)]]: Used as part of the TELEWORK study protocol for Japanese teleworkers.
    

## Advantages and limitations

**Advantages:** Validated instrument, low cost, easy application, allows comparison between studies and contexts.

**Limitations:** Self-report, may have recall bias; does not replace clinical assessment; adapted versions may compromise comparability.

## Applicability to SMEs and remote or hybrid work