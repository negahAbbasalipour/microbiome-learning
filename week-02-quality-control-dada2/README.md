
# Week 2 – Sequence Quality Control and DADA2

## Overview

This week focused on understanding sequencing quality and performing an initial denoising analysis using QIIME 2 and the Moving Pictures tutorial dataset.

The main objective was to understand how sequencing reads are assessed, processed, and transformed into amplicon sequence variants (ASVs).

## What I Did

- Explored demultiplexed sequencing data.
- Generated and inspected the interactive quality visualization (`demux.qzv`).
- Examined per-base Phred quality scores.
- Investigated how sequencing quality changes across read positions.
- Performed an initial DADA2 denoising analysis using the `denoise-single` command.
- Generated the main DADA2 outputs:
  - Feature table (`table.qza`)
  - Representative sequences (`rep-seqs.qza`)
  - Denoising statistics (`stats.qza`)
  - Base transition statistics (`base-transition-stats.qza`)
- Inspected DADA2 statistics to understand read retention across processing steps.

## What I Learned

### 1. Sequencing Quality Assessment

I learned how to interpret Phred quality scores and examine quality profiles to identify changes in sequencing quality along read positions.

### 2. DADA2 Denoising

I explored how DADA2 processes sequencing reads and generates amplicon sequence variants (ASVs).

I also learned about the main processing stages:

- Input
- Filtering
- Denoising
- Chimera removal

### 3. Understanding DADA2 Parameters

I studied two important parameters used in read processing:

- `trimLeft`: Removes a specified number of nucleotides from the beginning of each read.
- `truncLen`: Truncates reads at a specified position.

I practiced calculating the remaining read length after applying both parameters.

## Challenges and Observations

One important part of this week's learning was understanding how read counts change during DADA2 processing.

By examining denoising statistics, I started learning how to interpret read retention and identify samples with substantial read loss.

I also learned that parameter selection should be guided by sequencing quality profiles rather than arbitrary values.

## Next Steps

- Learn how to select appropriate DADA2 parameters.
- Understand the effects of filtering and truncation settings.
- Continue exploring feature tables and representative sequences.
- Prepare for downstream taxonomic classification.

## Learning Notes

This week helped me move beyond simply running bioinformatics commands toward understanding what happens to sequencing data at each processing stage.

My focus remains on building a solid foundation in microbiome data analysis before applying these skills to urinary microbiome (Urobiome) datasets.

---

*Learning step by step, one dataset at a time.*

