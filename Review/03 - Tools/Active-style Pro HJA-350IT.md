type: tool  
name: "Active-style Pro HJA-350IT"  
acronym: "Active-style Pro HJA-350IT"  
aliases: ["Active-style Pro HJA-350IT", "Omron Active-style", "HJA-350IT"]  
category: equipment  
nature: validated  
remote_specific: false  
origin: not-reported  
original_reference: not-reported  
dimensions: ["steps", "sedentary time", "physical activity intensity"]  
items:  
risk_categories: ["[[Ergonomic Risks]]", "[[Physical Risks]]"]  
work_modality: [remote, telework, on-site]  
original_language: en  
access: restricted  
tags: []

---

# Active-style Pro HJA-350IT

## Description

Triaxial accelerometer calibrated for continuous recording of steps, sedentary time (below 1.5 METs), and physical activity intensity. Used in the TELEWORK study protocol for Japanese teleworkers.

## Origin and development

Not reported in the extraction. Manufactured by Omron.

## What it measures

- Number of steps
    
- Sedentary time (below 1.5 METs)
    
- Physical activity intensity
    

## How it is applied

Worn by the worker for 14 consecutive days. Provides objective and continuous measurement.

## Articles that used it

```dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Wada et al. (2025)]]: Used for objective measurement of steps, sedentary time, and physical activity intensity over 14 days in a cluster randomized controlled trial protocol.
    

## Advantages and limitations

**Advantages:** Objective measurement, continuous recording, validated device.

**Limitations:** Requires equipment; may not capture all types of activity; adherence dependent.

## Applicability to SMEs and remote or hybrid work