# Clinical AI Pattern Catalogue

**7 design patterns that determine whether your Clinical AI survives deployment.**

---

## The Problem

Most clinical AI systems are evaluated on metrics that cannot detect their most dangerous failure mode. Accuracy, F1, and AUC measure statistical performance against a dataset. They do not measure whether the dataset itself faithfully represents clinical reality.

In healthcare, data is shaped by billing incentives, documentation templates, coding guidelines, and institutional workflows before it ever reaches a model. A billing code is not a diagnosis. An administrative category is not a clinical observation. A reimbursement-optimized record is not a faithful representation of what happened to a patient.

We call this **ontological distortion**: the systematic divergence between the categories in your training data and the clinical phenomena they claim to represent. Standard ML evaluation cannot detect it. But it determines whether your system will work in deployment.

## What This Catalogue Provides

This catalogue documents seven architectural patterns that address ontological distortion at the infrastructure level. Each pattern is:

- **Research-backed**: derived from 12 peer-reviewed publications across 22 disciplines
- **Architecturally concrete**: includes data flow diagrams and implementation sketches
- **Independently assessable**: mapped to the [Ontological Fidelity Scorecard](https://1977flow.github.io/odix8-scorecard/)

## Quick Links

| Resource | Description |
|----------|-------------|
| [The 7 Patterns](patterns/index.md) | Full pattern documentation with diagrams |
| [Scorecard](scorecard.md) | Self-assess your system in 5 minutes |
| [Research](research.md) | The 12-paper corpus behind this catalogue |
| [Roadmap](roadmap.md) | Open-source tools implementing these patterns |

---

## About oDIX8

**oDIX8 | Systems for Innovation** identifies why Clinical AI fails before you deploy it. Our work sits at the intersection of clinical medicine, information systems, and AI governance.

Based in Halle (Germany) and London (UK).

[www.odix8.com](https://www.odix8.com) | [office@odix8.com](mailto:office@odix8.com)
