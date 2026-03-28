---
title: README
type: note
permalink: obsidian/readme
---

# HFE + AuDHD Health Research Vault

Personal health research vault investigating the intersection of **HFE compound heterozygosity** (C282Y/H63D), **AuDHD** (ADHD-PI + Autism), and **Trichotillomania**. Built in [Obsidian](https://obsidian.md) and published as a [Digital Garden](https://dg-docs.ole.dev/) via Vercel.

> **Disclaimer:** This vault is for personal research and information-tracking. It does not constitute medical advice. All clinical decisions should be made with qualified healthcare professionals.

---

## Who This Is For

- People with **HFE compound heterozygosity** who've been told it's "clinically insignificant" but experience symptoms
- Adults with **late-diagnosed autism and/or ADHD** exploring iron metabolism connections
- Anyone interested in the **iron-dopamine-glutamate axis** and its role in neurodevelopmental conditions
- Researchers and clinicians looking for a cross-referenced evidence base connecting iron overload to neuropsychiatry

## The Core Question

> If HFE C282Y/H63D compound heterozygosity is "low risk," why does this patient present with iron overload (ferritin 738, TSAT 60%), neurodevelopmental conditions, fatigue, joint pain, and trichotillomania — and how are these connected?

## Patient Profile

- **Age:** 37 | **Conditions:** AuDHD (ADHD-PI + Autism, both diagnosed in adulthood), Trichotillomania (onset age 12), HFE C282Y/H63D compound heterozygote
- **Medication:** Elvanse (lisdexamfetamine) 70mg
- **Key labs (March 2026):** Ferritin 380 (down from 738), TSAT 60%, low-normal copper/zinc, HFE genotype confirmed

## What's In This Vault

### Research Notes (46 published)

Cross-referenced notes covering seven domains, each with inline PubMed citations, evidence ratings (A-D), and mermaid pathway diagrams:

| Domain | Notes | Key Topics |
|--------|-------|------------|
| **Genetics** | 3 | HFE compound het penetrance, disease associations beyond iron, genetic architecture of AuDHD (COMT, MTHFR, SLC6A3 overlap) |
| **Iron Metabolism** | 4 | NTBI toxicity, transferrin saturation thresholds, ceruloplasmin/ferroxidase, tryptophan-kynurenine pathway |
| **Neurodevelopment** | 8 | Iron-dopamine-ADHD axis, late-diagnosed autism subtypes, ADHD-PI internal hyperactivity, gut-brain axis, interoception, trichotillomania neurobiology |
| **Research** | 17 | Brain iron regulation (hepcidin, NTBI, ferroptosis), sleep as central amplifier, exercise prescription, NAC mechanisms, neurodegeneration risk, endocrine effects, pharmacogenomics |
| **Minerals** | 1 | Copper-zinc-iron competitive absorption and downstream effects |
| **Symptoms** | 2 | Multifactorial fatigue model, HFE arthropathy |
| **Clinical** | 4 | Diet strategy, supplement protocol, action plan, lab results |

### Key Findings

Findings verified against PubMed and OpenAlex (March 2026):

1. **Iron overload drives repetitive behaviour** — Chang 2014 showed HFE-model mice develop stereotyped behaviours via basal ganglia iron disruption
2. **H63D variant increases glutamate release** — Mitchell 2009 demonstrated H63D HFE cells show increased glutamate release, the same pathway targeted by NAC for trichotillomania
3. **Memantine 60.5% vs 8.3% for TTM** — Grant 2023 RCT (n=100) confirms glutamate hypothesis for BFRBs (NNT=1.9)
4. **Cross-disorder GWAS identifies shared architecture** — Grotzinger 2025 mapped 238 pleiotropic loci across 14 psychiatric disorders; ADHD and autism load onto shared factors
5. **Iron overload causes cognitive impairment via gut-brain axis** — Suparan 2024 (PMID 39438708) linked iron burden to gut/blood microbiome alterations and cognition
6. **No published study on stimulant-mediated autism unmasking** — identified evidence gap despite clinical recognition

### Visual Pathway Diagrams

Every research note includes a **mermaid flowchart** showing mechanistic pathways, with:
- Colour-coded nodes (foldable legend above each diagram)
- `flowchart` syntax for Digital Garden compatibility
- Solid lines for causal/pathological connections
- Dotted lines for protective/therapeutic connections

The main index splits the full system into three focused diagrams:
1. **Iron Overload Cascade** — HFE → five damage pathways → symptom endpoints
2. **Sleep as Central Amplifier** — vicious cycles radiating from poor sleep
3. **Interventions and Targets** — what helps and what it targets

## Vault Structure

```
health-research/
├── genetics/           # HFE, MTHFR, GWAS, pharmacogenomics
├── iron-metabolism/     # Iron pathways, NTBI, hepcidin, ferroptosis
├── neurodevelopment/    # ADHD, autism, TTM, interoception, dopamine
├── research/            # Deep-dive notes, intervention protocols
├── minerals/            # Copper, zinc, iron interactions
├── symptoms/            # Fatigue, pain, symptom analysis
├── lab-results/         # Annotated blood work
├── diet-management/     # Dietary strategy, supplement protocol
├── MOCs/                # Auto-generated indexes (not published)
├── Templates/           # Note templates (not published)
└── Daily/               # Daily logs (not published)
```

## Evidence Standards

- **A** — RCTs, meta-analyses, systematic reviews
- **B** — Single well-designed RCT or multiple controlled studies
- **C** — Pilot studies, open-label trials, strong observational evidence
- **D** — Expert opinion, case series, hypothesis-generating

All notes include inline citations with PMIDs linking to PubMed. Key journals referenced include *Nature Genetics*, *Blood*, *JAMA Psychiatry*, *Hepatology*, *Molecular Autism*, and EASL/BJH clinical guidelines.

## Entry Points

- **[Health Research MOC](https://research.principal-ms.co.uk/)** — main index with pathway diagrams
- **Action Items and Monitoring Plan** — clinical next steps
- **Diet and Supplement Strategy** — current protocol with evidence ratings
- **Research Avenues Tracker** — all 70 tracked research leads

## Current Stage

**Research + clinical preparation** — preparing for GP appointment (phlebotomy referral, endocrine testing, MTHFR genotyping). Continuing to build evidence base across sleep, exercise, interoception, and autonomic domains.

## Tech Stack

- **Obsidian** — note-taking and knowledge management
- **Digital Garden plugin** — publishes notes with `dg-publish: true` frontmatter
- **Vercel** — hosts the published garden
- **Mermaid** — pathway diagrams (flowchart syntax, classDef colour coding)

## Privacy

- No full surnames, DOB, NHS numbers, employer names, or contact details
- Patient identified as "Anthony G." or "Patient" only
- Raw uploaded files with PII are gitignored

## Contributing

This is a personal research vault, but if you spot errors in citations, have relevant research to suggest, or see broken links, feel free to open an issue.

## Licence

Content is shared for educational purposes. Academic citations remain the property of their respective authors and publishers.
