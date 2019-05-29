---
layout: page
title: Bioinformatics Training Materials
---

On this page you will find a variety of curated training materials and tutorials related to bioinformatics, biostatistics, and general computational biology. They are broken down into two groups:

* [General Tutorials](#general-tutorials)
  * These are general overviews of a subject, code, or software.
* [Project-specific Materials](#project-specific-materials)
  * These are more specific training materials created in support of a particular project or course. 


## General Tutorials

* [Introduction to the Unix Shell](https://github.com/MaineINBRE/IntroToShell)
  * This tutorial is a modified form of the introduction to the Unix shell as offered by [Software Carpentry](https://software-carpentry.org). It focuses on teaching undergraduates the basic skills necessary to understand the shell and utilize command line tools.
  * Key Skills: Unix, Bash, Command Line

* [Introduction to Quality Assessment, FastQC, and Trimmomatic](https://github.com/MaineINBRE/IntroToFASTQCandTrimmomatic)
  * This tutorial is an introduction to the quality assessment step in a bioinformatics pipeline. It focuses on the most common file formats (FASTA/FASTQ), the motivation for and use of FastQC, and using Trimmomatic to trim paired-end reads. It is highly tailored to the use of the MDIBL Bioinformatics Core cluster to use example data.
  * Key Skills: FastQC, Trimmomatic

* [Introduction to TopHat](https://github.com/MaineINBRE/IntroToTopHat2)
  * This tutorial is an introduction to the [TopHat2](https://ccb.jhu.edu/software/tophat/index.shtml) software suite and its use in mapping RNA-seq reads. Though an incredible tool in any sequence analysis pipeline, this particular tutorial is highly tailored to the use of the MDIBL Bioinformatics Core. 
  * Key Skills: TopHat

* [Introduction to HTseq](https://github.com/MaineINBRE/IntroToHTSEQ)
  * This tutorial is an introduction to the `htseq-count` function in the [HTseq](http://www-huber.embl.de/users/anders/HTSeq/doc/index.html) computational environment. Though useful in many situations, it is highly tailored to the use of the MDIBL Bioinformatics Core. 
  * Key Skills: HTseq, Samtools

* [Introduction to NCBI and BLAST](https://github.com/MaineINBRE/IntroToNCBIandBLAST)
  * This tutorial was created for undergraduate students studying with Dr. Elizabeth Ehrenfeld at the [Southern Maine Community College](https://www.smccme.edu). It focuses primarily on learning how to navigate the NCBI website, perform simple queries, and understanding and perfomring BLAST alignments on simple sequences. 
  * Key Skills: BLAST, Entrez Search

* [Converting a Genbank file to a GTF file](https://github.com/MaineINBRE/GenBankToGTF)
  * This script was created to show how to quickly convert a raw Genbank file to a GTF file when a GTF file cannot be located. It was created for undergraduate students at [The University of Maine](www.umaine.edu). 
  * Key Skills: perl
  
***

## Project-specific Materials

* [Guide to RNA-Seq Analysis with Galaxy: pt.1](https://github.com/MaineINBRE/GilesRNASeqGuide)
  * This is a set of instructional materials for aligning RNA-seq reads from the *Giles* bacteriophage to the genome of its host, *Mycobacterium smegmatis*. This was done in support of the [The University of Maine's Honors College](https://honors.umaine.edu). The Github repo also contains a link to an RPub page. 
  * Key Skills: Galaxy

* [Guide to RNA-Seq Analysis with Galaxy: pt.2](https://github.com/MaineINBRE/GilesRNASeqGuide2)
  * This is a continuation of the above project. This is a set of instructional materials for aligning RNA-seq reads from the *Giles* bacteriophage to its own annotated genome. This was done in support of the [The University of Maine's Honors College](https://honors.umaine.edu). The Github repo also contains a link to an RPub page. 
  * Key Skills: Galaxy

* [Using DESeq2 to Perform Basic Differential Expression Analysis](https://github.com/MaineINBRE/GilesDESEQ2Guide)
  * This is a set of instructional materials for performing basic differential analysis on RNA-seq reads. It is explicitly designed to be the final module for the work on the *Giles* bacterioohage above. The Github repo also contains a link to an RPub page. 
  * Key Skills: R, Bioconductor, DESeq2 


