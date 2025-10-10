This is the home for _Klebsiella_ genomics tools and resources developed collaboratively by the teams of [Kat Holt](https://holtlab.net) ([LSHTM](https://www.lshtm.ac.uk)) and [Kelly Wyres](https://wyreslab.com/) ([Monash University](https://www.monash.edu/medicine/ccs/infectious-diseases/home)).

------

<img src="https://github.com/klebgenomics/.github/blob/main/profile/kaptive_logo.png" alt="Kaptive" width="200">

  
[Kaptive](https://github.com/klebgenomics/Kaptive) is commandline software for identifying surface polysaccharide loci (capsule and O antigen) from genome assemblies. It was initially developed for the _Klebsiella pneumoniae_ species complex, but also includes reference databases for _Acinetobacter baumannii_ and _Vibrio paramaemolyticus_. 
  
You can also run a graphical version of Kaptive via [this web interface](http://kaptive-web.erc.monash.edu/) (which hosts [Kaptive-Web source code](https://github.com/kelwyres/Kaptive-Web)).

Code and resources:
* [Kaptive code](https://github.com/klebgenomics/Kaptive) 
* [Kaptive docs](https://kaptive.readthedocs.io/en/latest/), including instructions and info on Kaptive logic
* [Kaptive-Web](https://github.com/kelwyres/Kaptive-Web), an online version of Kaptive where you can upload genomes and visualise results
* [Kaptive Tutorial](https://bit.ly/kaptive-workshop), illustrating how to use Kaptive and interpret the data

Major contributors are Kelly Wyres and [Tom Stanton](https://github.com/orgs/klebnet/people/tomdstanton). Earlier versions were developed by [Ryan Wick](https://github.com/rrwick), with contributions from [Margaret Lam](https://scholar.google.com.au/citations?user=mjNrNqMAAAAJ&hl=en) and Kat Holt.
    
------
    
<img src="https://github.com/klebgenomics/.github/blob/main/profile/kleborate-logo.png" alt="Kleborate" width="200">
    
[Kleborate](https://github.com/klebgenomics/kleborate) is a tool to screen genome assemblies of _Klebsiella pneumoniae_ and the _Klebsiella pneumoniae_ species complex (KpSC) for:
 * MLST sequence type
 * species (e.g. _K. pneumoniae_, _K. quasipneumoniae_, _K. variicola_, etc.)
 * ICE<i>Kp</i> associated virulence loci: yersiniabactin (_ybt_), colibactin (_clb_), salmochelin (_iro_), hypermucoidy (_rmpA_)
 * virulence plasmid associated loci: salmochelin (_iro_), aerobactin (_iuc_), hypermucoidy (_rmpA_, _rmpA2_)
 * antimicrobial resistance determinants: acquired genes, SNPs, gene truncations and intrinsic β-lactamases
 * K (capsule) and O antigen (LPS) serotype prediction, via _wzi_ alleles and [Kaptive](https://github.com/klebgenomics/Kaptive)

Code and resources:
* [Kleborate code](https://github.com/klebgenomics/kleborate) 
* [Kleborate docs](https://kleborate.readthedocs.io/en/latest/), including instructions and info on Kleborate logic
* [Kleborate-viz](https://kleborate.erc.monash.edu/), a ShinyR app for visualising Kleborate output (which hosts the [Kleborate-viz source code](https://github.com/klebgenomics/Kleborate-viz))
* [Kleborate Tutorial](https://docs.google.com/document/d/1R61bQbBngpiDB2Gl_eXigePBVakYZEjy/edit), illustrating how to use Kleborate and interpret the data
* Details of Kleb specific AMR typing including [SHV alleles](https://doi.org/10.1099/mgen.0.001294) and [ciprofloxacin resistance prediction](https://github.com/klebgenomics/cipropaper)
* [This paper](https://www.microbiologyresearch.org/content/journal/mgen/10.1099/mgen.0.000936) explores the accuracy of Kaptive & Kleborate genotyping on genomes assembled solely from nanopore data (generated using Mk9.4.1 flowcells). We benchmark performance against genotypes called from Illumina-based assemblies, and hybrid Illumina+nanopore assemblies, using 55 _Klebsiella pneumoniae_ genomes. 

Major contributors are Kat Holt, Mary Maranga, Margaret Lam, Ebenezer Foster-Nyarko and Kara Tsang. Earlier versions were developed by [Ryan Wick](https://github.com/rrwick).
    
------

### KlebNET-GSP Epi Consortium

The KlebNET-GSP Epidemiology Consortium collates publicly available _K. pneumoniae_ species complex (KpSC) whole genome sequences with matched isolate source and sampling information, to support:

* KlebNET Clone Reviews – collaborative genomic epidemiology reviews of globally distributed clones (e.g multi-drug resistant or hypervirulent clones);
* KlebNET Clone Risk Framework – a systematic risk framework to support global genomic surveillance of _K. pneumoniae_;
* [KlebNET Metadata Repository](https://github.com/klebgenomics/KlebNET-Metadata-Repository-Database) – a comprehensive open-access repository of enhanced contextual meta-data, facilitating use and reuse of publicly available data by the global research community by enabling robust epidemiology and genomic meta-analyses.

The consortium is coordinated by Kelly Wyres and Hina Salimuddin (Monash University, Australia) on behalf of the KlebNet-GSP and operates according to its [Terms of Reference](https://docs.google.com/document/d/12wuWxgucGVYnnKHZ8xvDCVLQhV0tEafCb2CuxClw0Hw/edit?usp=sharing).

Participation in the consortium is contingent on contributing [contextual metadata](https://github.com/klebgenomics/Klebsiella-genome-metadata/tree/main) for _Klebsiella_ genome sequences that have been deposited in public databases, for inclusion in the [metadata repository](https://github.com/klebgenomics/KlebNET-Metadata-Repository-Database) and consortium analyses.

To join, please complete the [registration form](https://docs.google.com/forms/d/e/1FAIpQLSe9yoXfh0MP_tqvWh7RqxFKXr30MMAQkeZ_sxhEPyIsQX43dQ/viewform).

Relevant repositories:
* [Metadata Template](https://github.com/klebgenomics/Klebsiella-genome-metadata)
* [Metadata Repository](https://github.com/klebgenomics/KlebNET-Metadata-Repository-Database)
* Clone Risk Framework

------

### _Klebsiella_ neonatal sepsis

**K and O serotype distributions and coverage, from _Klebsiella pneumoniae_ neonatal sepsis in African and South Asian countries**

We recently published a [preprint](https://doi.org/10.1101/2025.06.28.25330253) presenting collaborative meta-analysis of K and O serotypes amongst neonatal sepsis isolates from 35 sites across 13 studies.
* Data, R code for modelling and visualisation, and all tables/figures from the paper are in this repository: [https://github.com/klebgenomics/KlebNNSsero](https://github.com/klebgenomics/KlebNNSsero) (developed by Kat Holt and Shaun Keegan)
* An R shiny app to explore the data is available [here](https://klebsiella.shinyapps.io/neonatal/), app code is [here](https://github.com/klebgenomics/KlebNNSapp) (developed by Tom Stanton)


**Transmission estimator**

Shiny app designed to identify transmission clusters among neonatal sepsis bacterial isolates using genomic (genetic distance) and epidemiological (spatiotemporal) data.

* [Code](https://github.com/klebgenomics/transmission_estimator)
* [App](https://klebsiella.shinyapps.io/transmission_estimator)

(developed by Erkison Odih)

------    

### Other resources from the team
  * [KlebRef](https://github.com/klebgenomics/KlebRef) - Database of genomic data and typing information for _Klebsiella_ reference isolates available in public repositories
  * [KleborateR](https://github.com/klebnet/KleborateR) - developed by Tom Stanton, for analysing Kaptive and Kleborate output
  * [Kleborate Workshop Data](https://github.com/klebgenomics/kleborate_workshop_data) - used in the [Kleborate Workshop](https://bit.ly/kleborate-workshop)
  * [Klebs Genome Assemblies](https://github.com/klebgenomics/KlebsGenomes3) from the paper "Genomic analysis of diversity, population structure, virulence, and antimicrobial resistance in _Klebsiella pneumoniae_, an urgent threat to public health" [(Holt et al, 2015 PNAS)](https://doi.org/10.1073/pnas.1501049112)
  * [KpSC-pan-metabolic-model](https://github.com/kelwyres/KpSC-pan-metabolic-model) - a pan genome-scale metabolic model for the _K. pneumoniae_ species complex developed for use as a reference with [Bactabolize](https://github.com/kelwyres/Bactabolize) - a pipeline for high-throughput generation of strain-specific metabolic models and growth phenotype predictions. Developed by [Kelly Wyres, Ben Vezina and Helena Cooper]((https://wyreslab.com/team)) with major contributions from [Jane Hawkey](https://research.monash.edu/en/persons/jane-hawkey) and [Stephen Watts](https://github.com/scwatts).
