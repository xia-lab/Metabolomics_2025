# Using web-based tools for integrative analysis of metabolomics and microbiome data for deep functional insights

# Introduction
Metabolomics is increasingly used together with marker gene profiling and/or shotgun metagenomics to help
researchers gain deep insights into community functions and host-microbiome interactions. However, proper
data processing, statistical analysis, functional interpretation and multi-omics integration represent the major
bottleneck. In this workshop, we will introduce a suite of user-friendly, freely available bioinformatics software
tools that have been developed to comprehensively address this gap. The tool suite consists of four
components:

<br/>
1. Raw data processing based on OptiLCMS / Asari for metabolomics, and DADA2 / FunTaxSeq for
microbiome data<br/>
2. MetaboAnalyst.ca for metabolomics data profiling<br/>
3. MicrobiomeAnalyst.ca for microbiome data profiling<br/>
4. MicrobiomeNet.com for functional interpretation and system biology.<br/>

<br/>
The workshop will contain three components - lecture (~60 min), live demos & hands-on practices (~2.5 hours),
and summary & discussion (~30 min). During the live demo, we will illustrate common workflows through three
well-curated example datasets for three typical study designs. Users are expected to bring their laptops for
hands-on practice following each demo. We will also create a comprehensive protocol (~80 pages) containing
step-by-step instructions for common tasks.

<br/>

# Workshop Objectives
 Learn to process raw data generated in metabolomics & microbiomics<br/>
 How to perform statistical analysis<br/>
 How to perform multi-omics integration<br/>

# Learning Outcomes
 Be able to comfortably perform common data analysis tasks in microbiome metabolomics studies.


Details for each workflow are below. 

#### <ins>Before you start, please download [MetaboAnalyst 6.0](https://doi.org/10.1093/nar/gkae253) and [MetaboAnalystR 4.0](https://www.nature.com/articles/s41467-024-48009-6) as references.</ins>

<br/>

# Slides In Sections

- [Introduction and Key Concepts](https://github.com/xia-lab/Metabolomics_2024/blob/main/slides/1_General_intro_MetaboAnalyst.pdf).
- [LC-MS/MS spectral processing and compound indentification](https://github.com/xia-lab/Metabolomics_2024/blob/main/slides/2_LC_MSMS_spec_section.pdf).
- [Functional analysis from LC-MS peaks](https://github.com/xia-lab/Metabolomics_2024/blob/main/slides/3_Functional_analysis_section.pdf).
- [Metabolomics Statistical Analysis of One-factor experimenta and complex metadatal design](https://github.com/xia-lab/Metabolomics_2024/blob/main/slides/4_statistics_section.pdf).
- [Causal Analysis and conclusion](https://github.com/xia-lab/Metabolomics_2024/blob/main/slides/5_Causal_analysis_summarization.pdf).

<br/>

## 1) LC-MS Spectra Processing and Annotation

The aim of this workflow is to use **LC-MS Spectra Processing module** in [MetaboAnalyst](https://www.metaboanalyst.ca/) to analyze the raw spectra data from a real-world experiments. This section includes raw spectral data format conversion and centroiding. Then we will show a quick demon on how to use MetaboAnalyst for raw LC-MS/MS spectra data processing. The data was obtained using untargeted metabolomics (Q-Exactive Plus Orbitrap MS in positive ion mode) of different blood types (whole blood, serum and plasma). 6 pooled QC samples and DDA MS/MS spectra files are also included. In this section, students will learn how to run the auto-optimized raw spectra processing workflow.

(Optionally) To practice raw spectral data conversion and centroiding, users could download some raw thermo-fisher spectral data (*.raw) from this [link](https://drive.google.com/file/d/17HwDYqISi60bSUEAghQYSzikkuw89n-9/view?usp=sharing).

For this workflow, users could use the 3rd example directly from the module page or optionally download [here](https://www.dropbox.com/scl/fi/2opls296pzffz5hbvjhun/blood_samples.zip?rlkey=tknlc3iik5yhlm2gmkk423c7m). **For the learning purpose, you are strongly encouraged to use the 1st example directly to run the whole process quickly.**

The tutorial of this module is available [here](https://api2.xialab.ca/api/download/metaboanalyst/1_LC_MS_Spectra_Processing.pdf) for further reference. Watch this [video](https://youtu.be/NSwc7Ywvbpw) to see a live demo of raw spectra data processing with MetaboAnalyst.

<br/>

## 4) Raw sequencing data processing (16s)

Some sentences



<br/>

## 3) Statistical analysis

Some sentences

<br/>

## 4) Multi-omics integration

Some sentences



<br/>

## Additional Reference Documents

To understand more background knowledge on metabolomics data analysis further, you can follow these documents/protocols below. 

#### MetaboAnalyst latest Nature Protocols
[Using MetaboAnalyst Nature Protocol](https://doi.org/10.1038/s41596-022-00710-w)

#### Latest tutorials of MetaboAnalyst
[All tutorial series](https://www.metaboanalyst.ca/MetaboAnalyst/docs/Tutorials.xhtml)


#### Latest tutorials of MetaboAnalystR
[MetaboAnalystR tutorial](https://www.metaboanalyst.ca/MetaboAnalyst/docs/RTutorial.xhtml)


#### Multi-omics integration and protocols
[Web-based multi-omics integration using the Analyst software suite](https://www.nature.com/articles/s41596-023-00950-4)

#### Protocols of Other Modules in MetaboAnalyst
[Using MetaboAnalyst 4.0 for Comprehensive and Integrative Metabolomics Data Analysis](https://currentprotocols.onlinelibrary.wiley.com/doi/10.1002/cpbi.86)

#### Critical Algorithms and concepts
[asari](https://www.nature.com/articles/s41467-023-39889-1);
[MetaboAnalystR 3.0](https://pubmed.ncbi.nlm.nih.gov/32392884/);
[Mummichog](https://pubmed.ncbi.nlm.nih.gov/23861661);
