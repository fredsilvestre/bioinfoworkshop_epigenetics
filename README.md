# bioinfoworkshop_epigenetics

This workshop is organized in February as part of the course "Ecological Proteomics and Epigenetics (SBOEM169)" in the master program in Organism Biology and Ecology from the University of Namur and the University of Louvain-la-Neuve (Belgium).  

The goal is to learn a workflow to analyse DNA methylation data from high throughput bisulfite sequencing (we're using RRBS examples). It is divided in 3 parts, each of half day. The scripts of each part are available in the repository (Workshop bioinfo 2025 partX.Rmd). 

The students should be familiar with RStudio environment and basic functions and syntax (ex:how to install and load packages, etc). The beginning of the workshop is dedicated to setup Bioconductor, to create a RMarkdown document, and to work with sequences and genomic objects. 


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

- Running quality control from a fastq sequence (FASTQC or Bioconductor)
- Alignment to a reference genome  (Bismark and Samtools)
- Trimming (Trim Galore! or Bioconductor)
- DNA methylation analysis on real data with the methylkit package
- Data visualisation (SeqMonk)

