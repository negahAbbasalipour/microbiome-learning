
# Microbiome Bioinformatics Learning Journey

This repository documents my hands-on journey into microbiome bioinformatics, including practical exercises, data analysis, learning notes, challenges, and solutions.

My goal is to develop practical skills in microbiome data analysis using **QIIME 2** and **R**, with a particular long-term interest in the urinary microbiome (Urobiome).

## Learning Objectives

- Understand microbiome sequencing data and quality control.
- Learn amplicon sequence variant (ASV) analysis using DADA2.
- Explore taxonomic classification and microbial diversity.
- Develop practical skills in QIIME 2 and R.
- Apply these skills to publicly available microbiome datasets.

## Weekly Progress

### Week 1 – Environment Setup

- Set up Git and GitHub.
- Installed WSL2 and Ubuntu on Windows.
- Installed and configured a QIIME 2 environment.
- Verified the installation using `qiime info`.

### Week 2 – Sequence Quality Control and DADA2

- Imported sequencing data from the QIIME 2 Moving Pictures tutorial.
- Explored sequencing reads and generated quality visualizations.
- Examined Phred quality scores across sequencing positions.
- Performed DADA2 denoising using `denoise-single`.
- Started interpreting denoising statistics and read retention at different processing steps.
- Learned about the roles of `trimLeft` and `truncLen` parameters.

**Current focus:** Understanding how quality filtering and trimming parameters influence the final sequencing reads.

## Planned Next Steps

- Complete the interpretation of DADA2 statistics.
- Explore feature tables and representative sequences.
- Perform taxonomic classification.
- Explore alpha and beta diversity.
- Begin working with a public urinary microbiome (16S) dataset.

## Long-Term Research Interest

My long-term goal is to apply microbiome bioinformatics approaches to urinary microbiome research and investigate microbial community composition and diversity.

---

*Learning step by step, one dataset at a time.*
