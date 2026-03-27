# Tooling Roadmap

Open-source tools that implement the 7 design patterns.

---

!!! info "Development Status"
    These tools are in active development. Star the [repository](https://github.com/1977Flow/clinical-ai-pattern-catalogue) to get notified when they ship.

## Planned Tools

| Tool | Pattern(s) | Description | Target |
|------|-----------|-------------|--------|
| `ontological-checkpoint` | 1. Coding-Fidelity | Python library that annotates health records with a coding-fidelity score at ingestion | Q2 2026 |
| `drift-sentinel` | 3. Semantic Drift | Monitoring service that detects and classifies semantic drift in clinical coding data | Q2 2026 |
| `reification-circuit-breaker` | 5. Feedback Loop | Pipeline middleware that tracks AI influence ratio and pauses retraining when threshold is exceeded | Q3 2026 |
| `terminology-version-gate` | 6. Terminology Gov. | Data layer middleware that version-tags records and blocks unvalidated cross-version queries | Q3 2026 |

## Architecture

All tools follow a shared design philosophy:

- **Python-first**: pip-installable, minimal dependencies
- **Pipeline-compatible**: Works with Airflow, Prefect, dbt, and standard ML pipelines
- **Healthcare-standards-aware**: FHIR R4, HL7, OMOP compatible where applicable
- **Open Core**: Base functionality is open source. Enterprise features (pre-trained models, managed dashboards, jurisdiction-specific adapters) are available through oDIX8.

## Contributing

We welcome contributions from the clinical AI community. If you are working on implementations of these patterns in your own systems, we would like to hear from you.

Contact: [office@odix8.com](mailto:office@odix8.com)
