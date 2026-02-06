---
title: "Optimized sample selection for cost-efficient long-read population sequencing"
date: 2021-03-01
tags: ["tomato","long-read","assembly"]
author: ["T. Rhyker Ranallo-Benavidez", "Zachary Lemmon", "Sebastian Soyk", "Sergey Aganezov", "William Salerno", "Rajiv McCoy", "Zachary Lippman", "Michael Schatz", "Fritz Sedlazeck"]
description: "Method leveraging short read data to optimize sample selection for population long-read sequencing projects. Published in Genome Research, 2021." 
summary: "Method leveraging short read data to optimize sample selection for population long-read sequencing and assembly projects." 
cover:
    image: "paperRB2021.png"
    alt: "long read sampling"
    relative: true
editPost:
    Text: "Cell"

---

---

##### Download

+ [Paper](https://doi.org/10.1101/gr.264879.120)

---

##### Abstract

An increasingly important scenario in population genetics is when a large cohort has been genotyped using a low-resolution approach (e.g., microarrays, exome capture, short-read WGS), from which a few individuals are resequenced using a more comprehensive approach, especially long-read sequencing. The subset of individuals selected should ensure that the captured genetic diversity is fully representative and includes variants across all subpopulations. For example, human variation has historically focused on individuals with European ancestry, but this represents a small fraction of the overall diversity. Addressing this, SVCollector identifies the optimal subset of individuals for resequencing by analyzing population-level VCF files from low-resolution genotyping studies. It then computes a ranked list of samples that maximizes the total number of variants present within a subset of a given size. To solve this optimization problem, SVCollector implements a fast, greedy heuristic and an exact algorithm using integer linear programming. We apply SVCollector on simulated data, 2504 human genomes from the 1000 Genomes Project, and 3024 genomes from the 3000 Rice Genomes Project and show the rankings it computes are more representative than alternative naive strategies. When selecting an optimal subset of 100 samples in these cohorts, SVCollector identifies individuals from every subpopulation, whereas naive methods yield an unbalanced selection. Finally, we show the number of variants present in cohorts selected using this approach follows a power-law distribution that is naturally related to the population genetic concept of the allele frequency spectrum, allowing us to estimate the diversity present with increasing numbers of samples.

---

##### Citation

Ranallo-Benavidez, T. Rhyker. et al. Optimized sample selection for cost-efficient long-read population sequencing. Genome Res. 31: 910-918 (2021).

---

