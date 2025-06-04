# Computer-Aided-Drug-Design-Novel-Drug-Target-Identification-for-MRSA
This project applies a **subtractive genomics approach** to identify potential novel drug targets in *Methicillin-resistant Staphylococcus aureus* (MRSA) using various bioinformatics tools.

## 🦠 Overview

MRSA is a multidrug-resistant pathogen responsible for a wide range of serious infections. This project aims to:

- Eliminate human and paralogous homologous proteins
- Identify essential, non-homologous proteins unique to the pathogen
- Pinpoint membrane and cytoplasmic proteins as drug targets
- Analyze conservation and avoid cross-reactivity with host “anti-targets”

## 🔬 Methodology

The pipeline involved:

1. **Data Retrieval**: Full proteome from NCBI
2. **Filtering**: Hypothetical proteins, non-paralogous via CD-Hit
3. **Non-Homology Screening**: BLASTp vs human proteome
4. **Essential Protein Identification**: DEG database
5. **Pathway Mapping**: KEGG & KAAS
6. **Subcellular Localization**: CELLO server
7. **Anti-target Analysis**: BLASTp vs known human anti-targets
8. **Conservancy Check**: BLASTp across MRSA strains

A single cytoplasmic protein involved in a unique pathogen-specific metabolic pathway was identified as a novel drug target.

## 📄 Report

The full report is available in [`report.pdf`](./Report.pdf).

## 👨‍🔬 Author

**Dinesh Davagandhi**  
Bachelor’s in Bioinformatics, Management and Science University  
---

> _Note: This project was submitted as part of an undergraduate major project in Bioinformatics._
