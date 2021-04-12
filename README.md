# bioinfoworkshop_epigenetics

This workshop is organized in February as part of the course "Ecological Proteomics and Epigenetics (SBOEM166)" in the master program in Organism Biology and Ecology from the University of Namur and the University of Louvain-la-Neuve (Belgium).  

The goal is to learn a workflow to analyse DNA methylation data from high throughput sequencing (we're using RRBS examples). It is divided in 3 parts, each of half day. The scripts of each part are available in the repository (Workshop bioinfo 2021 partX.Rmd). 

The students should be familiar with RStudio environment and basic functions and syntax (ex:how to install and load packages, etc). However, the beginning of the workshop is dedicated to setup RStudio and Bioconductor, and to create a RMarkdown document. It is asked to the students to share their RMarkdown document at the end of the workshop.

# Table of content:

# Part1:

- setup of RStudio environment; setup of Bioconductor; installing packages; creating a RMarkdown document and a github account
- working with sequences
  * DNAstring and DNAstringSet objects
- working with set of genes
  * GRange objects
  * ExpressionSet objects

# Part2:

- Learning the package "methylkit"
- Data filtering and exploratory analyses
  * analyses on CpG
  * analyses on regions
  * PCA and clustering analyses
- Extracting regions of interest
- Annotating DMR/DMC

# Part3:

- Running quality control from a fastq sequence (FASTQC)
- Alignment to a reference genome with Bismark and Samtools
- Trimming with Trim Galore!
- DNA methylation analysis on real data with the methylkit package

