# Australian Grains Genebank Strategic Partnership

![GRDC-AGG-AgVic-logos](https://pretzel-images-public.s3.ap-southeast-2.amazonaws.com/agvic_grdc.svg)

The AGG Strategic Partnership is a $30M joint investment between the Victorian State Government and Grains Research and Development Corporation (GRDC) that aims to unlock the genetic potential of plant genetic resources for the benefit of the Australian grain growers.

The AGG has the mandate to acquire, conserve, maintain and distribute genetic resources to plant breeders and researchers to underpin the development of more resilient and productive grain crop varieties for the benefit of the Australian grains industry.

The AGG’s ultimate goal is to unlock the genetic potential of plant genetic resources for cereal, oilseed and pulse crops to underpin the development of high yielding, climate resilient crops that will benefit Australian grain growers.

This page will be regularly updated with outputs from the Partnership, including information about datasets, digital tools, Community of Practice meeting and training sessions.

## Genotype data

A core aim of the Partnership is the genetic characterisation of the AGG collection.

Genotype datasets are made available on Harvard Dataverse under a CC BY 4.0 license: https://dataverse.harvard.edu/dataverse/australiangrainsgenebank-genotypedata

***Total genotypes released to date***: 37,666

### Wheat
The AGG wheat collection is being genotyped with the Illumina Infinium™ Wheat Barley 40K SNP array.

- 22nd August 2024 - First batch of 12,606 AGG wheat PGR genotypes released: https://doi.org/10.7910/DVN/CRSI0B

### Barley
The AGG barley collection is being genotyped with the Illumina Infinium™ Wheat Barley 40K SNP array.

- 14th August 2024 - First batch of 13,989 AGG barley PGR genotypes released: https://doi.org/10.7910/DVN/H6SNVM

### Chickpea
The AGG chickpea collection is being genotyped with the Illumina Infinium™ Pulse 30K SNP array.

- 3rd December 2024 - First batch of 11,071 AGG chickpea PGR genotypes released: https://doi.org/10.7910/DVN/SQFKJW

### Lentil

___Coming soon!___

## Digital tools

Source code for all digital tools developed by the Partnership are available on Github: https://github.com/plantinformatics

### Pretzel (https://github.com/plantinformatics/pretzel)

Pretzel is an interactive web application designed to enable rapid translation of genomics outputs for any species into concrete answers to research and breeding questions.

The AGG-branded Pretzel instance (https://agg.plantinformatics.io/) is loaded with all the AGG genotype data as it is released, together with datasets to enable connection of the AGG to research and breeding knowledge. Click [here](https://agg.plantinformatics.io/signup) to create your free account and start using Pretzel today!

![Pretzel_screenshot](https://github.com/user-attachments/assets/554294c5-4d9e-4900-b90b-074db6995921)

### Genolink (https://github.com/plantinformatics/genolink)

Genolink is middleware that connects genebank PGR passport data stored in [Genesys-PGR](https://www.genesys-pgr.org/) with genotype data stored in BrAPI-compliant databases such as [Gigwa](https://gigwa.southgreen.fr/gigwa/).

![image](https://github.com/user-attachments/assets/0ff58f54-deab-425f-a1ba-300574ab63c2)

### Lamington (https://github.com/plantinformatics/lamington)

Lamington is an R Shiny application for exploring genetic diversity among sets of accessions and defining core sets using CoreHunter3.

![image](https://github.com/user-attachments/assets/4b5d2f9e-861f-4d6b-8d8d-b61277be8dcb)

### Shortbread2 (https://github.com/plantinformatics/shortbread2)

Shortbread2 is a Nextflow pipeline for calling SNPs from short read sequencing data using GATK. Using Shortbread2, resequencing data can be rapidly re-mapped to any genome assembly, assisting with the linking of research and breeding knowledge to the AGG.

### Brioche (https://github.com/plantinformatics/brioche)

Brioche is a Nextflow pipeline for the mapping of genotype array probes (such as from the Illumina Infinium™ SNP arrays being used in the Partnership) to determine genomic positions and REF/ALT alleles of markers. In addition, Brioche is able to in-silico genotype assemblies to enable the integration of pan genomes with AGG genotype data. See this in action in [User Story 3]](https://docs.plantinformatics.io/User-Stories/User-story-3/#reproducing-the-haplotype-classification-from-kuzay-et-al-2019)!

## Documentation and Training

## Community of Practice

The Partnership engages with the Australian grains industry through the Australian Grains Genebank Community of Practice. Topics covered include updates on outputs, demonstration of digital tools and consultation around policy changes. Industry is encouraged to propose topics for future sessions.

- 18th October 2023 – Genomic data generation, access and use
- 15th November 2023 – Review high priority characterisation traits for industry
- 13th December 2023 – End User use-case development for bio-digital tools
- 20th February 2024 – Depositing seed and trait data into the AGG
- 14th May 2024 - Development of core diversity and subsets from the AGG collection
- 18th June 2024 – AGG Acquisition Policy – Industry Agreed Genotyping Assays
- 23rd July 2024 - Industry examples using AGG digital tools: An Introduction to User Stories
- 17th September 2024 - User Story 2: Filtering AGG wheat accessions for stripe rust resistance gene Yr34/Yr48
- 6th November 2024 – User Story 3: From SSRs to pan genomes with Pretzel: Two decades of wheat yield QTLs on chromosome 7A

- ___Coming in March 2025 - Introduction to Data Interoperability___

If you are interested in receiving updates about upcoming Community of Practice sessions, please email adam.dimech@agriculture.vic.gov.au.




