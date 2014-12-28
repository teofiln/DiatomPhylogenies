---
title: "Diatom Phylogenies in OneZoom format"
author: "Compiled by Teofil Nakov"
output: 
  html_document:
    toc: true
    theme: readable
    highlight: pygments
---

## About

A web space to store published phylogenies of diatoms and other algae. The repository holds two general types of files:

* methodologicaly explicit phylogenetic trees based on phenotypic or genetic data. These are trees derived from coded data via a tree building algorithm.

* informal hypotheses about evolutionary relationships.These are diagrams reflecting author's interpretation or beleif. They are derived from data that in most cases is not formally coded or procesed through a tree building program. There wont be many of these to start with.

Each tree is represented by the following:

1. the phylogenetic tree displayed in the wonderful OneZoom Tree of Life Explorer format

2. doi or link of the publication where this tree comes from (if available)

3. TreeBase or Dryad study ID of the publication where nexus files of the tree and data can be found (if available)

4. If 2 and/or 3 are missing, a full reference where the tree comes from is provided.

*******

## Trees

### Tree of the Cymbellales from Nakov et al. 2014 [Phycologia](http://www.phycologia.org/doi/abs/10.2216/14-002.1?journalCode=phya)

[Cymbellales - partitioned by-gene-by-codon](trees/OneZoomCymb.1.html)

[Cymbellales - partitioned by-rate](trees/OneZoomCymb.2.html)

[Cymbellales - with PhyloBayes' CAT model](trees/OneZoomCymb.3.html)

TreeBase: 15699

Note: Node ages are arbitrary as the published trees are not proportional to time. The phylograms reported in the paper were smoothed to relative time chronograms with root age 50 million years.

***

### Relative-time ultrametric tree of diatoms and Bolidomonas from Nakov et al. 2014 [ISME-J](http://www.nature.com/ismej/journal/v9/n1/full/ismej2014108a.html)

[Diatoms + Bolidomonas](trees/OneZoom_Nakov2014ISME.html)

Data and trees: http://teofil.discindo.org/data-and-downloads/

Note: The tree is displayed with an _arbitrary_ root age of 100 million years (as in the original publication).

***

### Chronogram of the Thalassiosirales from Alverson 2014, [Paleobiology](http://www.psjournals.org/doi/abs/10.1666/12055)

[Thalassiosirales](trees/OneZoomAlverson2013tree.html)

Dryad: doi 10.5061/dryad.85q50

***

### Chronogram of Pinnularia and outgroup taxa from Souffreau et al. 2011, [Molecular Phylogenetics and Evolution](http://www.sciencedirect.com/science/article/pii/S1055790311003927)

[Pinnularia](trees/OneZoomSouffreau2011.html)

TreeBase: 11769

***

### Tree of diatoms and a number of closely and distantly related eukaryotes from Theriot et al. 2009, [European Journal of Phycology](http://www.tandfonline.com/doi/abs/10.1080/09670260902749159#.UtKb9fhY6Xo)

[Diatoms and eukaryotes](trees/OneZoomTheriot2009.html)

TreeBase: 10114

Note: Branch lengths and node ages on this tree are meaningless. The TreeBase entry for this tree does not include branch lengths. To make the tree compatible with OneZoom, polytomies were first randomly resolved and branch lengths added by sampling from a normal distribution. This artificial "phylogram" was then smoothed to a relative time chronogram with root age 1 billion years. This is a larger tree with 1336 taxa and the diatoms are at the very tip.

***

### Tree of diatoms and Bolidomonas as outgroup from Theriot et al. 2010, [Plant Ecology and Evolution](http://www.ingentaconnect.com/content/botbel/plecevo/2010/00000143/00000003/art00005)

[Diatoms and Bolidomonas](trees/OneZoomTheriot2010.html)

TreeBase: S10953

Note: Node ages on this tree are arbitrary as the published tree is not proportional to time. The phylogram reported in the paper was smoothed to a relative time chronogram with root age 500 million years.

***

### Tree of diatoms and Bolidomonas as outgroup from Ashworth et al. 2013, [Journal of Phycology](http://onlinelibrary.wiley.com/doi/10.1111/jpy.12131/abstract)

[Diatoms and Bolidomonas](trees/OneZoomAshworth2013.html)

Note: Node ages on this tree are arbitrary as the published tree is not proportional to time. The phylogram reported in the paper was smoothed to a relative time chronogram with root age 500 million years.

***

### Tree of raphid diatoms from Ruck and Theriot 2011, [Protist](http://www.sciencedirect.com/science/article/pii/S1434461011000071)

[Raphid diatoms](trees/OneZoomRuck2011.html)

TreeBase: S11192

Note: Node ages on this tree are arbitrary as the published tree is not proportional to time. The phylogram reported in the paper was smoothed to a relative time chronogram with root age 100 million years.

***

### Tree of heterokonts and outgroups from Goertzen and Theriot 2003, [Journal of Phycology](http://onlinelibrary.wiley.com/doi/10.1046/j.1529-8817.2003.01238.x/abstract)

[Heterokonts and outgroups - SSU tree](trees/OneZoomGoertzen2003.SSU.html)

[Heterokonts and outgroups - rbcL tree](trees/OneZoomGoertzen2003.rbcl.html)

[Heterokonts and outgroups - SSU + rbcL tree](trees/OneZoomGoertzen2003.comb.html)

TreeBase: S909

Note: Branch lengths and node ages on these trees are meaningless. The TreeBase entry for these trees does not include branch lengths. To make the tree compatible with OneZoom, branch lengths added by sampling from an exponential distribution with rate=10. This artificial "phylogram" was then smoothed to a relative time chronogram with root age 500 million years.

***

### Trees of Amphora among other raphid taxa from Sato et al. 2013, [Phycologia](http://www.phycologia.org/doi/abs/10.2216/12-072.1)

[Amphora and relatives - Maximum likelihood tree](trees/OneZoomSato13_ML.html)

[Amphora and relatives - Bayesian inference tree](trees/OneZoomSato13_BI.html)

TreeBase: S13483

Note: The trees were scaled to 100 million years root age. The node ages are arbitrary.

***

### Tree of diatoms and Bolidomonas from Sato et al. 2008, [Phycologia](http://www.phycologia.org/doi/abs/10.2216/08-04.1)

[Diatoms and Bolidomonas - focus on Psammoneis](trees/OneZoomSato2008.html)

TreeBase: S2106

Note: Branch lengths and node ages on this tree are meaningless. The TreeBase entry did not include branch lengths. To make the tree compatible with OneZoom, branch lengths added by sampling from an exponential distribution with rate=10. This artificial "phylogram" was then smoothed to a relative time chronogram with root age 500 million years.

***

### Tree of diatoms and Bolidomonas from Sato et al. 2008, [Phycologia](http://www.phycologia.org/doi/abs/10.2216/PH08-02.1)

[Diatoms and Bolidomonas - focus on Pseudostriatella](trees/OneZoomSato2008B.html)

TreeBase: S2107

Note: Branch lengths and node ages on this tree are meaningless. The TreeBase entry did not include branch lengths. To make the tree compatible with OneZoom, branch lengths added by sampling from an exponential distribution with rate=10. This artificial "phylogram" was then smoothed to a relative time chronogram with root age 500 million years.

***

### Tree of Skeletonema and outgroups from Sarno et al. 2007, [Protist](http://www.sciencedirect.com/science/article/pii/S1434461007000739)

[Skeletonema and ougroups](trees/OneZoomSarno.html)

TreeBase: S1922

Note: Branch lengths and node ages on this tree are meaningless. The TreeBase entry did not include branch lengths. To make the tree compatible with OneZoom, branch lengths added by sampling from an exponential distribution with rate=10. This artificial "phylogram" was then smoothed to a relative time chronogram with root age 20 million years.

***

### Tree of Thalassiosirales from Alverson 2007, [Limnology & Oceanoraphy](http://aslo.org/lo/toc/vol_52/issue_4/1420.html)

[Thalassiosirales - tree from silicon transported genes (SIT)](trees/OneZoomSarno.html)

TreeBase: S2047

Note: Branch lengths and node ages on this tree are meaningless. The TreeBase entry did not include branch lengths. To make the tree compatible with OneZoom, branch lengths added by sampling from an exponential distribution with rate=10. This artificial "phylogram" was then smoothed to a relative time chronogram with root age 100 million years.

***

### Trees based on morphological data of Cyclotella nana (Thalassiosira pseudonana) and allies from Alverson et al. 2011, [BMC Evolutionary Biology](http://www.biomedcentral.com/1471-2148/11/125)

[Cyclotella nana and allies - Parsimony 1](trees/OneZoomCnana.1.html)

[Cyclotella nana and allies - Parsimony 2](trees/OneZoomCnana.2.html)

[Cyclotella nana and allies - Parsimony 3](trees/OneZoomCnana.3.html)

[Cyclotella nana and allies - Parsimony 4](trees/OneZoomCnana.4.html)

[Cyclotella nana and allies - Parsimony 5](trees/OneZoomCnana.5.html)

[Cyclotella nana and allies - Parsimony 6](trees/OneZoomCnana.6.html)

[Cyclotella nana and allies - Parsimony 7](trees/OneZoomCnana.7.html)

[Cyclotella nana and allies - Parsimony 8](trees/OneZoomCnana.8.html)

TreeBase: S11009

Note: Branch lengths and node ages on these trees are meaningless. The TreeBase entry did not include branch lengths. To make the trees compatible with OneZoom, branch lengths added by sampling from an exponential distribution with rate=10. Artificial "phylograms" were then smoothed to relative time chronograms with root age 100 million years.

***

### Trees of Stephanodiscus based on morphological data from Julius et al. 2006, [Phycological Research](http://onlinelibrary.wiley.com/doi/10.1111/j.1440-1835.2006.00436.x/abstract)

[Stephanodiscus - without S. kasuensis - Parsimony](trees/OneZoom_woKas.html)

[Stephanodiscus - with S. kasuensis - Parsimony. Polytomies randomly resolved.](trees/OneZoom_wKas.1.html)

[Stephanodiscus - with S. kasuensis - Parsimony. Polytomies randomly resolved.](trees/OneZoom_wKas.2.html)

[Stephanodiscus - with S. kasuensis - Parsimony. Polytomies randomly resolved.](trees/OneZoom_wKas.3.html)

TreeBase: S11011

Note: Branch lengths and node ages on these trees are meaningless. The TreeBase entry did not include branch lengths. To make the trees compatible with OneZoom, branch lengths added by sampling from an exponential distribution with rate=10. Artificial "phylograms" were then smoothed to relative time chronograms with root age 20 million years.

***
