# RNA-Seq_ArabidopsisThaliana

In this directory I develop an RNA-Seq Analysis from the organism Arabidopsis thaliana, using Sequence Read Archive (SRA) raw RNA-Seq data from NCBI. 

The project includes:

1. Bioproject Description
    1. Raw Data Download and Manipulation
    2. Quality Lectures Analysis using MultiQC and Fastqc
    3. Adapters Removal 
2. Reference Transcriptome assembly with Kallisto
    1. Pseudoalignment with Kallisto
3. Differential Expression with DESeq2 in R
    1. Data import from Kallisto to R
    2. Normalization of count for graphs 
    3. Differential expression of the transcriptomes
    4. GO terms analysis
4. Disscusion
    1. Comparing Results with the original paper
    2. Comparing out results with othe related papers
5. Bibliography. 

All in rmd and html format, along with .tsv, .csv and .map files.
