---
title: "Tutorials"
permalink: /tutorials/
layout: single
toc: true
toc_label: "Tutorials"
---

The workshop tutorials are built around the **anvi'o** platform. All materials will be made publicly available before the workshop begins.

## Prerequisites

Participants are expected to have:
- Basic familiarity with the Linux command line
- Basic understanding of next-generation sequencing concepts
- A laptop with internet access (software setup instructions will be provided ahead of the workshop)


### Installation of anvio-dev
Here is the link for the installation instructions for anvio-dev: [anvi'o development version install guide](https://anvio.org/install/#development-version ). Please follow the instructions relevant for their laptop OS

In addition to the base installation of anvio-dev, you need to  run a few commands which downloads and setup key resources needed for the workshop and for anyone using anvi'o for their research. 

In brief, here they are:

```bash
anvi-setup-scg-taxonomy

anvi-setup-ncbi-cogs

anvi-setup-kegg-data

anvi-setup-modelseed-databaseinsi
```


### Downloading training files

To download all the training files, please follow the instructions below. 

```bash

# set up your working directory

mkdir -p Stellenbosch_workshop

cd Stellenbosch_workshop

# interactive interface tutorial
curl -L https://cloud.uol.de/public.php/dav/files/SMzBr8KbrKgQKrN \
     -o interactive_interface.tar.gz
tar -zxvf interactive_interface.tar.gz

# trichodesmium tutorial (genomics, pangenomics, metabolism)
curl -L https://cloud.uol.de/public.php/dav/files/S67286XGxtax2AX \
     -o trichodesmium_tutorial.tar.gz
tar -zxvf trichodesmium_tutorial.tar.gz

# read recruitment tutorial
curl -L https://cloud.uol.de/public.php/dav/files/B849axL35cBZzYD \
     -o metagenomic-read-recruitment-data-pack.tar.gz
tar -zxvf metagenomic-read-recruitment-data-pack.tar.gz

# binning tutorials
curl -L -o INFANT-GUT-TUTORIAL.tar.gz \
     https://cloud.uol.de/public.php/dav/files/WLxH3aPJymCW9Lp
tar -zxvf INFANT-GUT-TUTORIAL.tar.gz

curl -L https://cloud.uol.de/public.php/dav/files/c4TyGoDe3D7XPiq \
     -o BINNING_POPGEN_TUTORIAL.tar.gz
tar -xvf BINNING_POPGEN_TUTORIAL.tar.gz

# workflow tutorial
curl -L https://cloud.uol.de/public.php/dav/files/9eHngByzx4L63aq \
     -o WORKFLOW_MATERIAL.tar.gz
tar -xvf WORKFLOW_MATERIAL.tar.gz
```


### Discord channel
Use this link to join the [discord](https://discord.com/invite/C6He6mSNY4) channel for communication. 


## Module 1: Genomics
---

## Module 2: Pangenomics
---

## Module 3: Metagenomics
---

## Module 4: Scalable Bioinformatics & Wrap-up (training)
---

## Additional Resources

- [anvi'o official documentation](https://anvio.org)
- [anvi'o tutorials](https://merenlab.org/tutorials/)
- [Meren Lab](https://merenlab.org)
