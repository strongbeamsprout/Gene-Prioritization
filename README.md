# Gene-Prioritization User Manual
Author: Yile Chen, Shantanu Jain, Daniel Zeiberg, Lilia Iakoucheva, Sean D. Mooney, Predrag Radivojac, Vikas Pejaver

## Introduction
This repo contains:

- Data:

  1. genetab.csv: master gene table summarizing variants clinical significance information from ClinVar, the number of variants in gnomAD, and the distribution of REVEL scores for each gene.
  2. geneWassay.csv: genes that have been assayed or are expected to be assayed in the near future. 
  3. g2pubcnt.wID: publication counts linked to each gene as reported by PubMed (https://ftp.ncbi.nlm.nih.gov/gene/DATA/gene2pubmed.gz) in July 2022.
  4. misrevel.RDS: REVEL scores obtained from https://sites.google.com/site/revelgenomics/downloads.
  5. REVEL_local_posteriors.txt: a mapping of all possible REVEL scores to local posterior probability of pathogenicity and benignity from Pejaver et al..
  6. complete_prio_gene_sysVarEffMap_paper.csv: DAIS score prioritized gene list from Kuang et al..

- Results:

  1. Supp. Table 1: master gene table 
  2. Supp. Figure 1: Functional enrichment analysis of the top 100 genes ranked by the optimal weighted combined scores. A. 36 significantly enriched GO terms (12 BP, 10 CC, 14 MF), B. 40 most significantly enriched HP terms. The point size indicates the number of genes found in both the functional terms and top 100 genes. GO:BP, GO biological process; GO:CC, GO cellular component; GO:MF, GO molecular function; HP, human phenotype. 
  3. gProfiler_output.csv: Functional enrichment analysis output. 
 
