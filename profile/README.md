This is the home for Klebsiella genomics tools and resources developed collaboratively by the teams of [Kat Holt](https://holtlab.net) ([LSHTM](https://www.lshtm.ac.uk)) and Kelly Wyres (Monash University).

------

<img src="https://github.com/klebgenomics/.github/blob/main/profile/kaptive_logo.png" alt="Kaptive" width="200">

  
[Kaptive](https://github.com/katholt/Kaptive) is commandline software for identifying surface polysaccharide loci (capsule and O antigen) from genome assemblies. It was initially developed for the _Klebsiella pneumoniae_ species complex, but also includes reference databases for _Acinetobacter baumannii_ and _Vibrio paramaemolyticus_. 
  
You can also run a graphical version of Kaptive via [this web interface](http://kaptive-web.erc.monash.edu/) (which hosts [Kaptive-Web source code](https://github.com/kelwyres/Kaptive-Web)).

Code and resources:
* [Kaptive code](https://github.com/katholt/Kaptive) 
* [Kaptive wiki](https://github.com/katholt/Kaptive/wiki), including instructions and info on Kaptive logic
* [Kaptive-Web](https://github.com/kelwyres/Kaptive-Web), an online version of Kaptive where you can upload genomes and visualise results
* [Kaptive Tutorial](https://bit.ly/kaptive-workshop), illustrating how to use Kaptive and interpret the data

Major contributors are [Ryan Wick](https://github.com/rrwick), [Margaret Lam](https://scholar.google.com.au/citations?user=mjNrNqMAAAAJ&hl=en) and [Tom Stanton](https://github.com/orgs/klebnet/people/tomdstanton).
    
------
    
<img src="https://github.com/klebgenomics/.github/blob/main/profile/kleborate-logo.png" alt="Kleborate" width="200">
    
[Kleborate](https://github.com/katholt/kleborate) is a tool to screen genome assemblies of _Klebsiella pneumoniae_ and the _Klebsiella pneumoniae_ species complex (KpSC) for:
 * MLST sequence type
 * species (e.g. _K. pneumoniae_, _K. quasipneumoniae_, _K. variicola_, etc.)
 * ICE<i>Kp</i> associated virulence loci: yersiniabactin (_ybt_), colibactin (_clb_), salmochelin (_iro_), hypermucoidy (_rmpA_)
 * virulence plasmid associated loci: salmochelin (_iro_), aerobactin (_iuc_), hypermucoidy (_rmpA_, _rmpA2_)
 * antimicrobial resistance determinants: acquired genes, SNPs, gene truncations and intrinsic β-lactamases
 * K (capsule) and O antigen (LPS) serotype prediction, via _wzi_ alleles and [Kaptive](https://github.com/katholt/Kaptive)

Code and resources:
* [Kleborate code](https://github.com/katholt/kleborate) 
* [Kleborate wiki](https://github.com/katholt/Kleborate/wiki), including instructions and info on Kleborate logic
* [Kleborate-viz](https://kleborate.erc.monash.edu/), a ShinyR app for visualising Kleborate output
* [Kleborate Tutorial](https://bit.ly/kleborate-workshop), illustrating how to use Kleborate and interpret the data

Major contributors are [Ryan Wick](https://github.com/rrwick) and [Margaret Lam](https://scholar.google.com.au/citations?user=mjNrNqMAAAAJ&hl=en).
    
------
      
### Other resources from the team
  * [KleborateR](https://github.com/klebnet/KleborateR) - developed by Tom Stanton, for analysing Kaptive and Kleborate output
  * [Kleborate Workshop Data](https://github.com/katholt/kleborate_workshop_data) - used in the [Kleborate Workshop](https://bit.ly/kleborate-workshop)
  * [Klebs Genome Assemblies](https://github.com/katholt/KlebsGenomes3) from the paper "Genomic analysis of diversity, population structure, virulence, and antimicrobial resistance in Klebsiella pneumoniae, an urgent threat to public health" [(Holt et al, 2015 PNAS)](https://doi.org/10.1073/pnas.1501049112)
  
------
  
### KlebNet 

Together with Sylvain Brisse at the Institut Pasteur, we coordinate the KlebNet network for _Klebsiella_ surveillance. You can sign up [here](https://groups.google.com/g/klebnet/members?pli=1) to join the email list and participate in working groups and upcoming events.

#### KlebNet Genomic Surveillance Platform

We also work in partnership with teams at the [Institut Pasteur](https://bigsdb.pasteur.fr/) and [Pathogenwatch](https://pathogen.watch/) to coordinate tools and platforms for Klebsiella genomic surveillance, under an initiative known as the [KlebNet Genomic Surveillance Platform](https://klebnet.org/).
