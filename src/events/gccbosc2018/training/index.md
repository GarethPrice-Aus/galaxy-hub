{{> Events/GCCBOSC2018/Header }}

# Nominate a training topic!

**[Nominate a training topic Now](http://bit.ly/gccbosc2018-tr-nom)**

The joint [2018 Galaxy Community and Bioinformatics Open Source Conferences](https://gccbosc2018.sched.com/) start with training and *the training topics that will be offered **are determined by you***. Please take a few minutes to consider which training topics you would like to see offered at GCCBOSC2018. Any topics of interest to these communities can be nominated. 

[GCCBOSC2018](https://gccbosc2018.sched.com/) will be held 25-30 June in Portland, Oregon, United States. It will feature two days of training: the second of which is multi-track and will feature content for both the BOSC and Galaxy communities.  

Nominated topics can cover a wide range. For example:

- How to use open source software using just a web browser (e.g., Intro to Using Galaxy) 
- How to use software packages (The Newbie's Guide to BioRuby)
- Advanced applications of software (Genome Assembly with Galaxy, or Proteomics with BioPython)
- Software installation and configuration (Tool Wrapping for Galaxy, or Using CloudLaunch)
- Open source community (Building a Curation Community using Apollo, or Training using the Galaxy Training Network)

These are only examples.  If you think the communities would be interested in a topic, then please  [nominate it](http://bit.ly/gccbosc2018-tr-nom)!

Nominated topics will be published on this page as they come in.

**Topic Nominations close January 12.** Topics will be compiled into a uniform list by the GCCBOSC2018 organizers, and then voted on by the community starting one week later.

# Nominated Topics

Topics are posted here as they are nominated.  If you see a topic with a brief description that you would like to expand on then please send an email to outreach@galaxyproject.org.

As of January 8, 2018 these topics have been nominated:

## 12. Galaxy For Proteogenomics !

Large-scale ‘omics’ data generation is driven by high throughput genome and transcriptome sequencing, and proteome characterization using mass spectrometry. As a result, many researchers are turning to generating integrative analysis of these ‘multi-omics’ datasets given the great potential to provide novel biological insights. These multi-omics applications are particularly challenging for data analysis, as they require the use of multiple, domain-specific software programs on scalable infrastructure capable of handling the computing and storage needs of this large-scale data.

Galaxy has been shown to solve the problems of software integration and scalability for multi-omics analysis, and additionally offer benefits for sharing complete workflows in a user-friendly environment accessible by wet-bench scientists. In this workshop, we will introduce the use of Galaxy platform for multi-omics data analysis applications. As a representative example, we will focus on the maturing field of proteogenomic applications. Proteogenomics most commonly integrates RNA-Seq data, for generating customized protein sequence databases, with mass spectrometry-based proteomics data, which are matched to these databases to identify novel protein sequence variants. (*Cancer Res.* (2017); 77(21):e43-e46. [doi: 10.1158/0008-5472.CAN-17-0331](http://cancerres.aacrjournals.org/content/77/21/e43.long).) 

*Workshop Content:* 

The course will include a basic introduction to proteomics and will include a hands-on session that will cover use of analytical workflows to generate proteomic databases from RNASeq data. The use and understanding of modules for analytical workflows for proteogenomics analysis will be discussed.

*Workshop Schedule:*

* Introduction to multi-omic studies
* RNASeq Data Processing: Generating protein sequence search databases using Galaxy platform
* Hands-on session for proteomics data analysis using Galaxy
* Identification of novel proteoforms and visualization
    
*Workshop Goals:*
    
* Introduce the Galaxy framework as a solution for data analysis across ‘omics’ domains
* Demonstrate use of Galaxy for a proteogenomic analysis (RNA-seq and proteomic integrative analysis)
* Lay the foundation for attendees to implement Galaxy at their own facility or institution to meet ‘omics’ data analysis and informatics needs

**Prerequisites:**

* Users will need laptop for hands-on training

## 11. Workflow Description Language

The advent of open, portable workflow languages is an exciting development which allows for the definition of a workflow to be decoupled from the execution. One can create workflows which can run unmodified on local compute, HPC clusters, or the cloud. As these languages are not tied to a specific execution environment, the descriptions can easily be shared, discovered and even composed together to form more complex workflows. The [Workflow Description Language](http://openwdl.org/) (WDL) is an open, community driven standard that is designed from the ground up as a human-readable and -writable way to express portable tasks and workflows.

In this session we’ll walk through the lifecycle of writing, sharing and discovering portable workflows in WDL. We’ll introduce the WDL syntax. You’ll learn how to write and run a workflow locally. We’ll demonstrate how to use [EPAM’s Pipeline Builder tool](https://github.com/epam/pipeline-builder) to visualize WDL workflows. We’ll look at [Dockstore](https://dockstore.org/), an open platform where one can publish, share and discover workflows. Finally we’ll put everything together and see how we can compose workflows we find on Dockstore together with our own additions to create new, more powerful workflows.

**Prerequisites:**

* Mac or Linux computer
* Java 8 installed and runnable from the command line
* A workshop bundle downloaded from TBD

## 10. Galaxy Interactive Environments

In this session you will get in-depth introduction to Interactive Environments (IE). You will learn how to setup and secure IE’s ([Jupyter](http://jupyter.org/), [RStudio](https://www.rstudio.com/), etc.) in a production Galaxy instance. Moreover, we will create an IE on-the-fly to get you started in creating your own Interactive Environments.In this session you will get an introduction to Interactive Environments (IE) as an easy and powerful way to integrate arbitrary interactive web services into Galaxy. We will demonstrate the [IPython Galaxy Project](https://github.com/bgruening/galaxy-ipython) and the general concept of IE’s.

**Prerequisites:**

* Basic understanding of Galaxy from a developer point of view.
* General knowledge about Docker
* Knowledge and comfort with the Unix/Linux command line interface and a text editor. If you don't know what cd, mv, rm, mkdir, chmod, grep and so on can do then you will struggle in this workshop.
* A wi-fi enabled laptop with a modern web browser.  Google Chrome, Firefox and Safari will work best. 


## 9. GATK4

1. Intro to GATK
  - reminder of what GATK is about; purpose, variant calling for newbs, major file formats and so on
2. What's new in GATK4 specifically
  - new syntax/invocations, new engine capabilities, new scope of analysis, key improvements, tips & tricks.
3. Options for running GATK -- hands-on 
  - run  "straight up" on laptop (with Docker)
  - run Spark tools on Google Dataproc
  - run pipeline on Cromwell on laptop
  - run pipeline on Google via Cromwell+Pipelines API (some scripty goodness)
  - run pipeline on FireCloud in GUI (briefly)
  - run pipeline on FireCloud via API + python bindings (lots of scripty goodness)
  - run pipeline on Galaxy

## 8. Hi-C analysis in Galaxy

This session will introduce the basics of chromosome conformation capture assays and their applications, followed by best practices in mapping, QC'ing, visualazing and assigning 'topological associated domains' with Hi-C data.

**Prerequisites**

* Understanding of chromosome conformation capture (3C) and variants (HiC, 5C, 4C). Understanding of Illumina based "NGS".
* Understanding of Galaxy user interface.

## 7. Handling integrated biological data using Python (or R) and InterMine

This tutorial will guide you through loading and analyzing integrated biological data (generally genomic or proteomic) in [InterMine](http://intermine.org/) via an API in Python or R. Topics covered will include automatically generating code to perform queries, customising the code to meet your needs, and automated analysis of sets, e.g gene sets, including enrichment statistics. Skills gained can be re-used in any of the dozens of InterMines available, covering a broad range of organisms and dedicated purposes, from model organisms to plants, drug targets, and mitochondrial DNA.

**Prerequisites**

* Basic Python or R skills are advantageous but not required. 
* A laptop with wifi and Python or R Studio.

## 6. Deploying (Galaxy and your) applications into clouds

This tutorial will have two parts. Part 1 will demonstrate how to use the all-new CloudLaunch service to launch and manage instances of Galaxy on the Cloud on multiple cloud providers. In part 2, we will cover the technical process of adding custom applications into CloudLaunch and making them available for launching on any supported cloud (AWS, Azure, GCE, OpenStack). This part will also cover use of the CloudLaunch API, enabling external applications to leverage CloudLaunch capabilities.

**Prerequisites**

* Part 1: a laptop with WiFi and a modern browser
* Part 2: Basic programming skills (Python, Angular 2/4/5 useful but not essential?)


## 5. ChIPseq analysis using deepTools and MACS2

Did my IP work? Where is my signal? How well do my replicates correlate? What might my peaks even look like? Where are my peaks (or signal) in relationship to transcription start sites (or other features)? These are common questions that biologists first pose when dealing with ChIPseq data. We will use deepTools and MACS within Galaxy to demonstrate effective methods of

1. performing ChIPseq-specific quality control,
2. calling peaks and
3. visualising signal and peak enrichment around genes or other features."	"

**Prerequisites**

- Galaxy 101 or equivalent experience.
- Ideally participants will already be familiar with generic NGS quality control and read mapping, since those won't be covered
- A wi-fi enabled laptop with a modern web browser. Google Chrome, Firefox and Safari will work best. "

## 4. How to analyze microbiota data with Galaxy

The study of complex microorganism communities has been eased by the development of sequencing platforms and dedicated powerful bioinformatics tools. Several tools have recently been integrated into Galaxy for microbiota data analysis: Mothur, QIIME, MetaPhlAN, HUMAnN, FROGS, MEGAHIT, MetaSPAdes,...

In this training, we will show in this training how to analyze metagenomic and amplicon data inside Galaxy:

- Extraction of the OTUs using [QIIME](http://qiime.org/)/[Mothur](https://www.mothur.org/)
- Reconstruction of the taxonomic composition of a sample without OTUs using [MetaPhlAn](http://huttenhower.sph.harvard.edu/metaphlan2)
- Find the metabolic functions realized in an environment using [HUMAnN](https://huttenhower.sph.harvard.edu/humann)

**Prerequisites**

* Galaxy 101 or equivalent experience
* Ideally participants will already be familiar with the concepts behind metagenomics (e.g., OTU)
* A wi-fi enabled laptop with a modern web browser. Google Chrome, Firefox and Safari will work best

## 3. Bioinformatics Training and Education with the Galaxy Training Network

Galaxy with its flexibility, reproducibility, and scalability is an ideal environment for teaching and training diverse scientific topics. 

The Galaxy Training Network is a community initiative dedicated to high-quality Galaxy-based training around the world. One of its objectives is to support trainers with complete training material and recommendations about bioinformatics training. Templates and best training practices were defined to help trainers create new material, unify the different material, and make training materials more accessible and easy for users to learn and for teachers to teach (https://training.galaxyproject.org).

This workshop will introduce participants to the infrastructure of the GTN training materials and describe how to generate training materials following best practices. Participants will be introduced to the generation Galaxy Interactive Tours and the creation of Docker Flavors dedicated to teaching and training sessions. The workshop will also cover best practices for running Galaxy-based workshops (how to plan a training session based on number of attendees, time constraints, resource availability, etc).

**Prerequisites**

* Basic familiarity with using Galaxy (how to import datasets and run tools)
* Basic familiarity with git and Docker will also be helpful for parts of the workshop.
* A wi-fi enabled laptop with a modern web browser. Google Chrome or Firefox will work best.


## 2. Practical use of the Galaxy API command line tools

How to use the Galaxy [API](https://galaxyproject.org/develop/api/) to automate workflows.

Galaxy has an always-growing API that allows for external programs to upload and download data, manage histories and datasets, run tools and workflows, and even perform admin tasks. This session will cover various approaches to access the API, in particular using the [BioBlend Python library](https://bioblend.readthedocs.io/en/latest/).

**Prerequisites**

* Unix command line
* Basic understanding of Galaxy from a developer point of view.
* Python programming.
* A wi-fi enabled laptop with a modern web browser. Google Chrome, Firefox and Safari will work best.

## 1. The Galaxy Database Schema

Running a production Galaxy server, you some times end up in a situation, where you manually need to interact with the database, e.g. you want to extract usage information, which can not be gathered from the built in reports tool. Or, a more  risky adventure: you need to change the state of a job to 'error'. For both cases, you require a good understanding of the Galaxy database schema. In this training session, you will learn some of the design concepts of the database, and how to extract (or if necessary change) information useful for a Galaxy admin.	Experience maintaining a production Galaxy server and a basic knowledge of relational databases and SQL statements.

**Prerequisites**

* Experience maintaining a production Galaxy server and a basic knowledge of relational databases and SQL statements

# Nominations in Progress


## Genome-wide sgRNA screen analysis using GALAXY

Identify sgRNAs enriched in a screen with specific treatment.  Raw data processing, mapping, MAGeCK-VISPR.

## Open workflow languages

Hands on with CWL/WDL and jobrunners.


## Command line workflow management systems: Snakemake, Cluster Flow, Bpipe

How to use workflow management systems that are designed for the command line, such as [Snakemake](http://snakemake.readthedocs.io/en/stable/), [Cluster Flow](http://clusterflow.io/), and [Bpipe](https://github.com/ssadedin/bpipe#welcome-to-bpipe--).

**Prerequisites**

* Linux command line experience

## Analysis of scRNA sequencing data

How to analyze single cell RNA sequencing data, e.g. in [cellranger](https://support.10xgenomics.com/single-cell-gene-expression/software/pipelines/latest/what-is-cell-ranger) or with dedicated R packages

