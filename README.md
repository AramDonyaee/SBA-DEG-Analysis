Identification of novel hub genes for Small Bowel Adenocarcinoma with integrated and non-integrated bioinformatics tools

## Overview

This repository contains a detailed study aimed at identifying novel hub genes associated with small bowel (intestine) adenocarcinoma through differential gene expression analysis. The study utilizes Gene Ontology (GO) enrichment analysis, KEGG pathway analysis, and Protein-Protein Interaction (PPI) network construction using the STRING database. Additionally, we identify associated mRNA, transcription factors (TFs), and drugs linked to the hub genes using the NetworkAnalyst platform. The original microarray gene experssion data was obtained from GEO Omnibus. The accession number of the dataset is GSE61465 and is available on [here](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE61465).

## Table of Contents

- [Background](#background)
- [Objectives](#objectives)
- [Methodology](#methodology)
- [Usage](#usage)

## Background

Small bowel adenocarcinoma is a rare but aggressive form of cancer that poses significant treatment challenges. Identifying hub genes involved in its pathogenesis can provide insights into potential therapeutic targets and biomarkers. This study employs a systematic approach to uncover novel hub genes and their associated biological networks.

## Objectives

- Perform differential gene expression analysis to identify genes significantly associated with small bowel adenocarcinoma.
- Conduct GO and KEGG pathway enrichment analyses to understand the biological processes and pathways involved.
- Construct a PPI network using the STRING database to visualize interactions among the identified genes.
- Identify novel hub genes within the PPI network using Cytoscape.
- Explore associated mRNA, transcription factors, and drugs related to the hub genes using the NetworkAnalyst platform.

## Methodology

1. **Data Acquisition**: 
   - Collected gene expression data from GEO Omnibus

2. **Differential Gene Expression Analysis**: 
   - Utilized R limma package to identify differentially expressed genes (DEGs) between tumor and normal samples.

3. **GO and KEGG Enrichment Analysis**: 
   - Performed GO and KEGG pathway analyses to determine the biological significance of the DEGs.

4. **PPI Network Construction**: 
   - Built a PPI network using the STRING database to visualize gene interactions.

5. **Hub Gene Identification**: 
   - Identified novel hub genes from the PPI network using Cytoscape's network analysis tools.

6. **Network Analysis**: 
   - Used the NetworkAnalyst platform to explore associated mRNA, transcription factors, and potential drugs related to the hub genes.

## Usage

To run the analyses in this repository, run the cells in the R notebook provided in this repository.
