# Awesome Bioinformatics with stars

> Bioinformatics is an interdisciplinary field that develops methods and software tools for understanding biological data. — [Wikipedia](https://en.wikipedia.org/wiki/Bioinformatics)

A curated list of awesome Bioinformatics software, resources, and libraries. Mostly command line based, and free or open-source. Please feel free to [contribute](CONTRIBUTING.md)!

<!-- START doctoc generated TOC please keep comment here to allow auto update -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

## Table of Contents

* [Package suites](#package-suites)
* [Data Tools](#data-tools)
  * [Downloading](#downloading)
  * [Compressing](#compressing)
* [Data Processing](#data-processing)
  * [Command Line Utilities](#command-line-utilities)
* [Next Generation Sequencing](#next-generation-sequencing)
  * [Workflow Managers](#workflow-managers)
  * [Pipelines](#pipelines)
  * [Sequence Processing](#sequence-processing)
  * [Data Analysis](#data-analysis)
  * [Sequence Alignment](#sequence-alignment)
    * [Pairwise](#pairwise)
    * [Multiple Sequence Alignment](#multiple-sequence-alignment)
    * [Clustering](#clustering)
  * [Quantification](#quantification)
  * [Variant Calling](#variant-calling)
    * [Structural variant callers](#structural-variant-callers)
  * [BAM File Utilities](#bam-file-utilities)
  * [VCF File Utilities](#vcf-file-utilities)
  * [GFF BED File Utilities](#gff-bed-file-utilities)
  * [Variant Simulation](#variant-simulation)
  * [Variant Prediction/Annotation](#variant-predictionannotation)
  * [Python Modules](#python-modules)
    * [Data](#data)
    * [Tools](#tools)
  * [Assembly](#assembly)
  * [Annotation](#annotation)
* [Long-read sequencing](#long-read-sequencing)
  * [Long-read Assembly](#long-read-assembly)
* [Visualization](#visualization)
  * [Genome Browsers / Gene Diagrams](#genome-browsers--gene-diagrams)
  * [Circos Related](#circos-related)
* [Database Access](#database-access)
* [Resources](#resources)
  * [Becoming a Bioinformatician](#becoming-a-bioinformatician)
  * [Bioinformatics on GitHub](#bioinformatics-on-github)
  * [Sequencing](#sequencing)
  * [RNA-Seq](#rna-seq)
  * [ChIP-Seq](#chip-seq)
  * [YouTube Channels and Playlists](#youtube-channels-and-playlists)
  * [Blogs](#blogs)
  * [Miscellaneous](#miscellaneous)
* [Online networking groups](#online-networking-groups)
* [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

***

## Package suites

Package suites gather software packages and installation tools for specific languages or platforms. We have some for bioinformatics software.

* **[Biopython](https://github.com/biopython/biopython) ⭐ 5,164 | 🐛 608 | 🌐 Python | 📅 2026-08-06** - Freely available tools for biological computing in Python, with included cookbook, packaging and thorough documentation. Part of the [Open Bioinformatics Foundation](http://open-bio.org/). Contains the very useful [Entrez](https://biopython.org/DIST/docs/api/Bio.Entrez-module.html) package for API access to the NCBI databases. \[ [paper-2009](https://pubmed.ncbi.nlm.nih.gov/19304878) | [web](https://biopython.org) ]

* **[Rust-Bio](https://github.com/rust-bio/rust-bio) ⭐ 1,831 | 🐛 109 | 🌐 Rust | 📅 2026-07-27** - Rust implementations of algorithms and data structures useful for bioinformatics. \[ [paper-2016](http://bioinformatics.oxfordjournals.org/content/early/2015/10/06/bioinformatics.btv573.short?rss=1) ]

* **[(Poly)merase](https://github.com/TimothyStiles/poly) ⭐ 735 | 🐛 32 | 🌐 Go | 📅 2026-08-01** - A Go library and command line utility for engineering organisms.

* **[Biojava](https://github.com/biojava/biojava) ⭐ 630 | 🐛 79 | 🌐 Java | 📅 2026-08-13** - Java framework for processing biological data.

* **[SeqAn](https://github.com/seqan/seqan3) ⭐ 459 | 🐛 34 | 🌐 C++ | 📅 2026-08-15** - The modern C++ library for sequence analysis.

* **[Bioperl](https://github.com/bioperl/bioperl-live) ⭐ 320 | 🐛 64 | 🌐 Perl | 📅 2026-06-26** - International association of users & developers of open source Perl tools for bioinformatics, genomics and life sciences. \[ [paper-2002](https://doi.org/10.1101%2Fgr.361602) | [web](https://bioperl.org) ]

* **[Biocaml](https://github.com/biocaml/biocaml) ⭐ 125 | 🐛 36 | 🌐 OCaml | 📅 2025-11-26** - Biocaml aims to be a high-performance user-friendly library for Bioinformatics.

* **[Bioconductor](https://github.com/Bioconductor)** - A plethora of tools for analysis and comprehension of high-throughput genomic data, including 1500+ software packages. \[ [paper-2004](https://link.springer.com/article/10.1186/gb-2004-5-10-r80) | [web](https://www.bioconductor.org) ]

* **[Bioconda](https://github.com/bioconda)** - A channel for the [conda package manager](http://conda.pydata.org/docs/intro.html) specializing in bioinformatics software. Includes a repository with 3000+ ready-to-install (with `conda install`) bioinformatics packages. \[ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/29967506) | [web](https://bioconda.github.io) ]

* **[BioJulia](https://github.com/BioJulia)** - Bioinformatics and computational biology infastructure for the Julia programming language. \[ [web](https://biojulia.net) ]

## Data Tools

### Downloading

* **[SRA-Explorer](https://github.com/ewels/sra-explorer) ⭐ 224 | 🐛 10 | 🌐 HTML | 📅 2025-07-17** - Easily get SRA download links and other information. \[ [web](https://sra-explorer.info) ]
* **[GGD](https://github.com/gogetdata/ggd-cli) ⭐ 42 | 🐛 4 | 🌐 Python | 📅 2022-10-16** - Go Get Data; A command line interface for obtaining genomic data. \[ [web](https://gogetdata.github.io) ]

### Compressing

* **[Genozip](https://github.com/divonlan/genozip) ⭐ 190 | 🐛 0 | 🌐 C | 📅 2026-08-16** - A compressor of common genomic file formats (BAM, CRAM, FASTQ, VCF etc). \[ [web](https://genozip.com/?utm_source=Awesome-Bioinformatics) | [paper-2021](https://www.researchgate.net/publication/349347156_Genozip_-_A_Universal_Extensible_Genomic_Data_Compressor) ]

## Data Processing

### Command Line Utilities

* **[CSVKit](https://github.com/wireservice/csvkit) ⭐ 6,408 | 🐛 39 | 🌐 Python | 📅 2026-08-03** - Utilities for working with CSV/Tab-delimited files. \[ [web](https://csvkit.readthedocs.io/en/latest) ]
* **[Bioinformatics One Liners](https://github.com/stephenturner/oneliners) ⭐ 2,025 | 🐛 5 | 📅 2023-09-09** - Git repo of useful single line commands.
* **[csvtk](https://github.com/shenwei356/csvtk) ⭐ 1,166 | 🐛 15 | 🌐 Go | 📅 2026-07-29** - Another cross-platform, efficient, practical and pretty CSV/TSV toolkit. \[ [web](https://bioinf.shenwei.me/csvtk) ]
* **[zindex](https://github.com/mattgodbolt/zindex) ⭐ 659 | 🐛 19 | 🌐 C | 📅 2022-12-30** - Create an index on a compressed text file.
* **[BioNode](https://github.com/bionode/bionode) ⚠️ Archived** - Modular and universal bioinformatics, Bionode provides pipeable UNIX command line tools and JavaScript APIs for bioinformatics analysis workflows. \[ [web](http://bionode.io) ]
* **[bioSyntax](https://github.com/bioSyntax/bioSyntax) ⭐ 273 | 🐛 15 | 🌐 Shell | 📅 2023-03-04** - Syntax Highlighting for Computational Biology file formats (SAM, VCF, GTF, FASTA, PDB, etc...) in vim/less/gedit/sublime. \[ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/30134911) | [web](http://www.bioSyntax.org) ]
* **[tabix](https://github.com/samtools/tabix) ⚠️ Archived** - Table file index. \[ [paper-2011](https://pubmed.ncbi.nlm.nih.gov/21208982) ]
* **[grabix](https://github.com/arq5x/grabix) ⭐ 86 | 🐛 17 | 🌐 C | 📅 2018-05-10** - A wee tool for random access into BGZF files.
* **[grepq](https://github.com/Rbfinch/grepq) ⭐ 60 | 🐛 5 | 🌐 Rust | 📅 2026-04-18** - Fast FASTQ filtering by matching reads against one or more regex patterns.
* **[gsort](https://github.com/brentp/gsort) ⭐ 36 | 🐛 2 | 🌐 Go | 📅 2025-11-07** - Sort genomic files according to a specified order.
* **[easy\_qsub](https://github.com/shenwei356/easy_qsub) ⭐ 29 | 🐛 1 | 🌐 Python | 📅 2023-05-24** - Easily submitting PBS jobs with script template. Multiple input files supported.
* **[wormtable](https://github.com/wormtable/wormtable) ⭐ 27 | 🐛 11 | 🌐 Python | 📅 2023-10-05** - Write-once-read-many table for large datasets.
* **[datamash](https://git.savannah.gnu.org/gitweb/?p=datamash.git)** - Data transformations and statistics. \[ [web](http://www.gnu.org/software/datamash) ]
* **GNU Parallel** - General parallelizer that runs jobs in parallel on a single multi-core machine. [Here](https://www.biostars.org/p/63816/) are some example scripts using GNU Parallel. \[ [web](http://www.gnu.org/software/parallel) ]

## Next Generation Sequencing

### Workflow Managers

* **[Nextflow](https://github.com/nextflow-io/nextflow) ⭐ 3,466 | 🐛 428 | 🌐 Groovy | 📅 2026-08-17 (recommended)** - A fluent DSL modelled around the UNIX pipe concept, that simplifies writing parallel and scalable pipelines in a portable manner. \[ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/29412134) | [web](http://nextflow.io) ]
* **[Common Workflow Language](https://github.com/common-workflow-language/common-workflow-language) ⭐ 1,480 | 🐛 241 | 🌐 Common Workflow Language | 📅 2026-08-15** - a specification for describing analysis workflows and tools that are portable and scalable across a variety of software and hardware environments, from workstations to cluster, cloud, and high performance computing (HPC) environments. \[ [web](http://www.commonwl.org) ]
* **[SciPipe](https://github.com/scipipe/scipipe) ⭐ 1,109 | 🐛 57 | 🌐 Go | 📅 2024-08-14** - Workflow library embedded in the Go programming language, focusing on supporting complex workflow constructs, compiling to a single binary, providing powerful file naming and comprehensive audit reports for every output \[ [paper-2019](https://pubmed.ncbi.nlm.nih.gov/31029061/) | [web](https://scipipe.org/) ]
* **[Cromwell](https://github.com/broadinstitute/cromwell) ⭐ 1,080 | 🐛 813 | 🌐 Scala | 📅 2026-08-04** - A Workflow Management System geared towards scientific workflows. \[ [web](https://cromwell.readthedocs.io) ]
* **[redun](https://github.com/insitro/redun) ⭐ 597 | 🐛 33 | 🌐 Python | 📅 2026-07-17** - A python-based workflow manager.
* **[Bpipe](https://github.com/ssadedin/bpipe) ⭐ 242 | 🐛 158 | 🌐 Groovy | 📅 2026-08-17** - A small language for defining pipeline stages and linking them together to make pipelines. \[ [web](http://docs.bpipe.org) ]
* **[Ruffus](https://github.com/cgat-developers/ruffus) ⭐ 175 | 🐛 49 | 🌐 Python | 📅 2021-07-12** - Computation Pipeline library for python widely used in science and bioinformatics. \[ [paper-2010](https://pubmed.ncbi.nlm.nih.gov/20847218) | [web](http://www.ruffus.org.uk) ]
* **[BigDataScript](https://github.com/pcingola/BigDataScript) ⭐ 92 | 🐛 11 | 🌐 Shell | 📅 2021-03-31** - A cross-system scripting language for working with big data pipelines in computer systems of different sizes and capabilities. \[ [paper-2014](https://pubmed.ncbi.nlm.nih.gov/25189778) | [web](https://pcingola.github.io/BigDataScript) ]
* **[SeqWare](https://github.com/SeqWare/seqware) ⭐ 30 | 🐛 5 | 🌐 Java | 📅 2018-07-09** - Hadoop Oozie-based workflow system focused on genomics data analysis in cloud environments. \[ [paper-2010](https://pubmed.ncbi.nlm.nih.gov/21210981) | [web](https://seqware.github.io) ]
* **[Workflow Descriptor Language](https://github.com/broadinstitute/wdl) ⚠️ Archived** - Workflow standard developed by the Broad. \[ [web](https://software.broadinstitute.org/wdl) ]
* **[Galaxy](https://github.com/galaxyproject)** - a popular open-source, web-based platform for data intensive biomedical research. Has several features, from data analysis to workflow management to visualization tools. \[ [paper-2018](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6030816) | [web](https://galaxyproject.org) ]
* **[Snakemake](https://bitbucket.org/snakemake)** - A workflow management system in Python that aims to reduce the complexity of creating workflows by providing a fast and comfortable execution environment. \[ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/29788404) | [web](https://snakemake.readthedocs.io) ]

### Pipelines

* **[Awesome-Pipeline](https://github.com/pditommaso/awesome-pipeline) ⭐ 6,619 | 🐛 34 | 📅 2026-08-04** - A list of pipeline resources.
* **[bcbio-nextgen](https://github.com/chapmanb/bcbio-nextgen) ⭐ 1,030 | 🐛 133 | 🌐 Python | 📅 2024-08-24** - Batteries included genomic analysis pipeline for variant and RNA-Seq analysis, structural variant calling, annotation, and prediction. \[ [web](https://bcbio-nextgen.readthedocs.io) ]
* **[Bactopia](https://github.com/bactopia/bactopia/) ⭐ 522 | 🐛 62 | 🌐 Nextflow | 📅 2026-08-05** - A flexible pipeline, built with Nextflow, for the complete analysis of bacterial genomes. \[ [web](https://bactopia.github.io/) ]
* **[Bacannot](https://github.com/fmalmeida/bacannot) ⭐ 109 | 🐛 10 | 🌐 Nextflow | 📅 2026-01-22** - A generic but comprehensive bacterial annotation pipeline, built with Nextflow, with nice graphical options for investigating results. \[ [web](https://bacannot.readthedocs.io/en/latest/?badge=latest) ]
* **[ngs-preprocess](https://github.com/fmalmeida/ngs-preprocess) ⭐ 36 | 🐛 4 | 🌐 Nextflow | 📅 2024-06-30** - A pipeline for preprocessing short and long sequencing reads, built with Nextflow. \[ [web](https://ngs-preprocess.readthedocs.io/en/latest/?badge=latest) ]
* **[R-Peridot](https://github.com/pentalpha/r-peridot) ⭐ 7 | 🐛 0 | 🌐 Java | 📅 2019-10-15** - Customizable pipeline for differential expression analysis with an intuitive GUI. \[ [web](http://www.bioinformatics-brazil.org/r-peridot) ]

### Sequence Processing

Sequence Processing includes tasks such as demultiplexing raw read data, and trimming low quality bases.

* **[SeqKit](https://github.com/shenwei356/seqkit) ⭐ 1,589 | 🐛 19 | 🌐 Go | 📅 2026-07-08** - A cross-platform and ultrafast toolkit for FASTA/Q file manipulation in Golang. \[ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/27706213) | [web](https://bioinf.shenwei.me/seqkit) ]
* **[Seqtk](https://github.com/lh3/seqtk) ⭐ 1,553 | 🐛 69 | 🌐 C | 📅 2025-06-01** - Toolkit for processing sequences in FASTA/Q formats.
* **[MultiQC](https://github.com/ewels/MultiQC) ⭐ 1,488 | 🐛 294 | 🌐 JavaScript | 📅 2026-08-12** - Aggregate results from bioinformatics analyses across many samples into a single report. \[ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/27312411) | [web](http://multiqc.info) ]
* **[FastQC](https://github.com/s-andrews/FastQC) ⭐ 612 | 🐛 30 | 🌐 Java | 📅 2026-07-20** - A quality control tool for high throughput sequence data. \[ [web](http://www.bioinformatics.babraham.ac.uk/projects/fastqc) ]
* **[AfterQC](https://github.com/OpenGene/AfterQC) ⭐ 213 | 🐛 27 | 🌐 Python | 📅 2020-05-14** - Automatic Filtering, Trimming, Error Removing and Quality Control for fastq data. \[ [paper-2017](https://pubmed.ncbi.nlm.nih.gov/28361673) ]
* **[Fastx Tookit](https://github.com/agordon/fastx_toolkit) ⭐ 202 | 🐛 12 | 🌐 C | 📅 2022-03-04** - FASTQ/A short-reads pre-processing tools: Demultiplexing, trimming, clipping, quality filtering, and masking utilities. \[ [web](http://hannonlab.cshl.edu/fastx_toolkit) ]
* **[SeqFu](https://github.com/telatin/seqfu2) ⭐ 129 | 🐛 0 | 🌐 Nim | 📅 2026-08-15** - Sequence manipulation toolkit for FASTA/FASTQ files written in Nim. \[ [paper-2021](https://www.mdpi.com/2306-5354/8/5/59) | [web](https://telatin.github.io/seqfu2/) ]
* **[seqmagick](https://github.com/fhcrc/seqmagick) ⭐ 120 | 🐛 16 | 🌐 Python | 📅 2024-03-18** - file format conversion in Biopython in a convenient way. \[ [web](http://seqmagick.readthedocs.io) ]
* **[Fastqp](https://github.com/mdshw5/fastqp) ⭐ 109 | 🐛 13 | 🌐 Python | 📅 2026-02-24** - FASTQ and SAM quality control using Python.
* **[smof](https://github.com/incertae-sedis/smof) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2024-08-01** - UNIX-style FASTA manipulation tools.

### Data Analysis

The following items allow for scalable genomic analysis by introducing specialized databases.

* **[Hail](https://github.com/hail-is/hail) ⭐ 1,069 | 🐛 362 | 🌐 Python | 📅 2026-08-14** - Scalable genomic analysis.
* **[GLNexus](https://github.com/dnanexus-rnd/GLnexus) ⭐ 187 | 🐛 103 | 🌐 C++ | 📅 2024-04-12** - Scalable gVCF merging and joint variant calling for population sequencing projects. \[ [paper-2018](https://www.biorxiv.org/content/10.1101/343970v1.abstract) ]

### Sequence Alignment

#### Pairwise

* **[BWA](https://github.com/lh3/bwa) ⭐ 1,764 | 🐛 99 | 🌐 C | 📅 2026-08-07** - Burrow-Wheeler Aligner for pairwise alignment between DNA sequences.
* **[DIAMOND](https://github.com/bbuchfink/diamond) ⭐ 1,314 | 🐛 216 | 🌐 C++ | 📅 2026-08-04** - An ultrafast protein aligner for `blastp` and `blastx` like searches. \[ [paper-2021](https://www.nature.com/articles/s41592-021-01101-x) ]
* **[Bowtie 2](https://github.com/BenLangmead/bowtie2) ⭐ 809 | 🐛 194 | 🌐 C++ | 📅 2026-06-01** - An ultrafast and memory-efficient tool for aligning sequencing reads to long reference sequences. \[ [paper-2012](https://pubmed.ncbi.nlm.nih.gov/22388286) | [web](http://bowtie-bio.sourceforge.net/bowtie2) ]
* **[MUMmer](https://github.com/mummer4/mummer) ⭐ 571 | 🐛 167 | 🌐 C++ | 📅 2025-02-04** -  A system for rapidly aligning entire genomes, whether in complete or draft form. \[ [paper-1999](http://mummer.sourceforge.net/MUMmer.pdf) | [paper-2002](http://mummer.sourceforge.net/MUMmer2.pdf) | [paper-2004](http://mummer.sourceforge.net/MUMmer3.pdf) | [web](http://mummer.sourceforge.net) ]
* **[Parasail](https://github.com/jeffdaily/parasail) ⭐ 286 | 🐛 34 | 🌐 C | 📅 2025-08-27** - SIMD C library for global, semi-global, and local pairwise sequence alignments \[ [paper-2016](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-016-0930-z) ]
* **[WFA](https://github.com/smarco/WFA) ⭐ 223 | 🐛 18 | 🌐 C | 📅 2026-08-07** - the wavefront alignment algorithm (WFA) which expoit sequence similarity to speed up alignment \[ [paper-2020](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btaa777/5904262) ]
* **[BWA-FastAlign](https://github.com/zzhofict/BWA-FastAlign) ⭐ 27 | 🐛 6 | 🌐 C | 📅 2026-02-22** - BWA-MEM drop-in replacement: 2-3x faster, 2-5x cheaper, 100% identical output on standard CPUs. \[ [paper-2026](https://dl.acm.org/doi/10.1145/3774934.3786421) ]

#### Multiple Sequence Alignment

* **[POA](https://github.com/ljdursi/poapy) ⭐ 76 | 🐛 0 | 🌐 Python | 📅 2024-06-20** - Partial-Order Alignment for fast alignment and consensus of multiple homologous sequences. \[ [paper-2002](https://academic.oup.com/bioinformatics/article/18/3/452/236691) ]

#### Clustering

* **[MMseqs2](https://github.com/soedinglab/MMseqs2) ⭐ 2,127 | 🐛 284 | 🌐 C | 📅 2026-08-14** - Ultra-fast, sensitive search and clustering suite for protein and nucleotide sequence sets. \[ [paper-2017](https://www.nature.com/articles/nbt.3988) | [paper-2018](https://www.nature.com/articles/s41467-018-04964-5) ]

### Quantification

* **[RSEM](https://github.com/deweylab/RSEM) ⭐ 474 | 🐛 144 | 🌐 C++ | 📅 2026-08-07** - A software package for estimating gene and isoform expression levels from RNA-Seq data. \[ [paper-2011](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-12-323) | [web](http://deweylab.github.io/RSEM/) ]
* **[Cufflinks](https://github.com/cole-trapnell-lab/cufflinks) ⭐ 323 | 🐛 89 | 🌐 C++ | 📅 2020-03-31** - Cufflinks assembles transcripts, estimates their abundances, and tests for differential expression and regulation in RNA-Seq samples. \[ [paper-2010](https://www.nature.com/articles/nbt.1621) ]

### Variant Calling

* **[DeepVariant](https://github.com/google/deepvariant) ⭐ 3,782 | 🐛 5 | 🌐 Python | 📅 2026-03-19** - Deep learning-based variant caller \[ [paper-2018](https://rdcu.be/7Dhl) ]
* **[bcftools](https://github.com/samtools/bcftools) ⭐ 884 | 🐛 348 | 🌐 C | 📅 2026-07-30** - samtools/bcftools are a suite of tools for manipulating NGS data and can be used to call variants. \[ [paper-2009](https://pubmed.ncbi.nlm.nih.gov/19505943) | [web](http://htslib.org) ]
* **[freebayes](https://github.com/ekg/freebayes) ⭐ 876 | 🐛 48 | 🌐 C++ | 📅 2026-04-20** - Bayesian haplotype-based polymorphism discovery and genotyping. \[ [web](http://arxiv.org/abs/1207.3907) ]
* **[Octopus](https://github.com/luntergroup/octopus) ⭐ 325 | 🐛 65 | 🌐 C++ | 📅 2026-02-13** - A polymorphic bayesian genotyping model with wide applicability. \[ [paper-2021](https://www.nature.com/articles/s41587-021-00861-3) ]
* **[GATK](https://github.com/broadgsa/gatk) ⭐ 302 | 🐛 0 | 🌐 Java | 📅 2018-08-22** - Variant Discovery in High-Throughput Sequencing Data. \[ [web](https://software.broadinstitute.org/gatk) ]

#### Structural variant callers

* **[Delly](https://github.com/dellytools/delly) ⭐ 528 | 🐛 38 | 🌐 C++ | 📅 2026-08-17** - Structural variant discovery by integrated paired-end and split-read analysis. \[ [paper-2012](https://pubmed.ncbi.nlm.nih.gov/22962449) ]
* **[manta](https://github.com/Illumina/manta) ⚠️ Archived** - Structural variant and indel caller for mapped sequencing data. \[ [paper-2015](https://pubmed.ncbi.nlm.nih.gov/26647377) ]
* **[lumpy](https://github.com/arq5x/lumpy-sv) ⭐ 345 | 🐛 197 | 🌐 C | 📅 2026-02-22** - lumpy: a general probabilistic framework for structural variant discovery. \[ [paper-2014](https://link.springer.com/article/10.1186/gb-2014-15-6-r84) ]
* **[gridss](https://github.com/PapenfussLab/gridss) ⭐ 284 | 🐛 95 | 🌐 Java | 📅 2025-05-21** - GRIDSS: the Genomic Rearrangement IDentification Software Suite. \[ [paper-2017](https://pubmed.ncbi.nlm.nih.gov/29097403) ]
* **[smoove](https://github.com/brentp/smoove) ⭐ 265 | 🐛 101 | 🌐 Go | 📅 2024-06-17** - structural variant calling and genotyping with existing tools, but,smoothly.

### BAM File Utilities

* **[mosdepth](https://github.com/brentp/mosdepth) ⭐ 869 | 🐛 49 | 🌐 Nim | 📅 2026-05-02** - fast BAM/CRAM depth calculation for WGS, exome, or targeted sequencing. \[ [paper-2017](https://pubmed.ncbi.nlm.nih.gov/29096012/) ]
* **[Bamtools](https://github.com/pezmaster31/bamtools) ⭐ 432 | 🐛 72 | 🌐 C++ | 📅 2025-05-18** - Collection of tools for working with BAM files. \[ [paper-2011](https://academic.oup.com/bioinformatics/article/27/12/1691/255399) ]
* **[Somalier](https://github.com/brentp/somalier) ⭐ 332 | 🐛 61 | 🌐 Nim | 📅 2026-07-20** - Fast sample-swap and relatedness checks on BAMs/CRAMs/VCFs/GVCFs. \[ [paper-2020](https://pubmed.ncbi.nlm.nih.gov/32664994) ]
* **[Telseq](https://github.com/zd1/telseq) ⭐ 77 | 🐛 14 | 🌐 C++ | 📅 2018-10-24** - Telseq is a tool for estimating telomere length from whole genome sequence data. \[ [paper-2014](https://academic.oup.com/nar/article/42/9/e75/1249448) ]
* **[SAMstat](https://github.com/TimoLassmann/samstat) ⭐ 24 | 🐛 4 | 🌐 C | 📅 2023-08-03** - Displaying sequence statistics for next-generation sequencing. \[ [paper-2010](https://academic.oup.com/bioinformatics/article/27/1/130/201972) | [web](http://samstat.sourceforge.net) ]
* **[mergesam](https://github.com/DarwinAwardWinner/mergesam) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2013-04-25** - Automate common SAM & BAM conversions.
* **[bam toolbox](https://github.com/AndersenLab/bam-toolbox) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2024-07-30** MtDNA:Nuclear Coverage; BAM Toolbox can output the ratio of MtDNA:nuclear coverage, a proxy for mitochondrial content.

### VCF File Utilities

* **[bcftools](https://github.com/samtools/bcftools) ⭐ 884 | 🐛 348 | 🌐 C | 📅 2026-07-30** - Set of tools for manipulating VCF files. \[ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/26826718) | [paper-2017](https://pubmed.ncbi.nlm.nih.gov/28205675) | [web](http://samtools.github.io/bcftools) ]
* **[vcflib](https://github.com/vcflib/vcflib) ⭐ 683 | 🐛 22 | 🌐 C++ | 📅 2026-03-20** - A C++ library for parsing and manipulating VCF files.
* **[vcftools](https://github.com/vcftools/vcftools) ⭐ 562 | 🐛 119 | 🌐 C++ | 📅 2025-05-15** - VCF manipulation and statistics (e.g. linkage disequilibrium, allele frequency, Fst). \[ [paper-2011](https://pubmed.ncbi.nlm.nih.gov/21653522) ]
* **[vcfanno](https://github.com/brentp/vcfanno) ⭐ 404 | 🐛 37 | 🌐 Go | 📅 2026-06-16** - Annotate a VCF with other VCFs/BEDs/tabixed files. \[ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/27250555) ]

### GFF BED File Utilities

* **[Bedtools2](https://github.com/arq5x/bedtools2) ⭐ 1,045 | 🐛 284 | 🌐 C | 📅 2026-06-10** - A Swiss Army knife for genome arithmetic. \[ [paper-2010](https://pubmed.ncbi.nlm.nih.gov/20110278) | [paper-2014](https://pubmed.ncbi.nlm.nih.gov/25199790) | [web](https://bedtools.readthedocs.io) ]
* **[AGAT](https://github.com/NBISweden/AGAT) ⭐ 584 | 🐛 33 | 🌐 HTML | 📅 2026-05-18** - Suite of tools to handle gene annotations in any GTF/GFF format. \[ [web](https://agat.readthedocs.io/en/latest/?badge=latest) ]
* **[gffutils](https://github.com/daler/gffutils) ⭐ 319 | 🐛 17 | 🌐 Python | 📅 2026-03-31** - GFF and GTF file manipulation and interconversion. \[ [web](http://daler.github.io/gffutils) ]
* **[BEDOPS](https://bedops.readthedocs.io/en/latest/index.html)** - The fast, highly scalable and easily-parallelizable genome analysis toolkit. \[ [paper-2012](https://academic.oup.com/bioinformatics/article/28/14/1919/218826) ]

### Variant Simulation

* **[wgsim](https://github.com/lh3/wgsim) ⭐ 287 | 🐛 21 | 🌐 C | 📅 2021-09-03** - **Comes with samtools!** - Reads simulator. \[ [web](https://popmodels.cancercontrol.cancer.gov/gsr/packages/wgsim) ]
* **[Bam Surgeon](https://github.com/adamewing/bamsurgeon) ⭐ 251 | 🐛 41 | 🌐 Python | 📅 2026-08-05** - Tools for adding mutations to existing `.bam` files, used for testing mutation callers. \[ [web](https://popmodels.cancercontrol.cancer.gov/gsr/packages/bamsurgeon) ]

### Variant Prediction/Annotation

* **[SIFT](https://github.com/teamdfir/sift) ⭐ 550 | 🐛 19 | 📅 2024-02-14** - Predicts whether an amino acid substitution affects protein function. \[ [paper-2003](https://pubmed.ncbi.nlm.nih.gov/12824425) | [web](http://sift.jcvi.org) ]
* **[SnpEff](https://github.com/pcingola/SnpEff) ⭐ 312 | 🐛 17 | 🌐 Java | 📅 2026-03-09** - Genetic variant annotation and effect prediction toolbox. \[ [paper-2012](https://www.tandfonline.com/doi/full/10.4161/fly.19695) | [web](https://pcingola.github.io/SnpEff) ]
* **[Ensembl VEP](https://anaconda.org/bioconda/ensembl-vep)** - The VEP determines the effect of your variants (SNPs, insertions, deletions, CNVs or structural variants) on genes, transcripts, and protein sequence, as well as regulatory regions. \[ [paper-2016](https://doi.org/10.1186/s13059-016-0974-4) | [web](http://www.ensembl.org/info/docs/tools/vep/index.html) ]
* **[ANNOVAR](https://annovar.openbioinformatics.org/en/latest/)** - An annotation tool for genetic variants, predicting effects on genes, transcripts, and regulatory elements, which allows for custom database integration. \[ [paper-2010](https://doi.org/10.1093/nar/gkq603) | [web](https://annovar.openbioinformatics.org/en/latest/) ]

### Python Modules

#### Data

* **[pyensembl](https://github.com/openvax/pyensembl) ⭐ 406 | 🐛 6 | 🌐 Python | 📅 2026-07-08** - Pythonic Access to the Ensembl database. \[ [web](https://pyensembl.readthedocs.io/en/latest/pyensembl.html) ]
* **[bioservices](https://github.com/cokelaer/bioservices) ⭐ 341 | 🐛 5 | 🌐 Python | 📅 2026-06-12** - Access to Biological Web Services from Python. \[ [paper-2013](https://academic.oup.com/bioinformatics/article/29/24/3241/194040) [web](http://bioservices.readthedocs.io) ]
* **[cruzdb](https://github.com/brentp/cruzdb) ⭐ 138 | 🐛 13 | 🌐 Python | 📅 2020-08-27** - Pythonic access to the UCSC Genome database. \[ [paper-2013](https://academic.oup.com/bioinformatics/article/29/23/3003/248468) ]

#### Tools

* **[Scanpy](https://github.com/scverse/scanpy) ⭐ 2,542 | 🐛 526 | 🌐 Python | 📅 2026-08-17** - Scalable toolkit for analyzing single-cell gene expression data, including preprocessing, visualization, clustering, and trajectory inference. \[ [paper-2018](https://doi.org/10.1186/s13059-017-1382-0) | [web](https://scanpy.readthedocs.io) ]
* **[pysam](https://github.com/pysam-developers/pysam) ⭐ 904 | 🐛 266 | 🌐 Cython | 📅 2026-08-10** - Python wrapper for [samtools](https://github.com/samtools/samtools) ⭐ 1,939 | 🐛 196 | 🌐 C | 📅 2026-08-17. \[ [web](https://pysam.readthedocs.io/en/latest/api.html) ]
* **[pyfaidx](https://github.com/mdshw5/pyfaidx) ⭐ 489 | 🐛 3 | 🌐 Python | 📅 2026-03-19** - Pythonic access to FASTA files.
* **[cyvcf2](https://github.com/brentp/cyvcf2) ⭐ 446 | 🐛 47 | 🌐 Cython | 📅 2026-06-25** - Cython + HTSlib == fast VCF parsing; even faster parsing than pyVCF. \[ [paper-2017](https://pubmed.ncbi.nlm.nih.gov/28165109) | [web](https://brentp.github.io/cyvcf2) ]
* **[pyVCF](https://github.com/jamescasbon/PyVCF) ⭐ 419 | 🐛 100 | 🌐 Python | 📅 2023-09-22** - A VCF Parser for Python. \[ [web](http://pyvcf.readthedocs.org/en/latest/index.html) ]
* **[pyBedTools](https://github.com/daler/pybedtools) ⭐ 330 | 🐛 22 | 🌐 Python | 📅 2025-03-16** - Python wrapper for [bedtools](https://github.com/arq5x/bedtools) ⭐ 143 | 🐛 74 | 🌐 C++ | 📅 2021-05-28. \[ [paper-2011](https://pubmed.ncbi.nlm.nih.gov/21949271) | [web](http://daler.github.io/pybedtools) ]
* **[polars-bio](https://github.com/biodatageeks/polars-bio) ⭐ 190 | 🐛 46 | 🌐 Python | 📅 2026-08-17** - Python library for blazing-fast genomic interval operations and genomic file formats I/O on Polars DataFrames \[ [paper-2025](https://doi.org/10.1093/bioinformatics/btaf640) | \[ [web](https://biodatageeks.org/polars-bio/) ] ]
* **[cyvcf](https://github.com/arq5x/cyvcf) ⭐ 53 | 🐛 12 | 🌐 Python | 📅 2018-03-27** - A port of [pyVCF](https://github.com/jamescasbon/PyVCF) ⭐ 419 | 🐛 100 | 🌐 Python | 📅 2023-09-22 using Cython for speed.

### Assembly

* **[Minimap2](https://github.com/lh3/minimap2) ⭐ 2,235 | 🐛 74 | 🌐 C | 📅 2026-05-19** - Minimap2 is an pairwise aligner for genomic and spliced nucleotide sequences. It can perform the assembly-to-assembly alignment, and works with gzip'd FASTQ, FASTA formats. It also finds overlaps between long-reads.
* **[SPAdes](https://github.com/ablab/spades) ⭐ 955 | 🐛 303 | 🌐 C++ | 📅 2026-06-16** - SPAdes (St. Petersburg genome assembler) is an assembly toolkit containing various assembly pipelines and the de-facto standard for prokaryotic genome assemblies.
* **[SKESA](https://github.com/ncbi/SKESA) ⭐ 127 | 🐛 22 | 🌐 C++ | 📅 2024-10-11** - SKESA is a de-novo sequence read assembler for microbial genomes. It uses conservative heuristics and is designed to create breaks at repeat regions in the genome. This leads to excellent sequence quality without significantly compromising contiguity.
* **[D-GENIES](https://dgenies.toulouse.inra.fr/)** - **D**ot plot large **Gen**omes in an **I**nteractive, **E**fficient and **S**imple way. It is an online tool designed to support large genome, compare two genomes, and you can interact with the dot plot to improve the visualisation. It can also be used for extension of minimap2 by uploading the output generated in PAF(Pairwise mApping Format) or MAF(Multiple Alignment File) alignment files to D-GENIES

### Annotation

* **[Prokka](https://github.com/tseemann/prokka) ⭐ 992 | 🐛 244 | 🌐 Perl | 📅 2026-01-06** - Prokka: rapid prokaryotic genome annotation. Prokka is one of the most cited annotation command line tools for microbial genome annotations.
* **[Bakta](https://github.com/oschwengers/bakta) ⭐ 666 | 🐛 26 | 🌐 Python | 📅 2026-08-07** - Bakta is a tool for the rapid & standardized annotation of bacterial genomes & plasmids. It provides dbxref-rich and sORF-including annotations in machine-readable JSON & bioinformatics standard file formats for automatic downstream analysis.

## Long-read sequencing

### Long-read Assembly

* **[flye](https://github.com/fenderglass/Flye) ⭐ 948 | 🐛 18 | 🌐 C | 📅 2026-04-03** - De novo assembler for single molecule sequencing reads using repeat graphs.
* **[hifiasm](https://github.com/chhylp123/hifiasm) ⭐ 803 | 🐛 614 | 🌐 C++ | 📅 2026-05-31** - A haplotype-resolved assembler for accurate Hifi reads.
* **[canu](https://github.com/marbl/canu) ⭐ 707 | 🐛 5 | 🌐 C++ | 📅 2026-06-18** - A single molecule sequence assembler for genomes large and small.
* **[wtdbg2](https://github.com/ruanjue/wtdbg2) ⭐ 531 | 🐛 42 | 🌐 C | 📅 2023-09-27** -  A fuzzy Bruijn graph approach to long noisy reads assembly

## Visualization

### Genome Browsers / Gene Diagrams

The following tools can be used to visualize genomic data or for constructing customized visualizations of genomic data including sequence data from DNA-Seq, RNA-Seq, and ChIP-Seq, variants, and more.

* **[IGV js](https://github.com/igvteam/igv) ⭐ 757 | 🐛 196 | 🌐 Java | 📅 2026-08-06** - Java-based browser. Fast, efficient, scalable visualization tool for genomics data and annotations. Handles a large variety of formats. \[ [paper-2019](https://pubmed.ncbi.nlm.nih.gov/31099383) | [web](https://software.broadinstitute.org/software/igv) ]
* **[BioJS](https://github.com/biojs/biojs) ⭐ 506 | 🐛 57 | 📅 2021-10-11** - BioJS is a library of over hundred JavaScript components enabling you to visualize and process data using current web technologies. \[ [paper-2014](https://pubmed.ncbi.nlm.nih.gov/25075290/) | [web](http://biojs.net/) ]
* **[JBrowse](https://github.com/GMOD/jbrowse) ⭐ 474 | 🐛 158 | 🌐 JavaScript | 📅 2026-07-16** - JavaScript genome browser that is highly customizable via plugins and track customizations. \[ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/27072794) | [web](http://jbrowse.org/) ]
* **[pileup.js](https://github.com/hammerlab/pileup.js) ⭐ 281 | 🐛 83 | 🌐 JavaScript | 📅 2021-10-26** - JavaScript library that can be used to generate interactive and highly customizable web-based genome browsers. \[ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/27153605) ]
* **[biodalliance](https://github.com/dasmoth/dalliance) ⭐ 229 | 🐛 68 | 🌐 JavaScript | 📅 2019-08-28** - Embeddable genome viewer. Integration data from a wide variety of sources, and can load data directly from popular genomics file formats including bigWig, BAM, and VCF.
  \[ [paper-2011](https://pubmed.ncbi.nlm.nih.gov/21252075) | [web](http://www.biodalliance.org) ]
* **[scribl](https://github.com/chmille4/Scribl) ⭐ 76 | 🐛 15 | 🌐 JavaScript | 📅 2019-05-06** - JavaScript library for drawing canvas-based gene diagrams. \[ [paper-2012](https://pubmed.ncbi.nlm.nih.gov/23172864) | [web](http://chmille4.github.io/Scribl) ]
* **[DNAism](https://github.com/drio/dnaism) ⭐ 62 | 🐛 0 | 🌐 CSS | 📅 2016-04-30** - Horizon chart D3-based JavaScript library for DNA data. \[ [paper-2016](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-016-0891-2) | [web](http://drio.github.io/dnaism/) ]
* **[Circleator](https://github.com/jonathancrabtree/Circleator) ⭐ 46 | 🐛 19 | 🌐 Perl | 📅 2019-06-18** - Flexible circular visualization of genome-associated data with BioPerl and SVG. \[ [paper-2014](https://pubmed.ncbi.nlm.nih.gov/25075113) ]
* **[Squiggle](https://github.com/Lab41/squiggle) ⚠️ Archived** - Easy-to-use DNA sequence visualization tool that turns FASTA files into browser-based visualizations. \[ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/30247632) | [web](https://squiggle.readthedocs.io/en/latest/) ]
* **[Island Plot](https://github.com/lairdm/islandplot) ⭐ 33 | 🐛 1 | 🌐 JavaScript | 📅 2015-07-12** - D3 JavaScript based genome viewer. Constructs SVGs. \[ [paper-2015](https://pubmed.ncbi.nlm.nih.gov/25916842/) ]
* **[PHAT](https://github.com/chgibb/PHAT) ⭐ 17 | 🐛 76 | 🌐 TypeScript | 📅 2022-12-12** - Point and click, cross platform suite for analysing and visualizing next-generation sequencing datasets. \[ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/30561651) | [web](https://chgibb.github.io/PHATDocs) ]
* **Lucid Align** - A modern sequence alignment viewer. \[ [web](https://lucidalign.com) ]

### Circos Related

* **[fujiplot](https://github.com/mkanai/fujiplot) ⭐ 99 | 🐛 0 | 🌐 R | 📅 2025-05-29** - A circos representation of multiple GWAS results. \[ [paper-2018](https://www.nature.com/articles/s41588-018-0047-6) ]
* **[Circos](https://github.com/vigsterkr/circos) ⭐ 90 | 🐛 4 | 🌐 Perl | 📅 2018-10-29** - Perl package for circular plots, which are well suited for genomic rearrangements. \[ [paper-2009](https://pubmed.ncbi.nlm.nih.gov/19541911) | [web](http://circos.ca) ]
* **ClicO FS** - An interactive web-based service of Circos. \[ [paper-2015](https://pubmed.ncbi.nlm.nih.gov/26227146) ]
* **OmicCircos** - R package for circular plots for omics data. \[ [paper-2014](https://pubmed.ncbi.nlm.nih.gov/24526832) | [web](http://www.bioconductor.org/packages/release/bioc/html/OmicCircos.html) ]
* **J-Circos** - A Java application for doing interactive work with circos plots. \[ [paper-2014](https://pubmed.ncbi.nlm.nih.gov/25540184) | [web](http://www.australianprostatecentre.org/research/software/jcircos) ]
* **[rCircos](https://bitbucket.org/henryhzhang/rcircos/src/master/)** - R package for circular plots. \[ [paper-2013](https://pubmed.ncbi.nlm.nih.gov/23937229) | [web](http://watson.nci.nih.gov/cran_mirror/web/packages/RCircos/index.html) ]

## Database Access

* [Entrez Direct: E-utilities on the UNIX command line](http://www.ncbi.nlm.nih.gov/books/NBK179288/) - UNIX command line tools to access NCBI's databases programmatically. Instructions to install and examples are found in the link.

## Resources

### Becoming a Bioinformatician

* [What is a bioinformatician](http://blog.fejes.ca/?p=2418)
* [Bioinformatics Curriculum Guidelines: Toward a Definition of Core Competencies](http://www.ploscompbiol.org/article/info:doi%2F10.1371%2Fjournal.pcbi.1003496)
* [Top N Reasons To Do A Ph.D. or Post-Doc in Bioinformatics/Computational Biology](http://caseybergman.wordpress.com/2012/07/31/top-n-reasons-to-do-a-ph-d-or-post-doc-in-bioinformaticscomputational-biology/)
* [A 10-Step Guide to Party Conversation For Bioinformaticians](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2013-14-1-104) - Here is a step-by-step guide on how to convey concepts to people not involved in the field when asked the question: 'So, what do you do?'
* [A History Of Bioinformatics (In The Year 2039)](https://www.youtube.com/watch?v=uwsjwMO-TEA) - A talk by C. Titus Brown on his take of looking back at bioinformatics from the year 2039. His notes for this talk can be found [here](http://ivory.idyll.org/blog/2014-bosc-keynote.html).
* [A farewell to bioinformatics](https://madhadron.com/science/farewell_to_bioinformatics.html) - A critical view of the state of bioinformatics.
* [A Series of Interviews with Notable Bioinformaticians](http://www.acgt.me/blog/2014/3/25/101-questions-a-new-series-of-interviews-with-notable-bioinformaticians) - Dr. Keith Bradnam "thought it might be instructive to ask a simple series of questions to a bunch of notable bioinformaticians to assess their feelings on the current state of bioinformatics research, and maybe get any tips they have about what has been useful to their bioinformatics careers."
* [Open Source Society University on Bioinformatics](https://github.com/ossu/bioinformatics) ⚠️ Archived - Solid path for those of you who want to complete a Bioinformatics course on your own time, for free, with courses from the best universities in the World.
* [Rosalind](http://rosalind.info/) - Rosalind is a platform for learning bioinformatics through problem solving.
* [A guide for the lonely bioinformatician](http://www.opiniomics.org/a-guide-for-the-lonely-bioinformatician/) - This guide is aimed at bioinformaticians, and is meant to guide them towards better career development.
* [A brief history of bioinformatics](https://doi.org/10.1093/bib/bby063)

### Bioinformatics on GitHub

* [Awesome AI-based Protein Design](https://github.com/opendilab/awesome-AI-based-protein-design) ⭐ 315 | 🐛 0 | 📅 2024-05-13 - A collection of research papers for AI-based protein design.
* [Awesome-alternative-splicing](https://github.com/HussainAther/awesome-alternative-splicing) ⭐ 60 | 🐛 0 | 📅 2018-03-31 - List of resources on alternative splicing including software, databases, and other tools.

### Sequencing

* [Next-Generation Sequencing Technologies - Elaine Mardis (2014)](https://youtu.be/6Is3W7JkFp8) \[1:34:35] - Excellent (technical) overview of next-generation and third-generation sequencing technologies, along with some applications in cancer research.
* [Annotated bibliography of \*Seq assays](https://liorpachter.wordpress.com/seq/) - List of \~100 papers on various sequencing technologies and assays ranging from transcription to transposable element discovery.
* [For all you seq... (PDF)](http://www.illumina.com/content/dam/illumina-marketing/documents/applications/ngs-library-prep/ForAllYouSeqMethods.pdf) (3456x5471) - Massive infographic by Illumina on illustrating how many sequencing techniques work. Techniques cover protein-protein interactions, RNA transcription, RNA-protein interactions, RNA low-level detection, RNA modifications, RNA structure, DNA rearrangements and markers, DNA low-level detection, epigenetics, and DNA-protein interactions. References included.

### RNA-Seq

* [Informatics for RNA-seq: A web resource for analysis on the cloud](https://github.com/griffithlab/rnaseq_tutorial) ⭐ 1,436 | 🐛 6 | 🌐 R | 📅 2023-05-31 - Educational resource on performing RNA-seq analysis in the cloud using Amazon AWS cloud services. Topics include preparing the data, preprocessing, differential expression, isoform discovery, data visualization, and interpretation.
* [RNA-seq Analysis](https://github.com/crazyhottommy/RNA-seq-analysis) ⭐ 1,096 | 🐛 1 | 🌐 Python | 📅 2021-11-15 - [@crazyhottommy](https://github.com/crazyhottommy)'s notes on various steps and considerations when doing RNA-seq analysis.
* [Review papers on RNA-seq (Biostars)](https://www.biostars.org/p/52152/) - Includes lots of seminal papers on RNA-seq and analysis methods.
* [RNA-seqlopedia](http://rnaseq.uoregon.edu/) - RNA-seqlopedia provides an awesome overview of RNA-seq and of the choices necessary to carry out a successful RNA-seq experiment.
* [A survey of best practices for RNA-seq data analysis](http://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-0881-8) - Gives awesome roadmap for RNA-seq computational analyses, including challenges/obstacles and things to look out for, but also how you might integrate RNA-seq data with other data types.
* [Stories from the Supplement](https://www.youtube.com/watch?v=5NiFibnbE8o) \[46:39] - Dr. Lior Pachter shares his stories from the supplement for well-known RNA-seq analysis software CuffDiff and [Cufflinks](http://cole-trapnell-lab.github.io/cufflinks/) and explains some of their methodologies.
* [List of RNA-seq Bioinformatics Tools](https://en.wikipedia.org/wiki/List_of_RNA-Seq_bioinformatics_tools) - Extensive list on Wikipedia of RNA-seq bioinformatics tools needed in analysis, ranging from all parts of an analysis pipeline from quality control, alignment, splice analysis, and visualizations.

### ChIP-Seq

* [ChIP-seq analysis notes from Tommy Tang](https://github.com/crazyhottommy/ChIP-seq-analysis) ⭐ 853 | 🐛 0 | 🌐 Python | 📅 2024-08-05 - Resources on ChIP-seq data which include papers, methods, links to software, and analysis.

### YouTube Channels and Playlists

* [Current Topics in Genome Analysis 2016](https://www.genome.gov/12514288/current-topics-in-genome-analysis-2016-course-syllabus-handouts-and-videos/) - Excellent series of fourteen lectures given at NIH about current topics in genomics ranging from sequence analysis, to sequencing technologies, and even more translational topics such as genomic medicine.
* [GenomeTV](https://www.youtube.com/user/GenomeTV) - "GenomeTV is NHGRI's collection of official video resources from lectures, to news documentaries, to full video collections of meetings that tackle the research, issues and clinical applications of genomic research."
* [Leading Strand](https://www.youtube.com/user/LeadingStrand) - Keynote lectures from Cold Spring Harbor Laboratory (CSHL) Meetings. More on [The Leading Strand](http://theleadingstrand.cshl.edu/).
* [Genomics, Big Data and Medicine Seminar Series](https://www.youtube.com/playlist?list=PLqLDR0CTP9_pboZCk6gR9Zn4kW7h9XWJI) - "Our seminars are dedicated to the critical intersection of GBM, delving into 'bleeding edge' technology and approaches that will deeply shape the future."
* [Rafael Irizarry's Channel](https://www.youtube.com/user/RafalabChannel/videos) - Dr. Rafael Irizarry's lectures and academic talks on statistics for genomics.
* [NIH VideoCasting and Podcasting](https://www.youtube.com/user/nihvcast) - "NIH VideoCast broadcasts seminars, conferences and meetings live to a world-wide audience over the Internet as a real-time streaming video." Not exclusively genomics and bioinformatics video but many great talks on domain specific use of bioinformatics and genomics.

### Blogs

* [ACGT](http://www.acgt.me/) - Dr. Keith Bradnam writes about this "thoughts on biology, genomics, and the ongoing threat to humanity from the bogus use of bioinformatics acroynums."
* [Opiniomics](http://www.opiniomics.org/) - Dr. Mick Watson write on bioinformatics, genomes, and biology.
* [Bits of DNA](https://liorpachter.wordpress.com/) - Dr. Lior Pachter writes review and commentary on computational biology.
* [it is NOT junk](http://www.michaeleisen.org/blog/) - Dr. Michael Eisen writes "a blog about genomes, DNA, evolution, open science, baseball and other important things"
* [#!/perl/bioinfo](https://bioinfoperl.blogspot.com) - The Computational and Structural Biology group at EEAD-CSIC writes, in Spanish and English, about ideas and code for plant genomics, computational and structural biology problems.

### Miscellaneous

* [The Leek group guide to genomics papers](https://github.com/jtleek/genomicspapers/) ⭐ 505 | 🐛 3 | 📅 2018-11-05 - Expertly curated genomics papers to get up to speed on genomics, RNA-seq, statistics (used in genomics), software development, and more.
* [A New Online Computational Biology Curriculum](https://doi.org/10.1371/journal.pcbi.1003662) - "This article introduces a catalog of several hundred free video courses of potential interest to those wishing to expand their knowledge of bioinformatics and computational biology. The courses are organized into eleven subject areas modeled on university departments and are accompanied by commentary and career advice."
* [How Perl Saved the Human Genome Project](http://www.foo.be/docs/tpj/issues/vol1_2/tpj0102-0001.html) - An anecdote by Lincoln D. Stein on the importance of the Perl programming language in the Human Genome Project.
* [Educational Papers from Nature Biotechnology and PLoS Computational Biology](https://liacs.leidenuniv.nl/~hoogeboomhj/mcb/nature_primer.html) - Page of links to primers and short educational articles on various methods used in computational biology and bioinformatics.
* [The PeerJ Bioinformatics Software Tools Collection](https://peerj.com/collections/45-bioinformatics-software/) - Collection of tools curated by Keith Crandall and Claus White, aimed at collating the most interesting, innovative, and relevant bioinformatics tools articles in PeerJ.

## Online networking groups

* [Bioinformatics (on Discord)](https://discord.com/invite/3uxbPns) - a Discord server for general bioinformatics
* [r-bioinformatics](https://www.reddit.com/r/bioinformatics/comments/7ndwm1/rbioinformatics_slack_channel_and_an_open_call/) - the official Slack workspace of r/bioinformatics ([send a direct message to apfejes on reddit](https://www.reddit.com/message/compose/?to=apfejes\&subject=Request%20to%20join%20the%20r/bioinformatics%20Slack%20group\&message=I%20would%20like%20to%20request%20to%20join%20the%20r/bioinformatics%20Slack%20group))
* [BioinformaticsGRX](https://bioinformaticsgrx.es/) - A community of bioinformaticians based in Granada, Spain
* [Comunidad de Desarolladores de Software en Bioinformática](https://comunidadbioinfo.github.io/) - A community of bioinformaticians centered in Latin America
* [COMBINE](https://combine.org.au/) - An Austrialian group for bioinformatics students

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-17._
