This is the home for _Klebsiella_ genomics tools and resources developed collaboratively by the teams of [Kat Holt](https://holtlab.net) and [Kelly Wyres](https://wyreslab.com/), at ([LSHTM](https://www.lshtm.ac.uk)) and ([Monash University](https://www.monash.edu/medicine/ccs/infectious-diseases/home)).

------

<img src="https://github.com/klebgenomics/.github/blob/main/profile/kaptive_logo.png" alt="Kaptive" width="200">

  
[Kaptive](https://github.com/klebgenomics/Kaptive) is commandline software for identifying surface polysaccharide loci (capsule and O antigen) from genome assemblies. The software was initially developed for the _Klebsiella pneumoniae_ species complex, but there are now typing databases for several other organisms (each with their own repository). 
  
You can also run a graphical version of Kaptive via the [Kaptive-Web](http://kaptive-web.erc.monash.edu/) online interface developed by [Tom Stanton](https://github.com/orgs/klebnet/people/tomdstanton).

Code and resources:
* [Kaptive code](https://github.com/klebgenomics/Kaptive) 
* [Kaptive docs](https://klebgenomics.github.io/Kaptive/), including instructions and info on Kaptive logic
* [Kaptive v3 Tutorial](https://docs.google.com/document/d/1EXZanC6uCbhAniVyJn91HOVD8JF6DLRZxmFPGs_nlME/edit?usp=sharing), illustrating how to use Kaptive and interpret the data
 * [Kaptive-Web](http://kaptive-web.erc.monash.edu/), an online version of Kaptive where you can upload genomes and visualise results


Kaptive databases:
* [_Klebsiella pneumoniae_ Species Complex K and O](https://github.com/klebgenomics/KpSC_surface_antigen_loci)
* [_Klebsiella oxytoca_ Species Complex K and O](https://github.com/klebgenomics/KoSC-surface-antigen-loci/)
* For details on all databases supported by Kaptive, including third-party databases for _Acinetobacter baumanii_ and _Escherchia coli_, see the docs [here](https://klebgenomics.github.io/Kaptive/db/overview.html#available-databases)

Major contributors are Kelly Wyres and [Tom Stanton](https://github.com/orgs/klebnet/people/tomdstanton). Earlier versions were developed by [Ryan Wick](https://github.com/rrwick), with contributions from [Margaret Lam](https://scholar.google.com.au/citations?user=mjNrNqMAAAAJ&hl=en) and Kat Holt.
    
------
    
<img src="https://github.com/klebgenomics/.github/blob/main/profile/kleborate-logo.png" alt="Kleborate" width="200">

[Kleborate](https://github.com/klebgenomics/kleborate) was initially developed to type genome assemblies of _Klebsiella pneumoniae_ and its species complex (KpSC), but now also includes modules for typing _Klebsiella oxytoca_ species complex (KoSC) and _Escherichia coli/Shigella_.

Code and resources:
* [Kleborate code](https://github.com/klebgenomics/kleborate) 
* [Kleborate docs](https://kleborate.readthedocs.io/en/latest/) (in English and French)
* [Kleborate Tutorial](https://docs.google.com/document/d/1R61bQbBngpiDB2Gl_eXigePBVakYZEjy), illustrating how to use Kleborate and interpret the data

[This paper](https://doi.org/10.1099/mgen.0.000936) explores the accuracy of Kaptive & Kleborate genotyping on genomes assembled solely from Oxford Nanopore data (generated using Mk9.4.1 flowcells). We benchmark performance against genotypes called from Illumina-based assemblies, and hybrid Illumina+nanopore assemblies, using 55 _Klebsiella pneumoniae_ genomes. 

Major contributors are Kat Holt, Mary Maranga, Margaret Lam, Ebenezer Foster-Nyarko and Kara Tsang. Earlier versions were developed by [Ryan Wick](https://github.com/rrwick).
    
------

### KlebNET-GSP Epi Consortium

The [KlebNET-GSP Epidemiology Consortium](https://klebnet.org/klebnet-gsp-epidemiology-consortium/) collates publicly available _K. pneumoniae_ species complex (KpSC) whole genome sequences with matched isolate source and sampling information, to support:

* KlebNET Clone Reviews – collaborative genomic epidemiology reviews of globally distributed clones (e.g multi-drug resistant or hypervirulent clones);
* KlebNET Clone Risk Framework – a systematic risk framework to support global genomic surveillance of _K. pneumoniae_;
* [KlebNET Metadata Repository](https://github.com/klebgenomics/KlebNET-Metadata-Repository-Database) – a comprehensive open-access repository of enhanced contextual meta-data, facilitating use and reuse of publicly available data by the global research community by enabling robust epidemiology and genomic meta-analyses.

The [Consortium](https://klebnet.org/klebnet-gsp-epidemiology-consortium/) is coordinated by Kelly Wyres and Hina Salimuddin (Monash University, Australia) on behalf of the [KlebNet-GSP](https://klebnet.org/) and operates according to its [Terms of Reference](https://docs.google.com/document/d/12wuWxgucGVYnnKHZ8xvDCVLQhV0tEafCb2CuxClw0Hw/edit?usp=sharing).

Participation in the consortium is contingent on contributing [contextual metadata](https://github.com/klebgenomics/Klebsiella-genome-metadata/) for _Klebsiella_ genome sequences that have been deposited in public databases, for inclusion in the [metadata repository](https://github.com/klebgenomics/KlebNET-Metadata-Repository-Database) and consortium analyses.

To join, please complete the [registration form](https://docs.google.com/forms/d/e/1FAIpQLSe9yoXfh0MP_tqvWh7RqxFKXr30MMAQkeZ_sxhEPyIsQX43dQ/viewform).

Relevant repositories:
* [Metadata Template](https://github.com/klebgenomics/Klebsiella-genome-metadata)
* [Metadata Repository](https://github.com/klebgenomics/KlebNET-Metadata-Repository-Database)
* Clone Risk Framework

------

### _Klebsiella_ neonatal sepsis

**K and O serotype distributions and coverage, from _Klebsiella pneumoniae_ neonatal sepsis in African and South Asian countries**

We recently published a [paper](https://doi.org/10.1371/journal.pmed.1004879) presenting collaborative meta-analysis of K and O serotypes amongst neonatal sepsis isolates from 35 sites across 13 studies.
* Data, R code for modelling and visualisation, and all tables/figures from the paper are in this repository: [https://github.com/klebgenomics/KlebNNSsero](https://github.com/klebgenomics/KlebNNSsero) (developed by Kat Holt and Shaun Keegan)
* An R shiny app to explore the data is available [here](https://klebsiella.shinyapps.io/neonatal/), app code is [here](https://github.com/klebgenomics/KlebNNSapp) (developed by Tom Stanton)


**Transmission estimator**

The `transmission_estimator` Shiny app is designed to identify transmission clusters among neonatal sepsis bacterial isolates using genomic (genetic distance) and epidemiological (spatiotemporal) data was developed for this paper, and can be used to undertake cluster analysis with your own data. The app allows users to explore the impact of temoporal and distance thresholds on clustering estimates, and to visualise cluster fractions and timelines stratified by other variables such as location or sequence type. (developed by Erkison Odih)
* [Code](https://github.com/klebgenomics/transmission_estimator)
* [App](https://klebsiella.shinyapps.io/transmission_estimator)

We used the app in a recently published [paper](https://doi.org/10.1371/journal.pmed.1005077) presenting collaborative meta-analysis of transmission cluster rates amongst neonatal sepsis isolates from 27 hospitals across 13 countries.
* Data, R code for analysis and visualisation, and all tables/figures from the paper are in this repository: [https://github.com/klebgenomics/KlebNNS_transmission](https://github.com/klebgenomics/KlebNNS_transmission) (developed by Erkison Odih)

------    

### Other resources from the team
  * [KlebRef](https://github.com/klebgenomics/KlebRef) - Database of genomic data and typing information for _Klebsiella_ reference isolates available in public repositories
  * [KleborateR](https://github.com/klebnet/KleborateR) - developed by Tom Stanton, for analysing Kaptive and Kleborate output
  * [Kleborate Workshop Data](https://github.com/klebgenomics/kleborate_workshop_data) - used in the [Kleborate Tutorial](https://docs.google.com/document/d/1R61bQbBngpiDB2Gl_eXigePBVakYZEjy)
  * [Klebs Genome Assemblies](https://github.com/klebgenomics/KlebsGenomes3) from the paper "Genomic analysis of diversity, population structure, virulence, and antimicrobial resistance in _Klebsiella pneumoniae_, an urgent threat to public health" [(Holt et al, 2015 PNAS)](https://doi.org/10.1073/pnas.1501049112)
  * [KpSC-pan-metabolic-model](https://github.com/kelwyres/KpSC-pan-metabolic-model) - a pan genome-scale metabolic model for the _K. pneumoniae_ species complex developed for use as a reference with [Bactabolize](https://github.com/kelwyres/Bactabolize) - a pipeline for high-throughput generation of strain-specific metabolic models and growth phenotype predictions. Developed by [Kelly Wyres, Ben Vezina and Helena Cooper]((https://wyreslab.com/team)) with major contributions from [Jane Hawkey](https://research.monash.edu/en/persons/jane-hawkey) and [Stephen Watts](https://github.com/scwatts).
  * Data and code for the paper reporting the ciprofloxacin resistance prediction module included in Kleborate [https://github.com/klebgenomics/cipropaper](https://github.com/klebgenomics/cipropaper), "Ciprofloxacin resistance in _Klebsiella pneumoniae_: phenotype prediction from genotype and global distribution of resistance determinants" [Tsang et al, 2025 BioRxiv](https://doi.org/10.1101/2025.09.24.678318), by the [KlebNET-GSP AMR Genotype-Phenotype Group](https://klebnet.org/amrgenopheno/)
  * Data and code for the paper reporting the ciprofloxacin resistance prediction module included in Kleborate [https://github.com/klebgenomics/cipropaper](https://github.com/klebgenomics/cipropaper), "Ciprofloxacin resistance in _Klebsiella pneumoniae_: phenotype prediction from genotype and global distribution of resistance determinants" [Tsang et al, 2025 BioRxiv](https://doi.org/10.1101/2025.09.24.678318), by the [KlebNET-GSP AMR Genotype-Phenotype Group](https://klebnet.org/amrgenopheno/)
  * Slides from the "_Klebsiella pneumoniae_ Genomic Epidemiology and Antimicrobial Resistance" training lectures delivered by members of the KlebNET Genomic Surveillance Platform in September 2025. [https://github.com/klebgenomics/KlebNetTrainingSep2025](https://github.com/klebgenomics/KlebNetTrainingSep2025)
