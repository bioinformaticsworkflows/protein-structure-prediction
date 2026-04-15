# Protein Structure Analysis Report  
## SARS-CoV-2 Main Protease (Mpro)

---

## Objective

Provide structural analysis and interpretation of a protein–ligand complex using reproducible bioinformatics workflows.

---

## Data Source

Structure: PDB 7GAW  
Resolution: 1.81 Å  
Source: Fragalysis platform (public structural dataset)  

---

## Structural Overview

The SARS-CoV-2 main protease (Mpro) is a cysteine protease essential for viral replication.

The active site is defined by the catalytic dyad:

- His41  
- Cys145  

---

## Binding Site Analysis

The analyzed ligand (MAT-POS-e194df51-1) occupies the canonical substrate-binding pocket.

Key interaction regions:

- S1 subsite: His163, Glu166  
- S2 subsite: Met49, Met165  
- Extended region: Gln189 and surrounding loop structures  

> **Structural reasoning note:**  
> Binding site identification prioritizes conserved catalytic features and ligand-supported conformations rather than relying solely on static structural snapshots.

---

## Structural Dynamics

Local conformational flexibility is observed in the loop region (~residues 186–192).

Ligand binding induces rearrangements in this region, particularly near:

- Gln189  

This results in expansion of the binding cavity and exposure of transient subpocket volumes that are not fully apparent in apo structures.

> **Interpretative note:**  
> Observed pocket expansion is interpreted as ligand-induced conformational adaptability rather than evidence of a distinct secondary binding site.

---

## Model Quality and Structural Interpretation

The analyzed structure corresponds to PDB entry 7GAW, a high-resolution crystallographic model of SARS-CoV-2 main protease in complex with a non-covalent inhibitor.

The structure presents high crystallographic quality:

- Resolution: 1.81 Å  
- No Ramachandran outliers  
- Low clashscore  

These features support reliable structural interpretation.

Because experimentally determined coordinates are used:

- atomic positions are derived from X-ray diffraction data  
- structural confidence exceeds predictive models  
- analysis focuses on interpretation rather than validation  

Interpretative criteria remain consistent with predictive workflows:

- structural stability assessed at domain level  
- flexible regions treated cautiously  
- binding interactions interpreted within structural context  

> **Analytical note:**  
> Structural interpretation integrates experimental validation with workflow-based reasoning, avoiding over-reliance on either purely computational predictions or purely visual inspection.

---

## Data Access

Interactive dataset:

https://fragalysis.diamond.ac.uk/viewer/react/preview/target/CoV-Mpro/tas/lb32627-272

Protein and ligand files can be downloaded directly from the platform for independent inspection.

---

## Limitations

This analysis does not represent experimental validation or drug discovery claims.

It is intended for structural interpretation and reproducible workflow demonstration.

---

## Deliverable Summary

This report demonstrates:

- structural interpretation capability  
- binding site characterization  
- use of experimental datasets  
- reproducible analytical workflow  

---

Prepared using reproducible bioinformatics workflows.
