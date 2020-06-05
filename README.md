 # Immunological data analysis using R and Bioconductor
 
 ## Part 1 - Gene expression profiles of different immune cell types
 
 The immune system is composed of many different cell types which have various biological functions. In order to examine the processes underlying the functional differences between these cell types we can compare their gene expression profiles using RNA sequencing (RNA-seq). RNA-seq is a widely used next-generation sequencing based technique to quantify the abundance of RNA transcripts in a biological sample at a given moment. Differences in gene expression profiles can be assessed by performing differential gene expression analysis. A common subsequent approach to interpreting the results is gene set enrichment analysis based on the functional annotation of the differentially expressed genes.

This part of the course will start with a short introduction to the programming language R and to Bioconductor software tools. We will then use different R/Bioconductor packages to analyse and compare the expression profiles of different human immune cell types. We will use Rmarkdown to document our analyses and create a comprehensive report.

**Learning objectives:**

- describe and explain the different steps in RNA sequencing workflows
- perform and understand differential gene expression analysis
- perform and understand gene set enrichment analysis
- use Rmarkdown to create an analysis report

** Teaching material:**

- Introduction to R and Bioconductor 
- Introduction the RNA sequencing and differential gene expression
- Introduction to gene set enrichment analysis
- Tutorial on analysis of immune population transcriptomics

## Part 2 – Automated analysis of an antibody reactivity assay

The enzyme-linked immunosorbent assay (ELISA) is one of the most frequently used assays to study antibody-antigen binding. While it is not the most quantitative assay (small linear range), it is cheap, has a high sensitivity, is easy to setup and only requires a simple absorbance reader. The absorbance data can be summarized to compare the antigen reactivity of different antibodies.

In this part of the course we will explore the different steps of a ELISA to understand how the absorbance data is generated. We will then use R to analyze and summarize the data and quantify antigen reactivity.

**Learning objectives:**

- describe and explain the steps of an ELISA assay to measure antibody antigen reactivity
- use R to perform an automated analysis of ELISA results
- compare the antigen reactivity of different antibodies
- use R to perform a small exploratory data analysis and create graphical representations

**Teaching material:**

- Introduction to ELISA antibody reactivity assay
- Introduction to data wrangling and graphical representation
- Tutorial on analysis of ELISA data


## Schedule

| Time  | Monday 15.06.2020 | Tuesday 16.06.2020 | Wednesday 17.06.2020 |
| ----- | ----------------- | ------------------ | -------------------- |
| 8-12  | Lecture           | Lecture            | Lecture              |
| 10-12 | Intro RNAseq      | Introduction GSEA  | Intro ELISA          |
| 12-13 |                   |                    |                      |
| 13-16 | Tutorial DGE      | Tutorial DGE+GSEA  |  Tutorial ELISA      |
| 16-18 | Journal Club      | Journal Club       |  Journal Club        |

## Reports

The practical report should be written in Rmarkdown and consist of the two parts, which correspond to the analyses performed in the tutorials:

- Differential gene expression analysis and gene set enrichment analysis
- Automated analysis of an antibody reactivity assay
