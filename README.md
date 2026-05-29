# CTX-M-Beta-Lactamase-Sequence-Conservation-Analysis
A bioinformatics workflow for CTX-M β-lactamase sequence retrieval, multiple sequence alignment, conservation profiling, and evolutionary interpretation using publicly available NCBI protein data.


## Biological Goal:
  -  Compare β-lactamase sequences from different bacterial origins
  -  Identify evolutionarily conserved and highly variable regions
  -  By identifying highly conserved and highly variable regions, this analysis provides sequence-level evidence for functional constraints and evolutionary diversification underlying antimicrobial resistance.

## Workflow
NCBI Protein Database
↓
Sequence Retrieval
↓
Multiple Sequence Alignment 
↓
Alignment Matrix Generation
↓
Conservation Score Calculation
↓
Visualization
↓
Biological Interpretation


## Project Structure
analysis/
│
├── data/
│   ├── ctxm_refseq_full.fasta
│   └── ctxm_refseq_full_aligned.fasta
│
├── notebooks/
│   ├── 01_fetch_sequences.ipynb
│   ├── 02_alignment.ipynb
│   └── 03_conservation_analysis.ipynb
│
├── results/
│   └── conservation_profile.png
│
└── README.md
