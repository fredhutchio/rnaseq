# RNAseq courses

## Description

This RNAseq course collection includes both lecture-type classes focused on concepts
as well as lab-type skills (coding) classes.
These materials are developed by fredhutch.io, 
the data and computational analysis training program at Fred Hutch. 

Sessions of these courses are periodically taught by instructors at Fred Hutch. The materials are also freely available for self-guided, work-at-your-own-pace study.

Information about RNAseq is available on the [Fred Hutch Biomedical Data Science Wiki](FIXME).

## RNAseq: Concepts

This four-class course introduces bulk RNAseq analysis for biomedical research,
and is designed for research scientists (lab, clinical, computational) who have no prior experience working with genomic data.
This course requires participants have a general understanding of the central dogma of molecular biology (DNA->RNA->protein),
but assumes no experience handling genomic data or performing computational analyses.
This course, or equivalent background knowledge, 
is a pre- or co-requisite for the skills course described below.

By the end of this course,
you should be able to:
- Identify data types and applications for bulk RNAseq analysis in biomedical research
- Design statistically robust RNAseq experiments
- Choose appropriate analytical approaches for RNAseq data
- Interpret common visualizations and hypothesis tests associated with RNAseq
- Connect data types, experimental design, and analysis methods to appropriately frame research questions and understand technical limitations of RNAseq analyses.

Please see each set of class materials for specific learning objectives. 

[[links to other materials that have been adapted in this lesson]]

### Concepts schedule

When taught by an instructor,
each of the four classes is scheduled for one hour.
The HackMD (interactive page used for sharing links and information) for instructor-led courses is [here](FIXME).

1. Introduction

By the end of this class, you should be able to:
- RNAseq workflow
- experimental design
  - replicates, read length, SE vs PE
  - balancing statistical power: number of samples vs sequencing depth; more samples better than deeper sequencing
- data types (mRNA stranded, mRNA non-stranded, rRNA depleted) and technical limitations of each
- quality assessment of data

2. Read mapping and quantification

By the end of this class, you should be able to:
- read mapping (tools and assessing quality)
- assemblies and annotations (human and mouse)
- gene level vs transcript level
- quantifying gene expression (htseq-count, cufflinks, RSEM)

3. Hypothesis and visualization

By the end of this class, you should be able to:
- Analysis tools: EdgeR, limma voom, DESeq
- visualizing results (MA-plot, volcano plot, heat map)

4. Contextualizing results, and mods to RNAseq

By the end of this class, you should be able to:
- GSEA, GOseq, GOrillia, etc
- isoforms & alternative splicing, lincRNAs, SNVs & RNA editing, multiple species (xenografts, viral, etc) 
- other types of RNA-seq: single-cell (sc) RNA-seq, small RNA-seq, Ribo-seq, nascent RNA-seq

## RNAseq: Skills

This four-class course introduces software and analysis methods asociated with bulk RNAseq analysis for biomedical research.
These genomics-focused materials are designed for research scientists with minimal prior coding experience who are interested in learning to perform their own analyses,
as well as computationally proficient staff who are interested in learning best practices for working with research software.
The concepts course listed above (or equivalent knowledge) is a pre- or co-requisite for this course.
As this class focuses on applying reproducible computational methods (e.g., computer coding) to interrogate bioinformatics data,
additional pre-requisites include Introduction to R (or equivalent knowledge). FIXME: basic familiarity with Unix command line (or one-hour crash course), include things this class doesn't include (developing workflows, Galaxy)

By the end of this course,
you should be able to:
- Manage data and organize projects associated with RNAseq experiments
- Recognize and interpret common file formats for genomic data, as well as software appropriate for interacting with such data
- Validate and assess quality of RNAseq data before, during, and after analysis
- Quantify RNAseq data at the gene level
- Create visualizations and test hypotheses

Please see each set of class materials for specific learning objectives. 

[[links to other materials that have been adapted in this lesson]]

Solutions for exercises can be found in [here](solutions/README.md).

### Skills schedule 

When taught by an instructor,
each of the four classes is scheduled for two hours.
The HackMD (interactive page used for sharing links and information) for instructor-led courses is [here](FIXME).

1. Introduction
By the end of this class, you should be able to:
- Organize files (data, code, results) associated with genomics projects (idiosyncratic things about Hutch infrastructure, including accessing Unix-stored data from Mac vs Windows)
- reproducibility
- QC of data
- data trimming and filtering

1. Read mapping and quantification
By the end of this class, you should be able to:
- mapping tools
- gene vs transcript
- pseudomapping
- IGV

3. Hypothesis testing
By the end of this class, you should be able to:
- Bioconductor 
- EdgeR, limma voom, DESeq

1. Visualization
By the end of this class, you should be able to:
- Create and customize
- MA-plot, volcano plot, heat map

Each class in this course includes code-along tutorials interspersed with challenge exercises.

*Required software:**

Software used in this course include:
- Unix shell (to access cluster)
- Text editor?
- IGV?

The links above reference relevant sections of [fredhutch.io's Software page](http://www.fredhutch.io/software/).

## For curriculum contributors and instructors

Please see the following resources for more information on:
- [**Teaching**](https://github.com/fredhutchio/instructors) these materials.
[`instructors.md`](instructors.md) includes information for instructors to facilitate teaching each lesson.
[`hackmdio.md`](hackio.md) is an archive of the [interactive webpage](https://hackmd.io) used during lessons.
- [**Contributing**](https://github.com/fredhutchio/curriculum_contribution) to lessons.
Each lesson's materials are described in markdown (`.md`) files
in the [GitHub repository](FIXME).
