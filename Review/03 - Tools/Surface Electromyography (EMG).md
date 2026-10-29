type: tool  
name: "Surface Electromyography"  
acronym: "EMG"  
aliases: ["EMG", "Surface Electromyography", "Electromyography", "Noraxon Telemyo MyoTrace 400"]  
category: equipment  
nature: validated  
remote_specific: false  
origin: not-reported  
original_reference: not-reported  
dimensions: ["trapezius muscle activity", "erector spinae muscle activity", "muscle fatigue"]  
items:  
risk_categories: ["[[Ergonomic Risks]]", "[[Physical Risks]]"]  
work_modality: [remote, hybrid, telework, on-site]  
original_language: en  
access: restricted  
tags: []

---

# EMG

## Description

Surface electromyography equipment for objective measurement of muscle activity and fatigue. The Noraxon Telemyo MyoTrace 400 with Biodex System 4 Pro was used to measure trapezius and erector spinae muscle fatigue during physical activity interventions.

## Origin and development

Not reported in the extraction.

## What it measures

- Trapezius muscle activity
    
- Erector spinae muscle activity
    
- Muscle fatigue
    

## How it is applied

Surface electrodes placed on the skin over the muscles of interest. Measurements taken during specific tasks or exercises.

## Articles that used it

dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Paluszak et al. (2025)]]: Used for objective measurement of muscle fatigue in a randomized controlled trial protocol on physical activity for remote and hybrid workers.
    

## Advantages and limitations

**Advantages:** Objective measurement, complements self-report, allows precise analysis.

**Limitations:** Requires specialized equipment; high cost; may be uncomfortable for workers.

## Applicability to SMEs and remote or hybrid work