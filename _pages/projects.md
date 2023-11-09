---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
{% include base_path %}

My research projects are mainly focused on the utilization and development of bioinformatics technologies and methods to study pediatric cancers, mostly pediatric leukemia.

## Characterize the heterogeneity of pediatric leukemia

Because of the low prevalence of cancer in children compared to adults, there is historically a lack of publicly available datasets and specific research pertaining to childhood cancer. Using single-cell RNA sequencing and other next-generation sequencing technologies, we can characterize the heterogeneity inter-subtype and intra-subtype malignant and microenvironment populations.

Leukemia is the most common type of childhood cancer. It encompasses about a quarter of new childhood cancer cases each year ([NCI](https://seer.cancer.gov/statfacts/html/childleuk.html)), and is a cancer of the blood and bone marrow. Leukemia occurs when *hematopoiesis*, or the process by which blood componenets are formed, becomes dysregulated and the bone marrow produces abnormal, undifferentiated (blast) cells.

**Mixed-phenotype acute leukemia (MPAL)**

In our 2023 publication in *Genome Medicine*, we characterize the heterogeneity in ***mixed phenotype*** acute leukemia, MPAL, which occurs when there are two or more blast populations in the bone marrow, through single-cell RNA sequencing. MPAL is a rare subtype of acute leukemia, and we performed the first *pediatric* single-cell study of MPAL.

> **Mumme HL**, Raikar SS, Bhasin SS et al. Single-cell RNA sequencing distinctly characterizes the wide heterogeneity in pediatric mixed phenotype acute leukemia. Genome Med 15, 83 (2023). https://doi.org/10.1186/s13073-023-01241-z

**Acute myeloid leukemia (AML)**

In our 2023 publication in *Nature Communications*, we again utilize single-cell RNA sequencing to characterize acute ***myeloid*** leukemia, AML, which occurs when there are myeloid-like blasts in the bone marrow. AML is a more common subtype of acute leukemia.

> **Mumme H**, Thomas BE, Bhasin SS et al. Single-cell analysis reveals altered tumor microenvironments of relapse- and remission-associated pediatric acute myeloid leukemia. Nat Commun 14, 6209 (2023). https://doi.org/10.1038/s41467-023-41994-0

**Pan-Leukemia**

Through our labs indvidual acute leukemia subtype studies, we have compiled a large consortium of pediatric acute leukemia single-cell RNA sequencing samples (over eighty). Through single-cell analytical methods, we integrate and perform a ***pan-leukemia*** analysis to assess how acute leukemia subtypes are similarity dysregulated compared to *normal* bone marrow from healthy donors.

## Create tools to increase accessibility of pan-cancer datasets and analytical modules

While single-cell technologies are incredibly useful in understanding cellular population transcriptome patterns, the utilization of these sequencing and analysis methods requires the use of bioinformatics and high-performance computing to analyze these large datasets. We are developing a ***Pediatric Single-Cell Cancer Atlas***, or ***PedSCAtlas***, to facilitate the analysis and exploration of multiple pan-cancer datasets without the requirement of bioinformatics expertise by the user. This increases the accessibility of pediatric datasets, which is incredibly important due to the lack of pediatric-specific studies and datasets due to the lower incidence of cancer in children compared to adults.

The first version of the PedSCAtlas is available online at [https://bhasinlab.bmi.emory.edu/PediatricSCAtlas/](https://bhasinlab.bmi.emory.edu/PediatricSCAtlas/). 

## Use omics technologies to identify novel immunotherapy targets

**Chimeric antigen receptor T cell Targets**

Chimeric antigen receptor T cells, or CAR-T cells, are human dervied effector T-cells engineering to target an epitope on malignant cancer cells. CAR-T immunotherapies have been developed and successful in B-cell acute lymphoblastic leukemia, B-ALL, with *CD19* and *BCMA* as targets. Current trials are undergoing for novel AML targets, such as *CD33* and *CD123*, but there is a lack of feasible CAR-T targets for t-cell acute lymphoblastic leukemia, T-ALL, due to the unique challges of developing a T-cell therapy for T-cell specific disease.

We are utilizing our T-ALL single-cell sequencing data to identify novel CAR-T targets through a single-cell pipeline that tests for efficacy and safety of target genes by utilizing public and local single-cell datasets, of T-ALL and healthy samples.
