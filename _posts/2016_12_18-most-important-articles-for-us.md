---
layout: post
title: Most important articles for us
description: ""
modified: 2016-12-18
category: publications
tags: [publicity, collaboration]
imagefeature: to_the_cloud.jpg
comments: true
share: true
featured: true
---

here is a list of papers that probably everybody on the team should read:

### other people's statistical work:

1. Model Based Clustering (Fraley & Rafterty, 2002): explains the relationship between  density estimation (via gaussian mixture modeling) and clustering.  still the best approach to cluster with medium-dimensional data
7. model selection is arbitrary (George & Foster; 2000): demonstrates that all the different model selection criteria are in fact arbitrary special cases of a general prior with 2 parameters
3. Energy Statistics review (Rizzo & Szekely, 2016): explains energy statistics that can perform a variety of tasks in high-dimensional data
4. Random Forest (Breiman, 2001): introduced random forest practice and theory
5. GMRA (Allard, Chen, Maggioni; 2012): introduces and explains relationships between dictionary learning and machine learning, with theory and implementation
6. MLE for Misspecified Models ([White; 1982](https://www.jstor.org/stable/1912526?seq=1#page_scan_tab_contents)): shows that MLE yields the minimum KL distance between the truth and the feasible region 
7. manifold learning is just kernel pca ([Ham et al., 2004](http://dl.acm.org/citation.cfm?id=1015417))

### other people's data collection:

1. [array tomograph](http://cshprotocols.cshlp.org/content/2010/11/pdb.top89.full.pdf+html)
1. [CLARITY](http://www.nature.com/nmeth/journal/v10/n6/full/nmeth.2481.html) and [iDisco](http://www.cell.com/abstract/S0092-8674(14)01297-5)
1. [serial EM](http://www.nature.com/nature/journal/v471/n7337/abs/nature09802.html)
1. [multimodal MRI](http://www.nature.com/nmeth/journal/v10/n6/abs/nmeth.2482.html)
1. [calcium imaging](http://www.nature.com/nmeth/journal/vaop/ncurrent/full/nmeth.3040.html)
1. [behavior](http://science.sciencemag.org/content/344/6182/386.long)
1. [biomarkers in psychiatry](https://www.researchgate.net/profile/Karen_Seymour2/publication/261507750_Consensus_Report_of_the_APA_Work_Group_on_Neuroimaging_Markers_of_Psychiatric_Disorders/links/0c9605346a4d865d9b000000.pdf)

### our work:

1. incommensurability phenomenon ([Fishkind et al; 2016](http://link.springer.com/article/10.1007/s00357-016-9203-9)): shows that if you run PCA twice on two different samples of noisy data, you get arbitrarily different results
1. You say, I say ([Priebe; 2011](http://www.cis.jhu.edu/~parky/CEP-Publications/scgn-21-2.pdf)): shows that graph invariants are test statistics, and therefore, we can determine which invariants are optimal for any test
1. Graph Matching: Relax at your own risk ([Lyzinski et al; 2016](http://ieeexplore.ieee.org/document/7091002/)): shows that we can use a convex analytic approx. to initialize a non-convex numerical approx, and get good results on an NP-hard problem
1. Consitency of ASE ([Sussman et al; 2012](http://amstat.tandfonline.com/doi/abs/10.1080/01621459.2012.699795)): shows that ASE yields consistent estimators of latent positions, so then we can use them for subsequent inference
1. HSBM ([Lyzinski et al; 2016](http://ieeexplore.ieee.org/document/7769223/)): is the best model of large graphs we know
2. [LOL](https://github.com/neurodata/LOL): shows that simple, computationally efficient tricks based on understanding the geometry of the problem can yield provably better results
1. [MGC](https://www.overleaf.com/read/ygghvtgftzpp): shows that we can use and estimate locality for certain exploitation tasks
1. [FlashGraph](https://arxiv.org/abs/1408.0500): demonstrates the power of semi-external memory modeling
1. [open connectome paper](https://arxiv.org/abs/1306.3543): explains basis of our spatial database
1. [mi-lddmm](https://arxiv.org/abs/1612.00356): the current best approach for nonlinear registration, imho
