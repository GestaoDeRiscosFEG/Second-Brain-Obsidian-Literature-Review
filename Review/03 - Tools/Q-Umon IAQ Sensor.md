type: tool  
name: "Q-Umon IAQ Sensor"  
acronym: "Q-Umon IAQ Sensor"  
aliases: ["Q-Umon", "Q-Umon IAQ", "Indoor Air Quality Sensor"]  
category: equipment  
nature: validated  
remote_specific: false  
origin: not-reported  
original_reference: not-reported  
dimensions: ["CO2", "temperature", "humidity"]  
items:  
risk_categories: ["[[Physical Risks]]", "[[Ergonomic Risks]]"]  
work_modality: [remote, telework, on-site]  
original_language: en  
access: not-reported  
tags: []

---

# Q-Umon IAQ Sensor

## Description

IoT station for continuous monitoring of indoor air quality, including CO2, temperature, and humidity. Used in the TELEWORK study protocol for Japanese teleworkers.

## Origin and development

Not reported in the extraction.

## What it measures

- CO2 concentration
    
- Temperature
    
- Humidity
    

## How it is applied

Continuous monitoring at intervals (e.g., every 10 minutes) at the home or office workstation.

## Articles that used it

dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Wada et al. (2025)]]: Used for objective measurement of indoor air quality at the home workstation.
    

## Advantages and limitations

**Advantages:** Objective environmental measurement, continuous monitoring.

**Limitations:** Requires equipment; measures only environmental parameters, not health outcomes directly.

## Applicability to SMEs and remote or hybrid work