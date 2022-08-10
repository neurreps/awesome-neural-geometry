# Symmetry and Geometry in Neural Representations

[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)](https://github.com/neurreps/reading-list/pulls) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Stars](https://img.shields.io/github/stars/neurreps/reading-list?color=yellow)  ![Forks](https://img.shields.io/github/forks/neurreps/reading-list?color=blue&label=Fork)

A curated collection of resources and research related to the geometry of representations in the brain, deep networks, and beyond, collaboratively generated on the [Symmetry and Geometry in Neural Representations](https://www.neurreps.org) [Slack Workspace](http://www.google.com/url?q=http%3A%2F%2Fneurreps.slack.com&sa=D&sntz=1&usg=AOvVaw2f5FLzxM-5cj4szVIPU_EH).

![](https://lh4.googleusercontent.com/vODs2cK98sKA9SVu_K2s-y8RFVmAXR8xEi4yGb6JBGBH73oFnpnhQSgb3C2qt2jFLLys2NY86l6lrPsFx2RpvV-Oqkqdf_TknI0ujQYyTeU2vCbaTgztq6xD-rhp4TJxGg=w1280)



## Contents


- [**Educational Resources**](#resources)
  - [Differential Geometry + Lie Groups](#diffgeo)
  - [Topology](#topology)
  - [Geometric Deep Learning](#gdl)
- [**Software Libraries**](#software)
- [**Research Papers**](#research)
  - [Perspectives](#perspectives)
  - [Neuroscience](#neuro) 
    - [Vision](#vision)
    - [Spatial Navigation](#navigation)
    - [Abstract Representations](#abstract)
    - [Methods](#methods)
  - [Geometric Deep Larning](#gdl)
    - [Invariance and Equivariance](#equivariance)
    - [Disentangling](#disentangling)
    

<br /><br />

<a name="resources" />

# Educational Resources


<a name="diffgeo" />

### Differential Geometry + Lie Groups

#### Textbooks 
* [**Lie Groups, Lie Algebras, and Representations** (2003) <br /> *Brian C. Hall*](https://link.springer.com/book/10.1007/978-3-319-13467-3)
* [**Differential Geometry and Lie Groups: A Computational Perspective** (2020) <br /> *Gallier & Quaintance*](https://link.springer.com/book/10.1007/978-3-030-46040-2)

#### Courses, Lectures, and Videos
* [**Differential Geometry for Computer Science** <br /> *Justin Solomon*](https://youtube.com/playlist?list=PLQ3UicqQtfNvPmZftPyQ-qK1wdXBxj86W)
* [**What is a Manifold?** <br /> *XylyXylyX*](https://youtube.com/playlist?list=PLRlVmXqzHjUQHEx63ZFxV-0Ortgf-rpJo)
* [**Lie Groups and Lie Algebras** <br /> *XylyXylyX*](https://youtube.com/playlist?list=PLRlVmXqzHjURZO0fviJuyikvKlGS6rXrb)


#### Notebooks and Blogposts
* [**Introduction to Differential Geometry and Machine Learning** <br /> *Geomstats Jupyter notebooks*](https://github.com/geomstats/geomstats/tree/master/notebooks)
* [**Differential Geometry for Machine Learning** <br /> *Roger Grosse*](https://metacademy.org/roadmaps/rgrosse/dgml)



<br />

### Topology

#### Courses, Lectures, and Videos
* [**Computational Algebraic Topology** <br /> Vidit Nanda](https://youtube.com/playlist?list=PLnLAqsCN_2ke8_EUd_KoJsLkPO0BKrrc6)

<br />


<a name="gdl" />


### Geometric Deep Learning

#### Textbooks

* [**Geometric Deep Learning: Grids, Groups, Graphs, Geodesics, and Gauges** (2021) <br /> _Michael M. Bronstein, Joan Bruna, Taco Cohen, Petar Veličković_](https://arxiv.org/abs/2104.13478)
* [**Group Theoretical Methods in Machine Learning** (2008) <br /> *Risi Kondor*](http://www.cs.columbia.edu/~jebara/papers/thesisKondor.pdf)
* [**Equivariant Convolutional Networks** (2021) <br /> *Taco Cohen*](https://pure.uva.nl/ws/files/60770359/Thesis.pdf)

#### Courses, Lectures, and Videos

* [**An Introduction to Group Equivariant Deep Learning** (2022) <br /> *UvA*](https://uvadl2c.github.io/)

#### Notebooks and Blogposts
* [**What does 2022 hold for Geometric & Graph ML?** <br /> *Michael Bronstein*](https://towardsdatascience.com/predictions-and-hopes-for-geometric-graph-ml-in-2022-aa3b8b79f5cc)


<br /><br />

<a name="software" />

# Software Libraries


* [**Geomstats**](https://geomstats.github.io/)
* [**Giotto TDA**](https://giotto-ai.github.io/gtda-docs/0.5.1/library.html)



<br /><br />

<a name="research" />

# Research Papers


<a name="perspectives" />

### Perspectives

* [**Symmetry-based representations for artificial and biological general intelligence** (2022)  <br /> *Irina Higgins, Sébastien Racanière, Danilo Rezende.*](https://www.frontiersin.org/articles/10.3389/fncom.2022.836498/full)

<br />

<a name="neuro" />

### Neuroscience

<a name="vision" />

#### Vision

* [**The Lie algebra of visual perception** (1966)  <br /> *William C.Hoffman*](https://www.sciencedirect.com/science/article/abs/pii/0022249666900058) 

* [**Representation of local geometry in the visual system** (1987)  <br /> *Jan Koenderink*](https://link.springer.com/article/10.1007/BF00318371) 

* [**Operational Significance of Receptive Fields Assemblies** (1989)  <br /> *Jan Koenderink*](https://link.springer.com/content/pdf/10.1007/BF00364136.pdf) 

* [**The Visual Cortex is a Contact Bundle** (1989)  <br /> *William C. Hoffman*](http://www.its.caltech.edu/~matilde/VisualCortexContactBundle.pdf) 

* [**Geometric visual hallucinations, Euclidean symmetry and the functional architecture of striate cortex** (2001)  <br /> *Paul C. Bressloff, Jack D. Cowan, Martin Golubitsky, Peter J. Thomas and Matthew C. Wiener*](https://royalsocietypublishing.org/doi/10.1098/rstb.2000.0769) 

* [**The neurogeometry of pinwheels as a sub-Riemannian contact structure** (2003)  <br /> *Jean Petitot*](https://www.sciencedirect.com/science/article/abs/pii/S092842570300072X?casa_token=0mRpfL4cgoQAAAAA:qqV8dNcjLcg7xS1XScDlk20agI3Aa0d_vzvihKM5seCNU-PVuMzTEiI8xaAeTJH5QATLFFo) 

* [**Parsimony, Exhaustivity and Balanced Detection in Neocortex** (2015)  <br /> *Alberto Romagnoni, Jérôme Ribot, Daniel Bennequin, Jonathan Touboul*](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004623) 

* [**Predicting the retinotopic organization of human visual cortex from anatomy using geometric deep learning** (2021)  <br /> *Fernanda L. Ribeiro, Steffen Bollmann, Alexander M. Puckett*](https://www.sciencedirect.com/science/article/pii/S1053811921008971)

* [**Primary visual cortex straightens natural video trajectories** (2021)  <br /> *Olivier J. Hénaff, Yoon Bai, Julie A. Charlton, Ian Nauhaus, Eero P. Simoncelli & Robbe L. T. Goris*](https://www.nature.com/articles/s41467-021-25939-z) 


<a name="navigation" />

#### Spatial Navigation

* [**The intrinsic attractor manifold and population dynamics of a canonical cognitive circuit across waking and sleep** (2019)  <br /> *Rishidev Chaudhuri, Berk Gerçek, Biraj Pandey, Adrien Peyrache & Ila Fiete*](https://www.nature.com/articles/s41593-019-0460-x) 


* [**Toroidal topology of population activity in grid cells** (2022)  <br /> *Richard J. Gardner, Erik Hermansen, Marius Pachitariu, Yoram Burak, Nils A. Baas, Benjamin A. Dunn, May-Britt Moser & Edvard I. Moser*](https://www.nature.com/articles/s41586-021-04268-7) 

<a name="abstract" />

#### Abstract Representations

* [**The Geometry of Abstraction in the Hippocampus and Prefrontal Cortex** (2020) <br /> *Silvia Bernardi, Marcus K.Benna, Matti Rigotti, Jérôme Munuera, Stefano Fusi, Daniel Salzman*](https://www.sciencedirect.com/science/article/pii/S0092867420312289) 


<a name="methods" />

#### Methods

* [**Interpreting neural computations by examining intrinsic and embedding dimensionality of neural activity** (2021) <br /> *Mehrdad Jazayeri, Srdjan Ostojic*](https://arxiv.org/abs/2107.04084) 

<br />

<a name="gdl" />

### Geometric Deep Learning

<a name="gdl-survey" />

#### Theory
* [**Universal Approximation Theorems for Differentiable Geometric Deep Learning** (2022)  <br /> *Anastasis Kratsios, L´eonie Papon*](https://www.jmlr.org/papers/volume23/21-0716/21-0716.pdf)

<a name="equivariance" />

#### Invariance and Equivariance

* [**How we know universals** (1947)  <br /> *Walter Pitts & Warren S. McCulloch*](https://link.springer.com/content/pdf/10.1007/BF02478291.pdf) 


<a name="disentangling" />

#### Disentangling


* [**Addressing the Topological Defects of Disentanglement via Distributed Operators** (2021)  <br /> *Diane Bouchacourt, Mark Ibrahim, Stéphane Deny*](https://arxiv.org/abs/2102.05623v1) 

