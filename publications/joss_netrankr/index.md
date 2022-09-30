---
date: "2022-09-26"
description: |
    One of the key concepts in network science is network centrality. Centrality seeks to provide
    the answer to the question of who (or what) is important in a network depending on the
    underlying process forming the network and the empirical phenomenon in question....
subtitle: David Schoch
title: "netrankr: An R package for total, partial, and probabilistic rankings in networks"
image: featured.png
title-block-style: none
toc: false
---

<button type="button" class="btn btn-outline-success"><a
href="https://github.com/schochastics/netrankr">R package</a></button>
<button type="button" class="btn btn-outline-success"><a href="https://doi.org/10.21105/joss.04563">journal</a></button>


## Abstract 
One of the key concepts in network science is network centrality. Centrality seeks to provide
the answer to the question of who (or what) is important in a network depending on the
underlying process forming the network and the empirical phenomenon in question. In a
nutshell, an actor in a network is more central if they have better relations, where the definition
of better relations depends on the conceptualization of structural importance. Applications of
centrality can be found in any field where networks arise. In social networks, we may simply
be interested in finding the most popular user. In bioinformatics, centrality is used to detect
essential proteins in protein-protein interaction networks (Jeong et al., 2001). Even in sports,
centrality is applied to rank athletes or teams (Radicchi, 2011). A myriad of indices have
been proposed, all with differing interpretations of what constitutes a central position within a
network. Although netrankr offers this traditional approach to network centrality, its main
focus lies on alternative assessments of centrality based on partial and probabilistic rankings in
networks.

*Journal of Open Source Software* 7 (77), 4563