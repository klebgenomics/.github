This is the home for Klebsiella genomics tools and resources developed collaboratively by the teams of [Kat Holt](https://holtlab.net) ([LSHTM](https://www.lshtm.ac.uk)) and Kelly Wyres (Monash University).

------

<img src="https://github.com/klebgenomics/.github/blob/main/profile/kaptive_logo.png" alt="Kaptive" width="200">

  
[Kaptive](https://github.com/katholt/Kaptive) is commandline software for identifying surface polysaccharide loci (capsule and O antigen) from genome assemblies. It was initially developed for the _Klebsiella pneumoniae_ species complex, but also includes reference databases for _Acinetobacter baumannii_ and _Vibrio paramaemolyticus_. 

  
You can also run a graphical version of Kaptive via [this web interface](http://kaptive-web.erc.monash.edu/) (which hosts [Kaptive-Web source code](https://github.com/kelwyres/Kaptive-Web)).

A step-by-step Kaptive tutorial is also available at [bit.ly/kaptive-workshop](https://bit.ly/kaptive-workshop).

Major contributors are [Ryan Wick](https://github.com/rrwick), [Margaret Lam](https://scholar.google.com.au/citations?user=mjNrNqMAAAAJ&hl=en) and [Tom Stanton](https://github.com/orgs/klebnet/people/tomdstanton).
    
------
    
<img src="https://github.com/klebgenomics/.github/blob/main/profile/kleborate-logo.png" alt="Kleborate" width="200">
    
Kleborate is a tool to screen genome assemblies of _Klebsiella pneumoniae_ and the _Klebsiella pneumoniae_ species complex (KpSC) for:
 * MLST sequence type
 * species (e.g. _K. pneumoniae_, _K. quasipneumoniae_, _K. variicola_, etc.)
 * ICE<i>Kp</i> associated virulence loci: yersiniabactin (_ybt_), colibactin (_clb_), salmochelin (_iro_), hypermucoidy (_rmpA_)
 * virulence plasmid associated loci: salmochelin (_iro_), aerobactin (_iuc_), hypermucoidy (_rmpA_, _rmpA2_)
 * antimicrobial resistance determinants: acquired genes, SNPs, gene truncations and intrinsic β-lactamases
 * K (capsule) and O antigen (LPS) serotype prediction, via _wzi_ alleles and [Kaptive](https://github.com/katholt/Kaptive)

You may also be interested in [Kleborate-viz](https://kleborate.erc.monash.edu/), a ShinyR app for visualising Kleborate output.

A step-by-step tutorial, illustrating how to use Kleborate and interpret the data, is available at [bit.ly/kleborate-workshop](https://bit.ly/kleborate-workshop)

Major contributors are [Ryan Wick](https://github.com/rrwick) and [Margaret Lam](https://scholar.google.com.au/citations?user=mjNrNqMAAAAJ&hl=en).
    
------
      
### Other resources
  * [KleborateR](https://github.com/klebnet/KleborateR) - developed by Tom Stanton, for analysing Kaptive and Kleborate output
  * [Kleborate Workshop Data](https://github.com/katholt/kleborate_workshop_data) - used in the [Kleborate Workshop](https://bit.ly/kleborate-workshop)
  * [Klebs Genome Assemblies](https://github.com/katholt/KlebsGenomes3) from the paper "Genomic analysis of diversity, population structure, virulence, and antimicrobial resistance in Klebsiella pneumoniae, an urgent threat to public health" [(Holt et al, 2015 PNAS)](https://doi.org/10.1073/pnas.1501049112)
