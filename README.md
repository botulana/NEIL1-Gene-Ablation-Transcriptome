# Ablation of the NEIL1 Gene Alters the Transcriptome of Htert RPE-1 Cells

## Master's Thesis Project

This repository contains the code, data analysis scripts, and relevant materials from my master’s thesis titled: **"Ablation of the NEIL1 Gene Alters the Transcriptome of Htert RPE-1 Cells."** This project explores the molecular and transcriptional consequences of NEIL1 gene knockout in human retinal pigment epithelial (Htert RPE-1) cells.

---

## Overview

The NEIL1 gene is crucial for the base excision repair (BER) pathway and is known to protect cells from oxidative stress. This study aims to understand the transcriptomic changes that occur when the NEIL1 gene is ablated in Htert RPE-1 cells. The findings provide insights into the gene's role in maintaining genome integrity and its potential implications in diseases such as cancer.

The project combines RNA sequencing (RNA-Seq) data, bioinformatics pipelines, and statistical analysis to identify differentially expressed genes and affected biological pathways.

---

## Contents of the Repository

- **data/**: Contains sample datasets used in the analysis (if allowed for sharing) or mock data that replicates the study's structure.
- **src/**: Source code for data preprocessing, quality control, alignment, and analysis.
- **notebooks/**: Jupyter notebooks with detailed step-by-step analysis, including:
  - RNA-Seq data processing (quality control, trimming, alignment)
  - Differential expression analysis using tools such as `DESeq2` or `edgeR`
  - Pathway enrichment and functional annotation
- **results/**: Outputs including plots, gene expression heatmaps, PCA, volcano plots, and pathway analysis results.
- **thesis/**: A copy of the final written thesis (optional).

---

## Key Features

- **RNA-Seq Workflow**: Full RNA-Seq analysis pipeline using tools such as `FastQC`, `Trim Galore!`, `STAR`, `HTSeq`, `DESeq2`, and more.
- **Differential Expression Analysis**: Identification of genes significantly altered due to NEIL1 ablation, with rigorous statistical testing.
- **Functional Enrichment**: Pathway and gene ontology (GO) analysis to pinpoint biological processes impacted by NEIL1 knockout.
- **Reproducible Research**: All scripts and analysis workflows are designed to ensure reproducibility.

---

## Installation & Requirements

To run the analysis, you’ll need the following tools and libraries installed:

- **Python 3.x**: For scripting and data handling.
- **R**: For statistical analysis and visualization (specifically, `DESeq2`).
- **Jupyter Notebooks**: For interactive exploration of the data.
- **RNA-Seq tools**:
  - `FastQC`
  - `Trim Galore!`
  - `STAR`
  - `HTSeq`
  - `DESeq2`

---

## Data Description

- **Transcriptome Data**: RNA-Seq data collected from Htert RPE-1 cells with and without NEIL1 gene ablation.
- **Data Preprocessing**: Steps include trimming, alignment to the reference genome, and quantification of gene expression levels.
- **Differential Expression**: Genes with significant expression changes identified using statistical thresholds (e.g., adjusted p-value < 0.05 and log2 fold change > |1|).

---

## Results

The analysis reveals that the ablation of the NEIL1 gene significantly alters the expression of genes involved in DNA repair, oxidative stress response, and cell cycle regulation. Pathway enrichment analysis highlights disruptions in key signaling pathways, providing insights into how NEIL1 helps maintain genome stability.

---

## Future Work

Future directions include validating the differential expression results through experimental techniques such as qPCR and further exploring the impact of NEIL1 ablation on cellular behavior and phenotypic outcomes.

