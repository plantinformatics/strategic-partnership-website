![image](https://github.com/user-attachments/assets/74956317-6b5f-4399-a5e8-d17fb6eedbff)

# Australian Grains Genebank Strategic Partnership

![GRDC-AGG-AgVic-logos](https://pretzel-images-public.s3.ap-southeast-2.amazonaws.com/agvic_grdc.svg)

The AGG Strategic Partnership is a $30M joint investment between the Victorian State Government and Grains Research and Development Corporation (GRDC) that aims to unlock the genetic potential of plant genetic resources for the benefit of the Australian grain growers.

![image](https://github.com/user-attachments/assets/ef8f92e0-de8c-4fb5-8d4b-e353988f9d9b)


The AGG has the mandate to acquire, conserve, maintain and distribute genetic resources to plant breeders and researchers to underpin the development of more resilient and productive grain crop varieties for the benefit of the Australian grains industry.

The AGG’s ultimate goal is to unlock the genetic potential of plant genetic resources for cereal, oilseed and pulse crops to underpin the development of high yielding, climate resilient crops that will benefit Australian grain growers.

This page will be regularly updated with outputs from the Partnership, including information about datasets, digital tools, Community of Practice meeting and training sessions.

## Genotype data

A core aim of the Partnership is the genetic characterisation of the AGG collection. The crops being targeted for genotyping by the Partnership are: bread wheat, durum wheat, barley, chickpea, lentil, field pea, lupin, faba bean, oats, canola, mung bean, brassica, sorghum.

Genotype datasets are made available on Harvard Dataverse under a CC BY 4.0 license: https://dataverse.harvard.edu/dataverse/australiangrainsgenebank-genotypedata

***Total genotypes released to date***: 51,422

[How to access passport information for genotyped accessions.](#exporting-passport-information-for-genotyped-agg-accessions-from-genolink)

### Wheat
The AGG wheat collection is being genotyped with the Illumina Infinium™ Wheat Barley 40K SNP array.

- 22nd August 2024 - First batch of 12,606 AGG wheat PGR genotypes released: https://doi.org/10.7910/DVN/CRSI0B

### Barley
The AGG barley collection is being genotyped with the Illumina Infinium™ Wheat Barley 40K SNP array.

- 14th August 2024 - First batch of 13,989 AGG barley PGR genotypes released: https://doi.org/10.7910/DVN/H6SNVM

### Chickpea
The AGG chickpea collection is being genotyped with the Illumina Infinium™ Pulse 30K SNP array.

- 3rd December 2024 - First batch of 11,071 AGG chickpea PGR genotypes released: https://doi.org/10.7910/DVN/SQFKJW
- 5th May 2025 - Second batch of AGG chickpea PGR genotypes released, including 1,813 additional accessions: https://doi.org/10.7910/DVN/ECQ4NC 

### Lentil
The AGG lentil collection is being genotyped with the Illumina Infinium™ Pulse 30K SNP array.

- 14th March 2025 - First batch of 6,308 AGG lentil PGR genotypes released: https://doi.org/10.7910/DVN/T0TDAS

### Field pea
The AGG lentil collection is being genotyped with the Illumina Infinium™ Pulse 30K SNP array.

- 8th August 2025 - First batch of 5,635 AGG field pea PGR genotypes released: https://doi.org/10.7910/DVN/A6WGYS

### Lupin

___Coming soon!___

## Digital tools

Digital tools are being developed to make the crop diversity within the AGG collection highly accessible to researchers and breeders, without the need for advanced bioinformatics skills.

We are working with international partners to build the digital infrastructure required for the seamless integration of genebank genomics across genebanks.

Source code for all digital tools developed by the Partnership are available on Github: https://github.com/plantinformatics

### Pretzel (https://github.com/plantinformatics/pretzel)

Pretzel is an interactive web application designed to enable rapid translation of genomics outputs for any species into concrete answers to research and breeding questions.

The AGG-branded Pretzel instance (https://agg.plantinformatics.io/) is loaded with all the AGG genotype data as it is released, together with datasets to enable connection of the AGG to research and breeding knowledge. Click [here](https://agg.plantinformatics.io/signup) to create your free account and start using Pretzel today!

![image](https://github.com/user-attachments/assets/44aea8c0-4828-4510-b24b-8a40c4c69c78)

### Genolink (https://github.com/plantinformatics/genolink)

Genolink is middleware that connects genebank PGR passport data stored in [Genesys-PGR](https://www.genesys-pgr.org/) with genotype data stored in BrAPI-compliant databases such as [Gigwa](https://gigwa.southgreen.fr/gigwa/).

![image](https://github.com/user-attachments/assets/0ff58f54-deab-425f-a1ba-300574ab63c2)

#### Exporting passport information for genotyped AGG accessions from Genolink

1. Load [Genolink](https://genolink.plantinformatics.io/)

2. By default, the AGG institute code ("AUS165") has been selected. In the left menu, click Crops and select the crop you want passport information for. For example, chickpea.

![image](https://github.com/user-attachments/assets/c708ebde-3f47-464c-8708-7e627e647b41)

4. (Optional) If you only want to export passport data for __genotyped accessions__, click the "Check for genotype" button at the bottom of the left panel.

![image](https://github.com/user-attachments/assets/f4005923-1e8c-4b38-a657-13b42314dd0f)

5. Click __Update Search__

![image](https://github.com/user-attachments/assets/e9b2341e-80e8-437a-b148-86252d92aebe)

7. Click __Export All Passport Data__

![image](https://github.com/user-attachments/assets/eb113351-84ca-4b0e-a5f2-3fb5fe46ce3c)

After a few moments, a TSV file with the passport data will be downloaded.

### Lamington (https://github.com/plantinformatics/lamington)

Lamington is an R Shiny application for exploring genetic diversity among sets of accessions and defining core sets using CoreHunter3.

![image](https://github.com/user-attachments/assets/4b5d2f9e-861f-4d6b-8d8d-b61277be8dcb)

### Shortbread2 (https://github.com/plantinformatics/shortbread2)

Shortbread2 is a Nextflow pipeline for calling SNPs from short read sequencing data using GATK. Using Shortbread2, resequencing data can be rapidly re-mapped to any genome assembly, assisting with the linking of research and breeding knowledge to the AGG.

### Brioche (https://github.com/plantinformatics/brioche)

Brioche is a Nextflow pipeline for the mapping of genotype array probes (such as from the Illumina Infinium™ SNP arrays being used in the Partnership) to determine genomic positions and REF/ALT alleles of markers. In addition, Brioche is able to in-silico genotype assemblies to enable the integration of pan genomes with AGG genotype data. See this in action in [User Story 3]](https://docs.plantinformatics.io/User-Stories/User-story-3/#reproducing-the-haplotype-classification-from-kuzay-et-al-2019)!

## Documentation and Training

Documentation is available at the [Pretzel documentation page](https://docs.plantinformatics.io/).

The documentation is organised into three main sections:

### User Stories

These are worked examples structured around real breeding and research questions with step-by-step instructions on how to reproduce the analysis. We want these to be relevant to industry so if you have a suggestion, or would like to work on a User Story together, please get in touch.

#### User Story 1 – [Identifying virus resistant PGRs using Pretzel](https://docs.plantinformatics.io/User-Stories/User-story-1/)

![image](https://pretzel-images-public.s3.ap-southeast-2.amazonaws.com/user-stories/user-story-1/us-1-29.png)

#### User Story 2 - [Filtering AGG wheat accessions for stripe rust resistance gene Yr34/Yr48](https://docs.plantinformatics.io/User-Stories/User-story-2/)

![image](https://github.com/user-attachments/assets/554294c5-4d9e-4900-b90b-074db6995921)

#### User Story 3 - [From SSRs to pan genomes with Pretzel: Two decades of wheat yield QTLs on chromosome 7A](https://docs.plantinformatics.io/User-Stories/User-story-3/)

![image](https://github.com/user-attachments/assets/6279cd32-09d6-49f1-9fb2-5b23c57a2a13)

### Use Cases

[Use Cases](https://docs.plantinformatics.io/Use-Cases/Finding-a-marker-or-gene-on-a-genome/) are examples of specific ways Pretzel can be used. The basis for Use Cases can be proposals by industry or based on parts of User Stories.

### Basic Functions

[Basic Functions](https://docs.plantinformatics.io/Basic-Functions/Search-tab/) describe the layout of the Pretzel application and its core features.

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
- 26th March 2025 - Making genotypic data interoperable: What is it, why is it important and how do you achieve it?
- 28th May 2025 - Trait characterisation in Brassica and Oat

- ___Next Community of Practice: 20th August 2025 - Linking genebank passport and genotype data with Genolink___

Slides and recordings of past sessions are available on request from adam.dimech@agriculture.vic.gov.au.

If you are interested in receiving updates about upcoming Community of Practice sessions, please email adam.dimech@agriculture.vic.gov.au.

## Workshops

- June 6th 2025 - Australasian Plant Breeding Conference 2025, Fremantle, Perth, Australia

- ___Next workshop: 15th September 2025 - 8th International Food Legume Research Conference and 5th Australian Pulse Conference in Perth, Western Australia___
- More details: https://www.iflrc-apc2025.com/pre-conference-workshops/

Training materials from previous workshops is available here: https://docs.plantinformatics.io/Workshops/workshops/




