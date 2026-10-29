type: tool  
name: "Myotonometry"  
acronym: "MyotonPRO"  
aliases: ["MyotonPRO", "Myotonometry", "Miotonometria"]  
category: equipment  
nature: validated  
remote_specific: false  
origin: not-reported  
original_reference: not-reported  
dimensions: ["muscle stiffness", "muscle tone", "muscle elasticity"]  
items:  
risk_categories: ["[[Ergonomic Risks]]", "[[Physical Risks]]"]  
work_modality: [remote, hybrid, telework, on-site]  
original_language: en  
access: restricted  
tags: []

---

# MyotonPRO

## Description

Non-invasive digital biomechanical probe for measuring muscle stiffness, tone, and elasticity. Used in a randomized controlled trial protocol to assess muscle overload in remote and hybrid workers.

## Origin and development

Not reported in the extraction.

## What it measures

- Muscle stiffness
    
- Muscle tone
    
- Muscle elasticity
    

## How it is applied

Probe placed on the skin over the muscle of interest. Non-invasive, quick measurement.

## Articles that used it

dataview

TABLE year, temporal_context, company_size, study_type
FROM "Articles"
WHERE contains(tools, this.file.link)
SORT year DESC

## How it was used in the studies

- [[Paluszak et al. (2025)]]: Used for objective measurement of muscle stiffness and tone in a randomized controlled trial protocol.
    

## Advantages and limitations

**Advantages:** Non-invasive, quick, provides objective biomechanical data.

**Limitations:** Requires specialized equipment; high cost; operator-dependent.

## Applicability to SMEs and remote or hybrid work