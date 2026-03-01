# Workflow Overview Diagram

This diagram summarizes the analytical logic used in this repository.

```mermaid
flowchart LR

A[Biological Sequence or Experimental Structure]
--> B[Data Curation & Context Evaluation]

B --> C[Structure Source Selection]
C -->|Experimental Structure Available| D[Use PDB / Fragalysis Structure]
C -->|No Structure Available| E[AlphaFold / ColabFold Prediction]

D --> F[Model Quality Evaluation]
E --> F

F --> G[pLDDT & PAE Interpretation]

G --> H[Structural Reasoning]
H --> I[Scientific Documentation]

I --> J[Reproducible Workflow Output]
