---
title: rMAP(Rapid Microbial Analysis Pipeline)
summary: Thorough easy-to-use resistome profiling bioinformatics pipeline for ESKAPE (Enterococcus faecium, Staphylococcus aureus, Klebsiella pneumoniae, Acinetobacter baumannii, Pseudomonas aeruginosa, and Enterobacter species) pathogens using Illumina Whole-genome sequencing (WGS) paired-end reads.
tags:
- Antimicrobial resistance
- Microbial genomics
- Mobile genetic elements
date: "2020-10-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by ivangunz on Github
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Follow
  url: https://github.com/GunzIvan28
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
The evolution of the genomics era has led to generation of sequencing data at an unprecedented rate. Many bioinformatics tools have been created to analyze this data; however, very few tools can be utilized by individuals without prior reasonable bioinformatics training

rMAP(Rapid Microbial Analysis Pipeline) was designed using already pre-existing tools to automate analysis WGS Illumina paired-end data for the clinically significant ESKAPE group pathogens. It is able to exhaustively decode their resistomes whilst hiding the technical impediments faced by inexperienced users. Installation is fast and straight forward. A successful run generates a .html report that can be easily interpreted by non-bioinformatics personnel to guide decision making.

rMAP is designed for beginners and people with  little bioinformatics expertise, and automates the steps required for WGS analysis directly from the raw genomic sequence data including: adapter and low quality sequence read trimming, de-novo genome assembly, genome annotation, SNP-variant calling, phylogenetic inference by maximum-likelihood, antimicrobial resistance profiling, plasmid profiling, virulence factor determination, multi-locus sequence typing (MLST), pangenome analysis, and insertion sequence characterization (IS). Once the analysis is finished, rMAP generates interactive web-like html report that can be visualized using any web browser, shared and reviewed in a simpler manner. Details for installation and running of the pipeline can be accessed via https://github.com/GunzIvan28/rMAP.
