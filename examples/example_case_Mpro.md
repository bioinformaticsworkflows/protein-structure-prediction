# Example Case — SARS-CoV-2 Main Protease (Mpro) Open-Science Dataset

## Objective

This example demonstrates application of the workflow to a real open-science structural biology dataset using accessible computational environments.

The purpose is methodological illustration and reproducible analysis rather than novel biological discovery.

---

## Dataset Context

The SARS-CoV-2 main protease (Mpro) became a central target for antiviral drug discovery during the COVID-19 pandemic.

Large collaborative initiatives released structural and ligand-screening datasets openly to accelerate global research efforts.

This example references publicly available structures distributed through the Fragalysis platform, associated with the COVID Moonshot open-science initiative.

---

## Data Provenance

- Target: SARS-CoV-2 Main Protease (Mpro)
- Dataset platform: Fragalysis
- Initiative context: COVID Moonshot open-science collaboration
- Structural data: experimentally determined protein–ligand complexes released for public analysis

All data referenced are publicly available and used strictly for methodological demonstration.

---

## Workflow Application

The repository workflow can be applied to this dataset through:

1. Structural inspection of ligand-bound complexes
2. Preparation of protein structures for analysis
3. Interpretation of structural confidence and binding context
4. Documentation of analytical reasoning

Analyses are designed to be executable using accessible computational environments rather than specialized HPC infrastructure.

---

## Structural Context

The SARS-CoV-2 main protease (Mpro) is a cysteine protease responsible for viral polyprotein processing and represents a validated antiviral drug target.

The active site is located in a cleft between domains I and II and contains the catalytic dyad:

- His41  
- Cys145  

---

## Binding Site Characterization

Analysis of ligand-bound structures from the COVID Moonshot dataset indicates that the inhibitor MAT-POS-e194df51-1 occupies the canonical substrate-binding pocket.

### Binding pocket organization:

- **S1 subsite:** interactions near His163 and Glu166 support ligand positioning
- **S2 subsite:** hydrophobic interactions involving Met49 and Met165
- **Extended pocket (S3–S5):** flexible region including Gln189 and surrounding loops


> **Structural reasoning note:**  
> Binding site identification prioritizes conserved catalytic features and ligand-supported conformations rather than relying solely on static structural snapshots.

---

## Cryptic Pocket Behavior

Structural datasets reveal localized conformational flexibility in the loop region spanning residues ~186–192.

Ligand binding induces rearrangements in this region, particularly near:

- Gln189  

This results in expansion of the binding cavity and exposure of transient subpocket volumes that are not fully apparent in apo structures.

Such behavior is consistent with ligand-induced pocket plasticity observed across multiple Mpro complexes. 

> **Interpretative note:**  
> Observed pocket expansion is interpreted as ligand-induced conformational adaptability rather than evidence of a distinct secondary binding site.

---

## Model Quality and Structural Interpretation

Because this example uses experimentally determined structures:

- atomic coordinates are derived from crystallographic data
- confidence is determined by experimental resolution rather than predictive metrics

However, interpretative criteria remain consistent with predictive workflows:

- structural stability assessed at domain level
- flexible regions treated cautiously
- binding interactions interpreted within structural context

> **Analytical note:**  
> Structural interpretation integrates experimental data with workflow-based reasoning to avoid over-reliance on either purely computational or purely visual inspection.

---

## Data Access

Interactive visualization and dataset access:

https://fragalysis.diamond.ac.uk/viewer/react/preview/target/CoV-Mpro/tas/lb32627-272

Users may download protein and ligand structures directly from the platform to reproduce analysis steps.



---

## Scientific Interpretation Scope

This example does not attempt drug discovery claims or experimental validation.

Its role is to demonstrate how open structural datasets can be incorporated into transparent computational workflows supporting reproducible scientific interpretation.

---

## Open-Science Relevance

The dataset exemplifies modern distributed scientific collaboration, where openly shared structural information enables independent researchers to participate in computational analysis and hypothesis exploration.

This aligns with the repository’s emphasis on accessibility, reproducibility, and methodological clarity.
