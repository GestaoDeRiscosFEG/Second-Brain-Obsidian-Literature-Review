type: tool  
name: "Hospital Anxiety and Depression Scale"  
acronym: "HADS"  
aliases: ["HADS", "HAD", "Hospital Anxiety and Depression Scale"]  
category: scale  
nature: validated  
remote_specific: false  
origin: not-reported  
original_reference: not-reported  
dimensions: ["anxiety", "depression"]  
items: 14  
risk_categories: ["[[Psychosocial Risks]]"]  
work_modality: [remote, hybrid, telework, on-site]  
original_language: en  
access: open  
tags: []

---

# HADS

## Description

Screening scale for anxiety and depression symptoms, originally developed for hospital settings but widely used in research and occupational health. Avoids somatic items that could be confused with physical illness.

## Origin and development

Developed by Zigmond and Snaith (1983). The French version was validated by Boini and Langevin (2020). Used by Fouquet et al. (2025) to assess depressive symptomatology in teleworkers.

## What it measures

- Anxiety subscale: 7 items
    
- Depression subscale: 7 items
    
- Separate score for each subscale (0 to 21)
    
- Indicates levels of anxiety and depression (normal, mild, moderate, severe)
    

## How it is applied

4-point Likert scale. The full version has 14 items (7 anxiety plus 7 depression). Takes about 5 minutes. Can be applied in person or online.

## Articles that used it

dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Fouquet et al. (2025)]]: Depression subscale used to assess depressive symptomatology in teleworkers during lockdown in France.
    

## Advantages and limitations

**Advantages:** Brief, validated, avoids somatic items, allows separate assessment of anxiety and depression.

**Limitations:** Does not replace clinical diagnosis; may overlap with other scales; does not capture all aspects of mental health.

## Applicability to SMEs and remote or hybrid work