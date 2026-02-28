# Structure Evaluation and Model Quality Assessment

This document describes methodological criteria used to evaluate predicted protein structures within this repository workflows.

The objective is not to claim experimental validation, but to provide transparent interpretation of computational model reliability.

---

## 1. Evaluation Philosophy

Protein structure predictions are interpreted as probabilistic structural hypotheses rather than experimentally confirmed conformations.

Quality assessment therefore focuses on identifying regions suitable for structural interpretation and regions requiring caution.

---

## 2. Confidence Metrics

### pLDDT (Predicted Local Distance Difference Test)

The pLDDT score provides residue-level confidence estimation.

General interpretation:

- **> 90** — very high confidence; suitable for structural interpretation and docking preparation
- **70–90** — reliable backbone prediction; acceptable for domain analysis
- **50–70** — low confidence; may indicate flexibility
- **< 50** — likely intrinsically disordered regions (IDRs)

Low-confidence regions are explicitly documented rather than removed without justification.

---

### Predicted Aligned Error (PAE)

PAE matrices are used to evaluate relative positioning between domains.

Interpretation focuses on:

- domain orientation reliability
- potential inter-domain flexibility
- uncertainty in large multidomain proteins

High PAE between domains suggests caution in rigid-body interpretation.

---

## 3. Domain-Level Interpretation

Structural confidence is analyzed at domain scale rather than relying solely on global scores.

This includes:

- identification of stable cores
- flexible linkers
- potentially disordered termini

Domain-aware interpretation improves downstream usability of predicted models.

---

## 4. Handling Low-Confidence Regions

Regions presenting low confidence scores are treated as biologically meaningful features when appropriate.

Possible interpretations include:

- intrinsically disordered regions
- conformational flexibility
- missing evolutionary constraints

Such regions are documented to avoid overinterpretation during docking or mechanistic inference.

---

## 5. Reproducibility Principles

All evaluations prioritize:

- transparent reporting
- conservative interpretation
- methodological traceability

The goal is to support reproducible structural reasoning using accessible computational environments.
