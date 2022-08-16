# Symmetry and Geometry in Neural Representations

[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)](https://github.com/neurreps/reading-list/pulls) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Stars](https://img.shields.io/github/stars/neurreps/reading-list?color=yellow)  ![Forks](https://img.shields.io/github/forks/neurreps/reading-list?color=blue&label=Fork)

A curated collection of resources and research related to the geometry of representations in the brain, deep networks, and beyond, collaboratively generated on the [Symmetry and Geometry in Neural Representations](https://www.neurreps.org) Slack Workspace.

This is a collaborative work-in-progress. Please contribute via PRs!

[Join us on Slack!](https://communityinviter.com/apps/neurreps/join)


![](https://lh4.googleusercontent.com/vODs2cK98sKA9SVu_K2s-y8RFVmAXR8xEi4yGb6JBGBH73oFnpnhQSgb3C2qt2jFLLys2NY86l6lrPsFx2RpvV-Oqkqdf_TknI0ujQYyTeU2vCbaTgztq6xD-rhp4TJxGg=w1280)



## Contents


- [**Educational Resources**](#resources)
  - [Differential Geometry + Lie Groups](#diffgeo)
  - [Algebra](#algebra)
  - [Topology](#topology)
  - [Geometric Deep Learning](#gdl)
  - [Computational Neuroscience](#neuro-resources)
- [**Software Libraries**](#software)
- [**Conferences and Workshops**](#conferences)
- [**Research Papers**](#research)
  - [Perspectives](#perspectives)
  - [Neuroscience](#neuro) 
    - [Vision](#vision)
    - [Spatial Navigation](#navigation)
    - [Abstract Representations](#abstract)
    - [Methods](#methods)
  - [Geometric Deep Larning](#gdl)
    - [Theory](#theory)
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
* [**Discrete Differential Geometry** <br /> CMU](https://www.youtube.com/playlist?list=PL9_jI1bdZmz0hIrNCMQW1YmZysAiIYSSS)
* [**What is a Manifold?** <br /> *XylyXylyX*](https://youtube.com/playlist?list=PLRlVmXqzHjUQHEx63ZFxV-0Ortgf-rpJo)
* [**Lie Groups and Lie Algebras** <br /> *XylyXylyX*](https://youtube.com/playlist?list=PLRlVmXqzHjURZO0fviJuyikvKlGS6rXrb)
* [**Lectures on Geometric Anatomy of Theoretical Physics** <br /> Frederic Schuller](https://youtube.com/playlist?list=PLPH7f_7ZlzxTi6kS4vCmv4ZKm9u8g5yic)
* [**Weekend with Bernie (Riemann)** <br /> Søren Hauberg @ DTU](http://www2.compute.dtu.dk/~sohau/weekendwithbernie/)


#### Notebooks and Blogposts
* [**Introduction to Differential Geometry and Machine Learning** <br /> *Geomstats Jupyter notebooks*](https://github.com/geomstats/geomstats/tree/master/notebooks)
* [**Differential Geometry for Machine Learning** <br /> *Roger Grosse*](https://metacademy.org/roadmaps/rgrosse/dgml)



<br />

### Algebra

#### Textbooks
* [**Tensors in Computations** (2021) <br /> *Lek-Heng Lim*](https://arxiv.org/pdf/2106.08090.pdf)
* [**Aspects of Harmonic Analysis and Representation Theory** (2021) <br /> *Gallier & Quaintance*](https://drive.google.com/file/d/1eK8B1UpTJTnCXV6DL4-blDaKo6XQk28r/view?usp=sharing)
* [**Representation Theory of Finite Groups** (2012) <br /> *Bemjamin Steinberg*](https://drive.google.com/file/d/1fe1qnVAkCHEY1hn9sOvcA6Ocww66fMmP/view?usp=sharing)

#### Courses, Lectures, and Videos
* [**What is a Tensor?** <br /> *XylyXylyX*](https://youtube.com/playlist?list=PLRlVmXqzHjUQARA37r4Qw3SHPqVXgqO6c)
* [**Representation Theory** <br /> *Math Doctor Bob*](https://youtube.com/playlist?list=PL57457844458A5A1F)


<br />


### Topology

#### Courses, Lectures, and Videos
* [**Computational Algebraic Topology** <br /> Vidit Nanda](https://youtube.com/playlist?list=PLnLAqsCN_2ke8_EUd_KoJsLkPO0BKrrc6)

<br />


<a name="gdl" />


### Geometric Deep Learning

#### Textbooks

* [**Geometric Deep Learning: Grids, Groups, Graphs, Geodesics, and Gauges** (2021) <br /> _Michael M. Bronstein, Joan Bruna, Taco Cohen, Petar Veličković_](https://arxiv.org/abs/2104.13478)
* [**Group Theoretical Methods in Machine Learning** (2008) <br /> *Risi Kondor, PhD Thesis*](http://www.cs.columbia.edu/~jebara/papers/thesisKondor.pdf)
* [**Equivariant Convolutional Networks** (2021) <br /> *Taco Cohen, PhD Thesis*](https://pure.uva.nl/ws/files/60770359/Thesis.pdf)

#### Courses, Lectures, and Videos

* [**Geometric Deep Learning** (2nd Edition) <br />  *Michael Bronstein, Joan Bruna, Taco Cohen, Petar Veličković @ AMMI*](https://www.youtube.com/watch?v=5c_-KX1sRDQ&list=PLn2-dEmQeTfSLXW8yXP4q_Ii58wFdxb3C)

* [**An Introduction to Group-Equivariant Deep Learning** (2022) <br /> *Erik Bekkers @ UvA*](https://uvadl2c.github.io/)

* [**Italian Summer School on Geometric Deep Learning** (2022) <br /> *Cristian Bodnar, Michael Bronstein, Francesco Di Giovanni, Pim de Haan, Maurice Weiler*](https://www.youtube.com/playlist?list=PLn2-dEmQeTfRQXLKf9Fmlk3HmReGg3YZZ)

* [**COMP760: Geometry and Generative Models** (2022) <br /> *Joey Bose and Prakash Panangaden @ MILA*](https://joeybose.github.io/Blog/GenCourse)

#### Notebooks and Blogposts
* [**Geometric foundations of Deep Learning** <br /> *Michael Bronstein, Joan Bruna, Taco Cohen, and Petar Veličković*](https://towardsdatascience.com/geometric-foundations-of-deep-learning-94cdd45b451d)
* [**What does 2022 hold for Geometric & Graph ML?** <br /> *Michael Bronstein*](https://towardsdatascience.com/predictions-and-hopes-for-geometric-graph-ml-in-2022-aa3b8b79f5cc)

<br />

<a name="neuro-resources" />

### Computational Neuroscience

#### Textbooks
* [**Introduction to the Theory of Neural Computation** (1991) <br /> *John Hertz, Anders Krogh, Richard G Palmer*](https://drive.google.com/file/d/1jjAHNSZld1tjH0wiqXc9wCv3Y6h5sjok/view?usp=sharing)
* [**Theoretical Neuroscience** (2001) <br /> *Peter Dayan*](http://www.gatsby.ucl.ac.uk/~lmate/biblio/dayanabbott.pdf)
* [**Dynamical Systems in Neuroscience: The Geometry of Excitability and Bursting** (2006) <br /> *Eugene M. Izhikevich*](https://drive.google.com/file/d/1CXQCPl6MN8XSmoyo6J0TbdlWhBmaib62/view?usp=sharing)
* [**Principles of Neural Design** (2015) <br /> *Peter Sterling & Simon Laughlin*](https://drive.google.com/file/d/1cskdlUJBjAY5wH7GeZa2IxT9iSXZ_3_0/view?usp=sharing)

#### Books - General Audience
* [**Rythyms of the Brain** (2006) <br /> *Gyorgy Buzsaki*](https://drive.google.com/file/d/1DtGEb54qJNS2wkny1FXM4b_dfT-b140y/view?usp=sharing)
* [**Networks of the Brain** (2010) <br /> *Olaf Sporns*](https://drive.google.com/file/d/1MsGNsFVF7AxPtnyv1WnH-YnZMGvhUkHb/view?usp=sharing)

#### Courses, Lectures, and Videos
* [**Neural Computation VS265** <br /> *Bruno Olshausen @ UC Berkeley*](https://redwood.berkeley.edu/courses/vs265/)

#### Open-Source Dataset Repositories
* [**OpenNeuro**](https://openneuro.org/)
* [**NeuroVault**](https://neurovault.org/)
* [**CRCNS**](https://crcns.org/data-sets)
* [**NeuroData Without Borders**](https://www.nwb.org/example-datasets/)
* [**Allen Brain Atlas**](https://portal.brain-map.org/)
* [**Kavli Institute for Systems Neuroscience Grid Cell Database**](https://www.ntnu.edu/kavli/research/grid-cell-data)
* [**The Natural Scenes Dataset**](http://naturalscenesdataset.org/)
  * Whole-brain fMRI data from 8 humans viewing thousands of natural scenes in color
* [**Open Neuroscience**](https://open-neuroscience.com/)
  * Database of open-source tools and software for neuroscience

<br /><br />

<a name="software" />

# Software Libraries


* [**Geomstats**](https://geomstats.github.io/)
  * Computation, statistics, and machine learning on non-Euclidean manifolds
* [**Giotto TDA**](https://giotto-ai.github.io/gtda-docs/0.5.1/library.html)
  * Topological Data Analysis
* [**E3NN**](https://github.com/e3nn/e3nn)
  * E(3)-equivariant neural networks
* [**equivariant-MLP**](https://github.com/mfinzi/equivariant-MLP)
  * Construct equivariant multilayer perceptrons for arbitrary matrix groups
* [**SHTOOLS**](https://github.com/SHTOOLS/SHTOOLS)
  * Python library for computations involving spherical harmoics
* [**LieConv**](https://github.com/mfinzi/LieConv)
  * Generalizing convolutional neural networks for equivariance to Lie groups on arbitrary continuous data



<br /><br />

<a name="conferences" />

# Conferences and Workshops

* [**NeurIPS Workshop on Symmetry and Geometry in Neural Representations (2022)**](https://neurreps.org)
* [**ICML Workshop on Topology, Algebra and Geometry in Machine Learning (2022)**](https://www.tagds.com/events/conferences/tag-in-machine-learning)
* [**ICLR Workshop on Geometrical and Topological Representation Learning (2022)**](https://gt-rl.github.io/)

<br /><br />


<a name="research" />

# Research Papers

**Math Tags**

<img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />
<img src="https://img.shields.io/badge/-groups-DCEDC2" />
<img src="https://img.shields.io/badge/-topology-FFD3B5" />
<img src="https://img.shields.io/badge/-graphs-FFAAA6"" />

<br />


<a name="perspectives" />

### Perspectives

* [**Symmetry-based representations for artificial and biological general intelligence** (2022)  <br /> *Irina Higgins, Sébastien Racanière, Danilo Rezende.* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://www.frontiersin.org/articles/10.3389/fncom.2022.836498/full)


<br />

<a name="neuro" />

### Neuroscience

<a name="vision" />

#### Vision

* [**The Lie algebra of visual perception** (1966)  <br /> *William C.Hoffman*  <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://www.sciencedirect.com/science/article/abs/pii/0022249666900058) 

* [**Representation of local geometry in the visual system** (1987)  <br /> *Jan Koenderink*](https://link.springer.com/article/10.1007/BF00318371) 

* [**Operational Significance of Receptive Fields Assemblies** (1989)  <br /> *Jan Koenderink*](https://link.springer.com/content/pdf/10.1007/BF00364136.pdf) 

* [**The Visual Cortex is a Contact Bundle** (1989)  <br /> *William C. Hoffman*  <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />](http://www.its.caltech.edu/~matilde/VisualCortexContactBundle.pdf) 

* [**Geometric visual hallucinations, Euclidean symmetry and the functional architecture of striate cortex** (2001)  <br /> *Paul C. Bressloff, Jack D. Cowan, Martin Golubitsky, Peter J. Thomas and Matthew C. Wiener*](https://royalsocietypublishing.org/doi/10.1098/rstb.2000.0769) 

* [**The neurogeometry of pinwheels as a sub-Riemannian contact structure** (2003)  <br /> *Jean Petitot* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />](https://www.sciencedirect.com/science/article/abs/pii/S092842570300072X?casa_token=0mRpfL4cgoQAAAAA:qqV8dNcjLcg7xS1XScDlk20agI3Aa0d_vzvihKM5seCNU-PVuMzTEiI8xaAeTJH5QATLFFo) 

* [**Parsimony, Exhaustivity and Balanced Detection in Neocortex** (2015)  <br /> *Alberto Romagnoni, Jérôme Ribot, Daniel Bennequin, Jonathan Touboul*](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004623) 

* [**Predicting the retinotopic organization of human visual cortex from anatomy using geometric deep learning** (2021)  <br /> *Fernanda L. Ribeiro, Steffen Bollmann, Alexander M. Puckett*](https://www.sciencedirect.com/science/article/pii/S1053811921008971)

* [**Primary visual cortex straightens natural video trajectories** (2021)  <br /> *Olivier J. Hénaff, Yoon Bai, Julie A. Charlton, Ian Nauhaus, Eero P. Simoncelli & Robbe L. T. Goris*](https://www.nature.com/articles/s41467-021-25939-z) 


<a name="navigation" />

#### Spatial Navigation

* [**The intrinsic attractor manifold and population dynamics of a canonical cognitive circuit across waking and sleep** (2019)  <br /> *Rishidev Chaudhuri, Berk Gerçek, Biraj Pandey, Adrien Peyrache & Ila Fiete* <br /> <img src="https://img.shields.io/badge/-topology-FFD3B5" />
](https://www.nature.com/articles/s41593-019-0460-x) 


* [**Toroidal topology of population activity in grid cells** (2022)  <br /> *Richard J. Gardner, Erik Hermansen, Marius Pachitariu, Yoram Burak, Nils A. Baas, Benjamin A. Dunn, May-Britt Moser & Edvard I. Moser* <br /> <img src="https://img.shields.io/badge/-topology-FFD3B5" />](https://www.nature.com/articles/s41586-021-04268-7) 

<a name="abstract" />

#### Abstract Representations

* [**The Geometry of Abstraction in the Hippocampus and Prefrontal Cortex** (2020) <br /> *Silvia Bernardi, Marcus K.Benna, Matti Rigotti, Jérôme Munuera, Stefano Fusi, Daniel Salzman*](https://www.sciencedirect.com/science/article/pii/S0092867420312289) 


<a name="methods" />

#### Methods

* [**Interpreting neural computations by examining intrinsic and embedding dimensionality of neural activity** (2021) <br /> *Mehrdad Jazayeri, Srdjan Ostojic*](https://arxiv.org/abs/2107.04084) 

<br />

<a name="gdl" />

### Geometric Deep Learning

<a name="theory" />

#### Theory
* [**The Riemannian Geometry of Deep Generative Models** (2018) <br /> *Hang Shao, Abhishek Kumar, P. Thomas Fletcher* <br /> <img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />](https://drive.google.com/file/d/1Nxq-lLG1txHy6cYjOM3fMM3D5yIZx6hd/view?usp=sharing)
* [**Universal Approximation Theorems for Differentiable Geometric Deep Learning** (2022)  <br /> *Anastasis Kratsios, L´eonie Papon* <br /> <img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />
](https://www.jmlr.org/papers/volume23/21-0716/21-0716.pdf)

<a name="equivariance" />

#### Invariance and Equivariance

* [**How we know universals** (1947)  <br /> *Walter Pitts & Warren S. McCulloch* <br /><img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://link.springer.com/content/pdf/10.1007/BF02478291.pdf) 
* [**Learning Symmetry Groups with Hidden Units: Beyond the Perceptron** (1986) <br /> *Terrence Sejnowski, Paul K. Kienker, Geoffrey Hinton* <br /><img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://drive.google.com/file/d/1P3QhDIw9vTgYUA-cTMDlRAoXOgpsPQom/view?usp=sharing)
* [**Learning Lie groups for invariant visual perception** (1999) <br /> *Rajesh Rao, Daniel Ruderman* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://proceedings.neurips.cc/paper/1998/file/277281aada22045c03945dcb2ca6f2ec-Paper.pdf)
* [**Learning the Lie groups of visual invariance** (2007) <br /> *Xu Miao, Rajesh Rao* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://direct.mit.edu/neco/article-abstract/19/10/2665/7221/Learning-the-Lie-Groups-of-Visual-Invariance)
* [**An unsupervised algorithm for learning Lie group transformations.** (2010) <br /> Jascha Sohl-Dickstein, Ching Ming Wang, Bruno Olshausen <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://arxiv.org/pdf/1001.1027.pdf)
* [**Learning the irreducible representations of commutative Lie groups** (2014) <br /> *Taco Cohen & Max Welling* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](http://proceedings.mlr.press/v32/cohen14.pdf)
* [**Group equivariant convolutional networks** (2016) <br /> *Taco Cohen & Max Welling* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://drive.google.com/file/d/10JqJrqRysF3c4_ruLe8ad0ijFdVlpjdp/view?usp=sharing)

* [**Spherical CNNs** (2018) <br /> *Taco Cohen, Mario Geiger, Jonas Kohler, & Max Welling* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://drive.google.com/file/d/186hhjJl_fQwEM9_lWpU6Dvac-S1ZTa3A/view?usp=sharing)

* [**Hyperspherical Variational Auto-Encoders** (2018) <br /> *Tim R. Davidson, Luca Falorsi, Nicola De Cao, Thomas Kipf, Jakub M. Tomczak* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://drive.google.com/file/d/1tGGqozCte2XmdzIETYu33LFSGgMvK774/view?usp=sharing)
* [**Clebsch–gordan nets: a fully fourier space spherical convolutional neural network** (2018) <br /> *Risi Kondor, Zhen Lin, Shubhendu Trivedi* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://drive.google.com/file/d/1-NuvFpo0VkY-NDbt89oGDroz23yQ9nhL/view?usp=sharing)
* [**Tensor field networks: Rotation-and translation-equivariant neural networks for 3d point clouds** (2018) <br /> *Nathaniel Thomas, Tess Smidt, Steven Kearnes, Lusann Yang, Li Li, Kai Kohlhoff, Patrick Riley* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://drive.google.com/file/d/1nwbEb9FIJ04aSX40BIZtAxH5ujTQ7Lfv/view?usp=sharing)

* [**A General Theory of Equivariant CNNs on Homogeneous Spaces** (2019)<br /> *Taco Cohen, Mario Geiger, & Maurice Weiler* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://drive.google.com/file/d/1Vd6ID_HsY9PTHFqCEmPv4iTDlLsoBqVr/view?usp=sharing)

* [**Generalizing convolutional neural networks for equivariance to Lie groups on arbitrary continuous data** (2020) <br /> *Marc Finzi, Samuel Stanton, Pavel Izmailov, Andrew Gordon Wilson* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://drive.google.com/file/d/1Xzvq2s7Oj3XXftHFcvrI5IhZklS7tt7L/view?usp=sharing)

<a name="disentangling" />

#### Disentangling


* [**Addressing the Topological Defects of Disentanglement via Distributed Operators** (2021)  <br /> *Diane Bouchacourt, Mark Ibrahim, Stéphane Deny* <br /> <img src="https://img.shields.io/badge/-topology-FFD3B5" />
](https://arxiv.org/abs/2102.05623v1) 

