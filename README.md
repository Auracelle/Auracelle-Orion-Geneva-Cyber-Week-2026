# Auracelle Orion v4 · Geneva Cyber Week 2026

**Cyber Governance Wargaming Simulation**  
Auracelle AI Governance Labs · E-AGPO-HT v2.0 Framework  
Presented at Geneva Cyber Week · May 2026 · CICG Geneva

---

## Overview

Auracelle Orion is a turn-based cyber governance wargaming simulation that stress-tests policy decisions across realistic supply chain and nuclear cybersecurity attack scenarios. Each 5-turn scenario compresses a full incident lifecycle — from initial threat entry through governance consolidation — into a structured decision environment that quantifies the quality of governance choices using the **Evans-Accelerated Governance Policy Optimization-Hierarchical Theory (E-AGPO-HT) v2.0** framework.

This repository hosts the Geneva Cyber Week 2026 conference edition of Auracelle Orion, customised for the cyber stability and multilateral governance context of GCW.

**Live Demo:** [https://auracelle.github.io/Auracelle-Orion-Geneva-Cyber-Week-2026/](https://auracelle.github.io/Auracelle-Orion-Geneva-Cyber-Week-2026/)

---

## Scenarios

### AI Cybersecurity Domain

| Scenario | Class | Primary Stressors |
|---|---|---|
| **MIRAGE CHAIN** | SolarWinds-class | SC-SBOM, SC-CONC, IFD/SWD |
| **IRONCLAD SIEGE** | Industroyer-class | SC-GREY, HW-PROV, SC-PATCH |
| **FRACTURE POINT** | XZ Utils-class | SC-SBOM, Q_coord, DEP-TRST |
| **PHANTOM CIRCUIT** | Nation-state implant | SC-GREY, HW-BOM, Attribution |

### Nuclear Cybersecurity Domain

| Scenario | Class | Primary Stressors |
|---|---|---|
| **SAFEGUARD ZERO** | IAEA Safeguards-class | NUC-VERIFY, IFD-SCADA, IAEA-COORD |
| **FISSION GATE** | Stuxnet-class | NUC-CTRL, SC-GREY, OT-ENRICH |
| **YELLOWCAKE RUN** | Supply-chain mineral attack | SC-PROVENANCE, IAEA-ITDB, CHAIN-AUTH |

---

## Framework

Auracelle Orion implements the **E-AGPO-HT v2.0** framework across a three-stratum architecture:

- **Stratum III** — Master g-GCC governance score with nonlinear λ cross-domain coupling
- **Stratum II** — Seven Behavioural Governance Capacity dimensions (IFD, SWD, SCTL, GOV, and domain-specific stressors)
- **Stratum I** — ~40 Normative Operational Factors (NOFs) including SBOM-VIS, SC-GREY, SC-CONC, PATCH-VEL, NUC-VERIFY

Decision quality is measured by **Ψ_v2**, a composite scoring function:

```
Ψ_v2 = 0.30·Q_timing + 0.25·Q_coord + 0.15·Q_norm + 0.20·Q_sctl + 0.10·Q_acc + 0.05·Q_domain_sep
```

---

## Gameplay

Each scenario runs across **5 turns**, each comprising four phases:

1. **Intel Phase** — Spend up to 3 intelligence tokens to reveal hidden observables before deciding
2. **Decision Phase** — Choose from 4 governance response options, each with explicit trade-off tags
3. **Consequence Phase** — Domain scores update; cascade probability calculated; After-Action log populated
4. **After-Action Review** — Full Ψ_v2 breakdown, decision history, and governance legacy score

---

## Governance Domains Covered

- Supply chain integrity (SBOM, HHI concentration, grey-market hardware)
- Nuclear facility cybersecurity (safeguards monitoring, OT/ICS enrichment systems, material transport)
- Regulatory compliance (NIS2, EO 14028, CISA KEV, EU CRA, IAEA CSA/Additional Protocol)
- Multilateral coordination (CSIRT, NATO, IAEA Board of Governors, UNSC)
- Attribution and diplomatic response (nation-state APT, treaty obligations, NPT frameworks)

---

## Intellectual Property

© 2013–2026 Grace-Alice Evans · Auracelle AI Governance Labs  
All rights reserved. Proprietary simulation framework — E-AGPO-HT v2.0.

The Evans-Accelerated Governance Policy Optimization-Hierarchical Theory (E-AGPO-HT) is proprietary intellectual property of Grace-Alice Evans and Auracelle AI Governance Labs. Reproduction, adaptation, or commercial use of the framework, scenario architecture, or scoring methodology requires written authorisation.

**Presented at:** Geneva Cyber Week 2026 · CICG Geneva · May 2026  
**Submitted to:** UNIDIR AISE26 · June 2026 · Geneva  
**Affiliation:** UC Berkeley Center for Long-Term Cybersecurity (CLTC) · Non-Resident Senior Fellow  
**NATO:** STO SAS-219 · Technical Role Member

---

## Contact

**Grace-Alice Evans**  
Founder & Principal Investigator, Auracelle AI Governance Labs  
Non-Resident Senior Fellow, UC Berkeley CLTC  
Technical Role Member, NATO STO SAS-219  

[Auracelle AI Governance Labs](https://auracelle.github.io)
