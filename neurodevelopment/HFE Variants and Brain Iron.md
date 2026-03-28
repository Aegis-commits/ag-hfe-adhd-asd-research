---
dg-publish: true

date: 2026-03-17
type: research
status: active
tags:
- HFE
- brain-iron
- C282Y
- H63D
- cognition
- neurobiology
summary: HFE variant effects on CNS iron distribution, cognitive outcomes, and neurodegeneration pathways
aliases:
- Brain Iron and HFE
permalink: neurodevelopment/hfe-variants-and-brain-iron
---

# HFE Variants and Brain Iron

## Key Point
HFE variants are not just liver/iron-panel variants. They can influence brain iron distribution and neurobiology.

## Pathway Overview

> [!info]- Colour Key
> 🟤 HFE | 🔵 Brain region | 🟣 Effect | ⚫ Outcome

```mermaid
flowchart TD
    A[HFE C282Y/H63D] --> B[Altered Brain Iron Handling]
    B --> C[Regional Iron Accumulation]

    C --> D[Basal Ganglia]
    C --> E[Substantia Nigra]

    D --> F[Dopamine Dysregulation]
    E --> F

    B --> G[Impaired Myelination]
    B --> H[Oxidative Stress]

    H --> I[ROS Generation]
    I --> J[Neuronal Vulnerability]

    F --> K[ADHD Symptoms]
    G --> L[Cognitive Effects]
    J --> L

    classDef hfe fill:#d2b4de,stroke:#7d3c98,color:#1a0422
    classDef region fill:#85c1e9,stroke:#2471a3,color:#0a1929
    classDef effect fill:#d7bde2,stroke:#8e44ad,color:#1a0422
    classDef outcome fill:#f7dc6f,stroke:#b7950b,color:#1a1400

    class A,B hfe
    class C,D,E region
    class F,G,H,I,J effect
    class K,L outcome
```

## Evidence
- Kalpouzos G et al. *Neuropsychopharmacol Rep* 2021;41(3):393-404 (PMC8411306)
  - C282Y and/or H63D carriage associated with altered blood and brain iron measures
  - Associations with cognitive/motor outcomes examined in healthy adults

- Connor JR. PMID: 21346098
  - HFE variants linked to altered brain iron handling and oxidative stress models

- Kim Y, Connor JR. *Mol Aspects Med* 2020;75:100867
  - HFE genotype modifies mechanisms and presentation across neurological conditions

- Marshall Moscon SL, Connor JR. *Int J Mol Sci* 2024;25(6):3334
  - Review on HFE mutations in neurodegeneration and hormesis framework

## Relevance To Your Context
Your C282Y/H63D genotype plus ADHD/autism and fatigue may involve overlapping pathways:
- peripheral iron loading tendency
- potential CNS iron-handling differences
- oxidative stress vulnerability

This is hypothesis-generating and should not be over-interpreted clinically without targeted imaging/neurology context.

## Cross-References
- [[HFE Compound Heterozygosity]]
- [[Iron-Dopamine-ADHD Axis]]
- [[Fatigue and Burnout]]
