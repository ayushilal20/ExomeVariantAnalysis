# ExomeVariantAnalysis

## Descritpion
This repository contains a series of Jupyter notebooks developed as part of the BIOL 6150 (Genomics and Applied Bioinformatics) course project. This project uses the PACE-ICE HPC environment to provide a comprehensive pipeline for whole exome sequencing (WES) data analysis, from raw reads to SNP variant calling. The pipeline is divided into three main stages, each represented by a Jupyter notebook:
1. Read Cleaning
2. Sequence Alignment
3. Variant Calling

## Notebooks Overview
01_read_cleaning.ipynb
This notebook covers the preprocessing steps required to clean raw WES reads, including:
* Quality control
* Adapter trimming
* Filtering low-quality reads

02_sequence_alignment.ipynb
This notebook describes the steps to align cleaned reads to the reference genome, including:
* Indexing the reference genome
* Aligning reads using BWA
* Post-alignment processing (e.g., sorting, marking duplicates)

03_variant_calling.ipynb
This notebook focuses on SNP variant calling, including:
* Generating the variant call format (VCF) file
* Filtering SNPs

## Acknowledgements
This project was developed as part of the BIOL 6150 course. Special thanks to the course instructors, the PACE-ICE HPC support team for their guidance and resources, and my team members Anagha Mohana Krishna and Hina Gaur.
