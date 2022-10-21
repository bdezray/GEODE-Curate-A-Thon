---
title: Data Curation Primer
category: Getting Started
order: 1
---

> **What is data curation?**

Data curation aids in preserving the value of research data for the long-term by optimizing data for discoverability, interoperability, and reusability (Munoz & Renear 2011; Johnston et al., 2018; Thomer et al, 2022). For more specifics on data curation in practice see the definition below provided by Zorich 1995:

  “Data sets need to be examined for consistency, long-term quality and relevance over time, and new sources of data must be identified and assessed. Changes or updates to data require authentication and verification. Tools which support object databases, such as authority lists, thesauri, data dictionaries and other documentation resources, need to be maintained, updated and distributed at regular intervals, while data security and access must be considered. All these concerns constitute the discipline of data curation.”

  > **Project Background**

When you hear the term “biodiversity” you probably think of the millions of species that  inhabit our forests, savannahs and oceans. However, each species comprises many individual organisms, which share a common heritage, their DNA. While individuals within species all have very similar DNA, each one is also distinguished by hundreds of mutations throughout their genome. In fact, it is these mutations that allow some individuals to adapt to changing environments, while others cannot: a phenomenon called natural selection. Species and populations that have a larger amount of diversity in their collective DNA (i.e. genetic diversity) are thus more likely to be able to adapt to climate change than those that have low genetic diversity. However, despite the recognized importance of genetic diversity, data about the genetic diversity of populations are not often incorporated into large scale conservation policy decisions. One reason for this is that the DNA sequence data are not FAIR (findable, accessible, interoperable and reusable).

While a culture of open data sharing exists for raw digital DNA sequence information, the goal of comprehensively summarizing and monitoring Earth’s genetic biodiversity remains largely elusive because these records lack sufficient geospatial and temporal metadata. You may be familiar with metadata, that, when attached to a digital picture taken by your smartphone, can tell a computer when and where that photo was taken. While most smart phones automatically attach such metadata to photos, only about 13% of potentially biodiversity-relevant genetic data in the Sequence Read Archive (SRA) of the [International Nucleotide Sequence Collaboration](https://www.insdc.org) ([NCBI](https://www.ncbi.nlm.nih.gov/sra/) + [DDBJ](https://www.ddbj.nig.ac.jp/dra/index-e.html) + [EMBL](https://www.ebi.ac.uk/ena/browser/home)) currently have temporal or geospatial metadata attached to them (Toczydlowski et al. 2021). This means that the other 80% are nearly useless for meta-analysis of essential biodiversity variables such as heterozygosity, divergence, and effective population size.

The Genomic Observatories Diversity Explorer (GEODE) project aims to visualize the world’s most foundational, yet under appreciated, layer of biodiversity: genetic diversity. Previous efforts to capture essential spatiotemporal metadata for population genomic datasets from the Sequence Read Archive will be expanded, and genetic variants will be called using a bioinformatic pipeline on Microsoft Azure Cloud to calculate essential biodiversity variables for genetic composition. GEODE will enable open access to genetic diversity information for government agencies and conservation NGOs, as well as for the general public.


> **Why does data curation matter?**

Data curation is important for making sure that datasets are FAIR:findable, accessible, interoperable, and reusable (Wilkinson et al., 2016). Previous work has demonstrated that data that have been curated are more likely to be trusted and reproducible as well as easily understood by other researchers and collaborators (Roche et al., 2015; McNutt 2016; Smith & Roberts 2016; Beagrie & Houghton 2014).

In particular, data curation of genetic and genomic sequence data is valuable because these data have immense reuse value for measuring genetic diversity. However, without information about the spatial and temporal context, the metadata, of the sample organism, the value of the genomic sequence is limited (Toczydlowski et al. 2021).

[Next](_docs/Getting Started/Data Curation Primer.md){: .btn}
