---
dg-publish: true
type: research
status: active
date: 2026-03-28
tags:
  - elvanse
  - lisdexamfetamine
  - pharmacokinetics
  - iron-overload
  - CYP2D6
  - COMT
summary: How iron overload affects lisdexamfetamine metabolism via CYP2D6 impairment, COMT inhibition, oxidative stress synergy, and renal pH — with clinical implications for phlebotomy
permalink: research/elvanse-pharmacokinetics-and-iron-overload
---

# Elvanse Pharmacokinetics and Iron Overload

## Bottom Line

There are **no direct studies** examining lisdexamfetamine pharmacokinetics in iron-overloaded patients. However, converging evidence from hepatic iron toxicology, enzyme biochemistry, and amphetamine pharmacology identifies at least five plausible mechanistic pathways through which iron overload could alter Elvanse efficacy and safety. The strongest signals involve CYP450 impairment from hepatic iron, COMT inhibition by ferric iron (Fe3+), and additive oxidative stress. Phlebotomy to normalise iron indices may change how Elvanse is metabolised, warranting dose reassessment.

**Evidence grade: C–D** (mechanistic inference from animal/in vitro data; no human pharmacokinetic studies in this specific intersection)

---

## 1. Lisdexamfetamine Metabolism — The Normal Pathway

Lisdexamfetamine (LDX) is a prodrug consisting of d-amphetamine conjugated to L-lysine. Its metabolic route is distinctive and clinically important:

```
LDX (oral) → GI absorption (intact prodrug)
           → Red blood cell hydrolysis (rate-limiting)
           → d-Amphetamine + L-Lysine
           → d-Amphetamine distributes to CNS
           → Hepatic metabolism via CYP2D6 (4-hydroxylation)
           → Renal excretion (30% unchanged, pH-dependent)
```

### Key Pharmacokinetic Features

| Parameter | Detail | Source |
|-----------|--------|--------|
| Prodrug activation | RBC peptidase hydrolysis, not hepatic first-pass | Hutson et al. 2014 (PMID: 24594478) |
| Active metabolite | d-Amphetamine | Comiran et al. 2016 (PMID: 27125257) |
| Tmax d-amphetamine | ~3.5–4 hours (delayed vs IR d-amph) | Heal et al. 2013 (PMID: 23539642) |
| Hepatic metabolism | CYP2D6 catalyses 4-hydroxylation (minor pathway) | Bach et al. 1999 (PMID: 10456690) |
| Primary elimination | ~30% renal excretion as unchanged d-amphetamine | Comiran et al. 2016 (PMID: 27125257) |
| pH dependence | Alkaline urine decreases clearance; acidic urine increases it | Huang et al. 2020 (PMID: 32198137) |
| Half-life | ~10–12 hours for d-amphetamine | Kämmerer 2024 (PMID: 39024047) |

**Critical point**: Unlike most CNS drugs, LDX activation depends on **erythrocyte hydrolysis**, not hepatic CYP enzymes. This means iron overload's effect on hepatic function affects the **clearance** of d-amphetamine more than its **activation**. [Evidence: B]

> Hutson PH et al. "Preclinical pharmacokinetics, pharmacology and toxicology of lisdexamfetamine: a novel d-amphetamine pro-drug." *Neuropharmacology*. 2014;87:41-50. PMID: 24594478

> Comiran E et al. "Lisdexamfetamine: A pharmacokinetic review." *Eur J Pharm Sci*. 2016;89:172-9. PMID: 27125257

---

## 2. Does Iron Overload Affect CYP2D6 and Amphetamine Clearance?

### 2a. Iron-Induced CYP450 Damage — Animal Evidence

The most directly relevant evidence comes from Bacon et al. (1986), who demonstrated that chronic dietary iron overload in rats produced **dose-dependent reductions in hepatic cytochrome P450**:

- At moderate hepatic iron loading: no significant CYP450 change
- At high hepatic iron loading: **56% decrease in cytochrome P450 concentration** (p < 0.001)
- Mechanism: iron-catalysed microsomal lipid peroxidation destroying the haemoprotein
- Also observed: 47% increase in heme oxygenase activity (degrading CYP haem)

> Bacon BR et al. "Hepatic microsomal function in rats with chronic dietary iron overload." *Gastroenterology*. 1986;90(6):1844-53. PMID: 3009259 [Evidence: C — animal model, robust methodology]

### 2b. CYP1A2 Activity and Hepatic Iron — Human Evidence

The only human study directly examining CYP450 activity vs hepatic iron is Shteyer et al. (2015), conducted in beta-thalassemia major patients with transfusional iron overload:

- CYP1A2 activity **positively correlated** with plasma ferritin
- Patients with **low** CYP1A2 activity were significantly less likely to have hepatic iron accumulation (OR 0.047)
- This suggests a complex bidirectional relationship rather than simple inhibition

> Shteyer E et al. "Activity of cytochrome P450 1A2 in relation to hepatic iron accumulation in transfusion-dependent β-thalassaemia major patients." *Vox Sang*. 2015;108(3):268-73. PMID: 25471486 [Evidence: B — human study but different CYP isoform and population]

### 2c. Iron-Alcohol Synergy and CYP2E1

Stål et al. (1996) showed that iron overload alone did not significantly alter CYP2E1 levels, but the combination of iron + alcohol produced synergistic hepatotoxicity dependent on a "chelatable iron pool." This is relevant because it demonstrates that excess labile iron in the liver creates a redox-active environment that can damage microsomal function even if specific CYP isoform levels appear stable.

> Stål P et al. "Hepatotoxicity induced by iron overload and alcohol. Studies on the role of chelatable iron, cytochrome P450 2E1 and lipid peroxidation." *J Hepatol*. 1996;25(4):538-46. PMID: 8912154 [Evidence: C — animal model]

### 2d. Synthesis: What This Means for d-Amphetamine Clearance

D-amphetamine's hepatic metabolism via CYP2D6 is a **minor** clearance pathway — the majority is excreted renally unchanged. Therefore:

- Even if hepatic iron overload reduces CYP2D6 activity by 20–50% (extrapolating from the Bacon data), the impact on total d-amphetamine clearance would be **modest**
- The effect would be to **slightly prolong** d-amphetamine exposure and delay its elimination
- CYP2D6 poor metabolisers already tolerate amphetamine safely, suggesting this pathway has redundancy
- **Net prediction**: iron overload may produce a small increase in d-amphetamine AUC, unlikely to be clinically significant at Anthony's ferritin level (380) unless hepatic fibrosis is present

---

## 3. COMT, Iron, and Catecholamine Metabolism

This is potentially the most clinically significant interaction and the least studied in vivo.

### 3a. COMT Enzyme Biochemistry

Catechol-O-methyltransferase (COMT) degrades catecholamines (dopamine, norepinephrine, epinephrine) by methylation. The enzyme **requires a divalent metal cation** — normally Mg2+ — in its active site, plus S-adenosyl-L-methionine (SAM) as the methyl donor.

Sparta and Alexandrova (2012) used quantum mechanical / molecular mechanical modelling to determine how different metal ions affect COMT catalytic activity:

| Metal | COMT Activity | Mechanism |
|-------|---------------|-----------|
| **Mg2+** | Full activity (reference) | Optimal protein structure and electronic configuration |
| **Fe2+** | Slightly less potent than Mg2+ | Similar geometry, slightly different electronic effect |
| **Fe3+** | **Inhibitor** — unable to promote catalysis | Electronic effect prevents methyl transfer |
| **Ca2+** | **Complete deactivation** | Repacks protein binding site, raises activation barrier |

> Sparta M, Alexandrova AN. "How metal substitution affects the enzymatic activity of catechol-O-methyltransferase." *PLoS One*. 2012;7(10):e47172. PMID: 23056605 [Evidence: C — computational/in vitro, rigorous methodology]

### 3b. Iron Chelation Inhibits COMT In Vivo

Waldmeier et al. (1993) demonstrated that the oral iron chelator deferiprone (L1/CP20) **inhibited COMT in rat brain** with a threshold dose of ~1 mg/kg and ED50 of ~10 mg/kg. The mechanism was attributed to structural similarity between the chelator and catechol substrates, but the study also showed that iron chelation simultaneously inhibited tyrosine hydroxylase and tryptophan hydroxylase by coordinating to enzyme-bound iron.

This demonstrates that **manipulating brain iron availability directly affects catecholamine synthesis and degradation enzymes**.

> Waldmeier PC et al. "Inhibition of catechol-O-methyltransferase (COMT) as well as tyrosine and tryptophan hydroxylase by the orally active iron chelator, 1,2-dimethyl-3-hydroxypyridin-4-one (L1, CP20), in rat brain in vivo." *Biochem Pharmacol*. 1993;45(12):2417-24. PMID: 7687131 [Evidence: C — animal model]

### 3c. Clinical Implication: The Iron-COMT-Dopamine Hypothesis

In iron overload states, intracellular Fe3+ accumulates. Since Fe3+ **inhibits** COMT:

1. **Reduced COMT activity** → slower dopamine degradation → higher synaptic dopamine persistence
2. Elvanse (which increases synaptic dopamine via DAT reversal and vesicular release) would act in a context of **already-slowed dopamine clearance**
3. This could produce a **functionally enhanced stimulant effect** relative to someone with normal iron status
4. After phlebotomy normalises iron, COMT activity may increase → faster dopamine clearance → **perceived reduction in Elvanse efficacy**

This is speculative but mechanistically coherent. The planned COMT Val158Met genotyping will provide additional context — Val/Val (fast COMT) individuals might be partially protected from this effect, while Met/Met (slow COMT) individuals could be more vulnerable to additive inhibition.

---

## 4. Oxidative Stress: Amphetamine + Iron = Compounding Risk?

### 4a. Amphetamine-Induced Oxidative Stress

D-amphetamine increases dopamine release. Extracellular dopamine undergoes auto-oxidation, generating reactive oxygen species (ROS), quinones, and ultimately contributes to oxidative stress. At therapeutic doses this is modest, but the mechanism is well-established from methamphetamine neurotoxicity research:

- Methamphetamine-induced dopaminergic neurotoxicity involves peroxynitrite formation and iron-dependent ROS generation
- The iron chelator deferoxamine (DFO) **attenuated** methamphetamine-induced neurotoxicity in rats, confirming iron's role in the damage cascade
- DFO reduced lipid peroxidation, glutathione depletion, and dopamine/serotonin loss caused by methamphetamine

> Park MJ et al. "Effect of alpha-tocopherol and deferoxamine on methamphetamine-induced neurotoxicity." *Brain Res*. 2006;1109(1):176-82. PMID: 16844102 [Evidence: C — animal model, high methamphetamine doses]

> Imam SZ et al. "Methamphetamine-induced dopaminergic neurotoxicity: role of peroxynitrite and neuroprotective role of antioxidants." *Ann N Y Acad Sci*. 2001;914:366-78. PMID: 11462792 [Evidence: C — animal model]

### 4b. Iron Overload + Stimulant: Additive Oxidative Burden

The concern is straightforward:

```
Iron overload → ↑ Fenton reaction → ↑ baseline ROS
d-Amphetamine → ↑ DA release → ↑ DA auto-oxidation → ↑ additional ROS
Combined → Compounding oxidative stress in dopaminergic neurons
```

The brain is especially vulnerable because of its high oxygen consumption, abundant PUFAs, and limited antioxidant reserves (see [[Ferroptosis and Neuronal Iron]]).

**Important caveat**: Therapeutic d-amphetamine doses (Elvanse 70mg yields ~21mg d-amphetamine) produce far less dopamine efflux than the neurotoxic methamphetamine doses used in animal studies (typically 10 mg/kg x4). The clinical relevance at therapeutic doses is uncertain but represents a theoretical vulnerability worth monitoring. [Evidence: D — extrapolation from high-dose methamphetamine models]

### 4c. Protective Factors Already in Anthony's Protocol

Several elements of the current supplement regimen (see [[Diet and Supplement Strategy]]) provide oxidative stress defence:

- **NAC** (N-acetylcysteine) — replenishes glutathione, supports GPX4 anti-ferroptotic defence
- **Vitamin C** — antioxidant (though caution: can increase iron absorption)
- **Omega-3 fatty acids** — anti-inflammatory (though PUFAs are also ferroptosis substrates)
- **Phlebotomy** — directly reduces the iron pool driving Fenton chemistry

---

## 5. Amphetamine and Iron Homeostasis

### 5a. Iron-DAT Axis: Methamphetamine Alters Iron Distribution

A striking finding from Yan et al. (2022) demonstrated that iron homeostasis and dopamine transporter (DAT) regulation are linked through a mitochondrial pathway:

- Decreased striatal and hippocampal iron → increased DAT expression on cell membranes
- Iron depletion increased ferroportin 1 (FPN1) expression via HIF-1α
- Iron status directly influenced methamphetamine reward behaviours
- This suggests a **bidirectional relationship**: iron status affects dopamine transporter function, and stimulants may in turn affect iron distribution

> Yan PJ et al. "Dysregulation of iron homeostasis and methamphetamine reward behaviors in Clk1-deficient mice." *Acta Pharmacol Sin*. 2022;43(7):1686-1698. PMID: 34811513 [Evidence: C — animal model]

> Hempel B, Xi ZX. "Mitochondrial Clk1-iron-DAT regulation pathway: a possible new therapeutic target for methamphetamine use disorder." *Acta Pharmacol Sin*. 2022;43(8):1887-1888. PMID: 34873315 [Evidence: D — commentary]

### 5b. Does d-Amphetamine Affect Ferroportin or Iron Absorption?

No direct studies exist examining whether therapeutic d-amphetamine alters ferroportin expression, hepcidin levels, or intestinal iron absorption in humans. This remains an evidence gap. [Evidence: D — no data]

---

## 6. Urinary pH and Renal Amphetamine Clearance

### 6a. The pH Effect on Amphetamine

Amphetamine is a weak base (pKa ~9.9). In acidic urine, it becomes ionised and **cannot** be reabsorbed across renal tubular membranes, leading to rapid excretion. In alkaline urine, it remains un-ionised and is **reabsorbed**, prolonging its half-life.

Huang et al. (2020) modelled this using PBPK:
- Acidic urine (pH ~5): renal clearance of amphetamine increases dramatically
- Alkaline urine (pH ~8): renal clearance drops, AUC increases substantially
- The effect is clinically significant — urine pH can alter amphetamine half-life from ~7 hours (acidic) to ~20+ hours (alkaline)

> Huang W et al. "Mechanistic PBPK Modeling of Urine pH Effect on Renal and Systemic Disposition of Methamphetamine and Amphetamine." *J Pharmacol Exp Ther*. 2020;373(3):488-501. PMID: 32198137 [Evidence: B — validated PBPK model]

### 6b. Does Iron Overload Affect Urinary pH?

There is **no established direct link** between HFE-related iron overload and altered urinary pH. However, two indirect pathways exist:

1. **Renal tubular iron deposition** — severe iron overload can damage renal tubules (Fanconi syndrome reported in hemosiderosis, PMID: 19833423), potentially affecting acid-base handling
2. **Diet composition** — iron-avoidance diets tend to be plant-heavy and may alkalinise urine, which would slow amphetamine clearance and prolong effect

At Anthony's current ferritin (380) and TSAT (60%), significant renal tubular damage is unlikely. Dietary pH effects are more plausible but unquantified. [Evidence: D — theoretical]

---

## 7. What Changes After Phlebotomy?

Phlebotomy to reduce ferritin to target (<150 ug/L) could alter Elvanse pharmacokinetics through several mechanisms:

| Mechanism | Direction of Change | Confidence |
|-----------|-------------------|------------|
| Hepatic CYP450 recovery (less oxidative damage) | ↑ CYP2D6 activity → ↑ clearance → slightly shorter duration | Low |
| COMT recovery (less Fe3+ inhibition) | ↑ COMT activity → faster DA clearance → reduced net stimulant effect | Medium |
| Reduced baseline oxidative stress | ↓ ROS → improved neuronal resilience → possibly clearer cognitive effect | Medium |
| Normalised DAT regulation | Possible shift in DAT expression → altered stimulant response | Low |
| Improved hepatic synthetic function | Better protein binding, albumin levels → altered free drug fraction | Low |

**Clinical prediction**: After successful phlebotomy, Anthony may notice a **subtle reduction in Elvanse perceived effect duration or intensity**, not because the drug is less effective, but because COMT-mediated dopamine clearance normalises. This does not necessarily mean the dose needs increasing — it may mean the baseline dopamine system is functioning better.

---

## 8. Evidence Gaps and Research Needs

| Question | Current Evidence | Priority |
|----------|-----------------|----------|
| Does HFE iron overload alter CYP2D6 activity in humans? | None | High |
| Does therapeutic d-amphetamine affect hepcidin or ferroportin? | None | Medium |
| Does COMT Val158Met genotype interact with iron status to alter stimulant response? | None | High |
| Do iron-loaded patients metabolise amphetamines differently? | None | High |
| Does phlebotomy alter stimulant pharmacokinetics? | None | Medium |
| What is urinary pH in HFE compound hets on plant-rich diets? | None | Low |

---

## Clinical Relevance for Anthony

### Current Status
- **Elvanse 70mg** (maximum licensed dose)
- **Ferritin 380**, **TSAT 60%** — biochemical iron overload
- **HFE C282Y/H63D compound het** — chronic iron dysregulation
- **Planned**: CYP2D6 and COMT genotyping, phlebotomy

### Actionable Points

1. **No dose change needed now** — there is insufficient evidence that iron overload at this level meaningfully alters Elvanse pharmacokinetics. The drug's RBC-based activation pathway is likely unaffected.

2. **Monitor subjective efficacy around phlebotomy** — keep a simple log (1–10 scale) of Elvanse perceived effect, duration, and evening "wearing off" timing for 2 weeks before and 4 weeks after the first phlebotomy. If efficacy perception changes, this supports the COMT/CYP hypothesis and warrants discussion with prescriber.

3. **COMT genotyping is now higher priority** — if Anthony carries Met/Met (slow COMT), the additive effect of iron-mediated COMT inhibition could be clinically meaningful. Val/Val would provide reassurance of enzymatic redundancy.

4. **CYP2D6 genotyping** — if Anthony is a CYP2D6 poor metaboliser, the minor hepatic clearance pathway is already impaired. Adding iron-mediated CYP damage on top would compound this, though the clinical effect would still be modest given renal excretion predominance.

5. **Antioxidant strategy remains justified** — the theoretical additive oxidative stress from amphetamine + iron overload supports continuing NAC and maintaining adequate selenium, vitamin E, and glutathione precursors.

6. **Avoid unnecessary urinary alkalinisation** — sodium bicarbonate, excessive antacid use, or very high vegetable/low protein diets could prolong amphetamine exposure. Conversely, vitamin C (which Anthony takes) mildly acidifies urine and may slightly increase amphetamine clearance — a potential interaction worth noting.

7. **Reassess after phlebotomy series** — once ferritin is <150 and TSAT <45%, and pharmacogenomics results are available, a more informed assessment of Elvanse optimisation becomes possible. This may be 3–6 months away.

---

## Key References

1. Hutson PH et al. Preclinical pharmacokinetics of lisdexamfetamine. *Neuropharmacology*. 2014;87:41-50. PMID: 24594478
2. Comiran E et al. Lisdexamfetamine: A pharmacokinetic review. *Eur J Pharm Sci*. 2016;89:172-9. PMID: 27125257
3. Heal DJ et al. Amphetamine, past and present. *J Psychopharmacol*. 2013;27(6):479-96. PMID: 23539642
4. Kämmerer W. Comparative pharmacology of dexamphetamine and lisdexamfetamine. *Hum Psychopharmacol*. 2024;39(6):e2910. PMID: 39024047
5. Bach MV et al. Involvement of CYP2D6 in the metabolism of amphetamine. *Xenobiotica*. 1999;29(7):719-32. PMID: 10456690
6. Bacon BR et al. Hepatic microsomal function in rats with chronic dietary iron overload. *Gastroenterology*. 1986;90(6):1844-53. PMID: 3009259
7. Shteyer E et al. CYP1A2 activity and hepatic iron in thalassaemia. *Vox Sang*. 2015;108(3):268-73. PMID: 25471486
8. Stål P et al. Hepatotoxicity induced by iron overload and alcohol. *J Hepatol*. 1996;25(4):538-46. PMID: 8912154
9. Sparta M, Alexandrova AN. How metal substitution affects COMT activity. *PLoS One*. 2012;7(10):e47172. PMID: 23056605
10. Waldmeier PC et al. Iron chelator inhibits COMT, tyrosine and tryptophan hydroxylase in vivo. *Biochem Pharmacol*. 1993;45(12):2417-24. PMID: 7687131
11. Huang W et al. PBPK modeling of urine pH effect on amphetamine disposition. *J Pharmacol Exp Ther*. 2020;373(3):488-501. PMID: 32198137
12. Park MJ et al. Deferoxamine attenuates methamphetamine neurotoxicity. *Brain Res*. 2006;1109(1):176-82. PMID: 16844102
13. Imam SZ et al. Methamphetamine-induced dopaminergic neurotoxicity. *Ann N Y Acad Sci*. 2001;914:366-78. PMID: 11462792
14. Yan PJ et al. Iron homeostasis and methamphetamine reward in Clk1-deficient mice. *Acta Pharmacol Sin*. 2022;43(7):1686-1698. PMID: 34811513
15. Hempel B, Xi ZX. Clk1-iron-DAT regulation pathway. *Acta Pharmacol Sin*. 2022;43(8):1887-1888. PMID: 34873315

---

## Cross-References

- [[Iron-Dopamine-ADHD Axis]]
- [[Elvanse and Mineral Metabolism]]
- [[Ferroptosis and Neuronal Iron]]
- [[Iron Overload and NTBI]]
- [[Iron and Oxidative Stress in Autism]]
- [[Diet and Supplement Strategy]]
- [[UK Testing Guide - Pharmacogenomics and Endocrine]]
- [[Action Items and Monitoring Plan]]
- [[Copper-Iron-Dopamine Triangle]]
- [[HFE Compound Heterozygosity]]
- [[Blood Results - March 2026]]
