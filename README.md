# FtsZ Inhibitor Analysis

This project investigates the potential of targeting *Mycobacterium tuberculosis* FtsZ protein as a novel drug target for developing a broad-spectrum antibacterial agent. It includes structural analyses, BLAST alignment, multiple sequence alignments (MSA), and small molecule docking visualizations.

---

## Project Overview

Multidrug-resistant bacterial strains pose a growing threat to global health. FtsZ is a highly conserved bacterial protein essential for cell division, and recent studies have identified it as a promising target for therapeutic intervention.

This project presents:
- PSI-BLAST search results comparing *M. tuberculosis* FtsZ with homologous proteins
- MSA and phylogenetic tree visualizations
- Structural analysis of FtsZ using PyMOL
- Docking studies highlighting promising small molecule inhibitors

---

## Repository Structure

```bash
FtsZ-Inhibitor-Analysis/
├── README.md
├── report/
│   └── FtsZ_inhibitor_analysis.pdf
└── data/
    └── pymol_sessions/
        └── residues_1rq7.pse
```

---

## Report

The full scientific write-up, including methods, analysis, figures, and references, is available here:

📄 [`report/FtsZ_inhibitor_analysis.pdf`](report/FtsZ_inhibitor_analysis.pdf)

---

## Supplementary Files

### PyMOL Sessions

Archived PyMOL session files used during protein structure analysis:

- `residues_1rq7.pse`: Highlights binding pocket residues (IDC region) on *M. tuberculosis* FtsZ (PDB: 1RQ7), including ARG91, GLY123, and THR125.

> ⚠️ Requires licensed PyMOL to view. Files are provided for reference only.

---

## Tools Used

- **NCBI PSI-BLAST**
- **JalView** (for MSA and phylogenetic tree)
- **PyMOL** (for structural visualization)
- **1-Click Docking** (for small molecule interaction predictions)

---

## Notes

This project is archived for academic reference and was originally conducted using a licensed version of PyMOL. Source code or raw data is not included, but all relevant outputs are preserved.

---
