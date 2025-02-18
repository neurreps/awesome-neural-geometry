# Awesome Neural Geometry

[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)](https://github.com/neurreps/reading-list/pulls) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Stars](https://img.shields.io/github/stars/neurreps/reading-list?color=yellow)  ![Forks](https://img.shields.io/github/forks/neurreps/reading-list?color=blue&label=Fork)

A curated collection of resources and research related to the geometry of representations in the brain, deep networks, and beyond, collaboratively generated on the [Symmetry and Geometry in Neural Representations](https://www.neurreps.org) Slack Workspace.

This is a collaborative work-in-progress. Please contribute via PRs!

[Join us on Slack!](https://communityinviter.com/apps/neurreps/join)


![](https://lh4.googleusercontent.com/vODs2cK98sKA9SVu_K2s-y8RFVmAXR8xEi4yGb6JBGBH73oFnpnhQSgb3C2qt2jFLLys2NY86l6lrPsFx2RpvV-Oqkqdf_TknI0ujQYyTeU2vCbaTgztq6xD-rhp4TJxGg=w1280)



## Contents


- [**Educational Resources**](#resources)
  - [Abstract Algebra + Group Theory](#grouptheory)
  - [Differential Geometry + Lie Groups](#diffgeo)
  - [Information Geometry](#infogeo)
  - [Topology](#topology)
  - [Geometric Machine Learning](#gdl)
  - [Computational Neuroscience](#neuro-resources)
- [**Datasets**](#datasets)
- [**Software Libraries**](#software)
- [**Conferences and Workshops**](#conferences)



<br /><br />

<a name="resources" />

# Educational Resources

<a name="grouptheory" />

### Abstract Algebra + Group Theory

#### Textbooks & Notes
* [**Group Theory: A Primer** (2019) <br /> *Luciano da Fontoura Costa*](https://www.researchgate.net/profile/Luciano-Da-F-Costa/publication/334126746_Group_Theory_A_Primer_CDT-11/links/5da83b2f299bf1c1e4c8ffb4/Group-Theory-A-Primer-CDT-11.pdf)
* [**Tensors in Computations** (2021) <br /> *Lek-Heng Lim*](https://arxiv.org/pdf/2106.08090.pdf)
* [**Aspects of Harmonic Analysis and Representation Theory** (2021) <br /> *Gallier & Quaintance*](https://drive.google.com/file/d/1eK8B1UpTJTnCXV6DL4-blDaKo6XQk28r/view?usp=sharing)
* [**Basic concepts of representation theory** (2013) <br /> *Amritanshu Prasad*](https://cel.archives-ouvertes.fr/cel-00963677/document)
* [**Representation Theory of Finite Groups** (2012) <br /> *Bemjamin Steinberg*](https://drive.google.com/file/d/1fe1qnVAkCHEY1hn9sOvcA6Ocww66fMmP/view?usp=sharing)

#### Courses, Lectures, and Videos
* [**Essence of Group Theory**  **Beginner-Friendly* <br /> *Mathemaniac*](https://youtube.com/playlist?list=PLDcSwjT2BF_VuNbn8HiHZKKy59SgnIAeO)
* [**Abstract Algebra** **Beginner-Friendly* <br /> *Socratica*](https://youtube.com/playlist?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)
* [**Euler's formula with introductory group theory** **Intuition Building* <br /> *3blue1brown*](https://www.youtube.com/watch?v=mvmuCPvRoWQ&t=648s&ab_channel=3Blue1Brown)
* [**What is a Tensor?** <br /> *XylyXylyX*](https://youtube.com/playlist?list=PLRlVmXqzHjUQARA37r4Qw3SHPqVXgqO6c)
* [**Representation Theory** <br /> *Math Doctor Bob*](https://youtube.com/playlist?list=PL57457844458A5A1F)
* [**Category Theory for AI** <br /> *Online Course, October 2022*](https://cats.for.ai/)

<br />


<a name="diffgeo" />

### Differential Geometry + Lie Groups

#### Textbooks & Notes
* [**Lie Groups, Lie Algebras, and Representations** (2003) <br /> *Brian C. Hall*](https://link.springer.com/book/10.1007/978-3-319-13467-3)
* [**Differential Geometry and Lie Groups: A Computational Perspective** (2020) <br /> *Gallier & Quaintance*](https://link.springer.com/book/10.1007/978-3-030-46040-2)
* [**Introduction to Riemannian Geometry and Geometric Statistics: from basic theory to implementation with Geomstats** (2022) <br /> *Nicolas Guigui, Nina Miolane, Xavier Pannec*](https://hal.inria.fr/hal-03766900/)

#### Courses, Lectures, and Videos
* [**Geometry and Topology**](https://youtu.be/kp1k90zNVLc) and [**Symmetry**](https://youtu.be/yCxacFBLHIY) **Beginner-Friendly* <br /> *Sean Carroll*
* [**Differential Geometry for Computer Science** <br /> *Justin Solomon*](https://youtube.com/playlist?list=PLQ3UicqQtfNvPmZftPyQ-qK1wdXBxj86W)
* [**Discrete Differential Geometry** <br /> CMU](https://www.youtube.com/playlist?list=PL9_jI1bdZmz0hIrNCMQW1YmZysAiIYSSS)
* [**What is a Manifold?** <br /> *XylyXylyX*](https://youtube.com/playlist?list=PLRlVmXqzHjUQHEx63ZFxV-0Ortgf-rpJo)
* [**Manifolds** <br /> *Robert Davie*](https://youtube.com/playlist?list=PLeFwDGOexoe8cjplxwQFMvGLSxbOTUyLv)
* [**Lie Groups and Lie Algebras** <br /> *XylyXylyX*](https://youtube.com/playlist?list=PLRlVmXqzHjURZO0fviJuyikvKlGS6rXrb)
* [**Lectures on Geometric Anatomy of Theoretical Physics** <br /> *Frederic Schuller*](https://youtube.com/playlist?list=PLPH7f_7ZlzxTi6kS4vCmv4ZKm9u8g5yic)
* [**Weekend with Bernie (Riemann)** <br /> *Søren Hauberg @ DTU*](http://www2.compute.dtu.dk/~sohau/weekendwithbernie/)
* [**Riemann and Gauss Meet Asimov: A Tutorial on Geometric Methods in Robot Learning, Optimization, and Control** <br /> *IROS 2022*](https://youtube.com/playlist?list=PL_oEZ6dld4ignAdbFvcP_LAJgNbdrNBKC)

#### Notebooks and Blogposts
* [**Introduction to Differential Geometry and Machine Learning** <br /> *Geomstats Jupyter notebooks*](https://github.com/geomstats/geomstats/tree/master/notebooks)
* [**Differential Geometry for Machine Learning** <br /> *Roger Grosse*](https://metacademy.org/roadmaps/rgrosse/dgml)
* [**Manifolds: A Gentle Introduction** <br /> *Brian Keng*](https://bjlkeng.github.io/posts/manifolds/)




<br />

<a name="infogeo" />

### Information Geometry

#### Primers
* [**The Many Faces of Information Geometry** (2022) <br /> *Frank Nielsen*](https://www.ams.org/journals/notices/202201/rnoti-p36.pdf)

<br />


### Topology

#### Courses, Lectures, and Videos

* [**Computational Algebraic Topology** <br /> Vidit Nanda](https://youtube.com/playlist?list=PLnLAqsCN_2ke8_EUd_KoJsLkPO0BKrrc6)

* [**Topological Data Analysis for Machine Learning** <br /> Bastian Rieck](https://www.youtube.com/playlist?list=PLjFHG9gPsecYteKmbVbPhjiz2jHRtKT20)

#### Textbooks, Notes
* [**Elementary Applied Topology** <br /> Robert Ghrist](https://www2.math.upenn.edu/~ghrist/notes.html)
<br />


<a name="gdl" />


### Geometric Machine Learning

#### Textbooks

* [**Group Invariance Applications in Statistics** (1989) <br /> Morris Eaton](https://www.jstor.org/stable/4153172)
* [**Group Theoretical Methods in Machine Learning** (2008) <br /> *Risi Kondor, PhD Thesis*](http://www.cs.columbia.edu/~jebara/papers/thesisKondor.pdf)
* [**Pattern Theory: The Stochastic Analysis of Real-World Signals** (2010) <br /> *David Mumford and Agnès Desolneux*](https://www.routledge.com/Pattern-Theory-The-Stochastic-Analysis-of-Real-World-Signals/Mumford-Desolneux/p/book/9781568815794)
* [**Geometric Deep Learning: Grids, Groups, Graphs, Geodesics, and Gauges** (2021) <br /> _Michael M. Bronstein, Joan Bruna, Taco Cohen, Petar Veličković_](https://arxiv.org/abs/2104.13478)
* [**Equivariant Convolutional Networks** (2021) <br /> *Taco Cohen, PhD Thesis*](https://pure.uva.nl/ws/files/60770359/Thesis.pdf)
* [**An Introduction to Optimization on Smooth Manifolds** (2022) <br /> *Nicolas Boumal*](https://sma.epfl.ch/~nboumal/book/IntroOptimManifolds_Boumal_2022.pdf)

#### Courses, Lectures, and Videos

* [**Geometric Deep Learning** (2nd Edition) <br />  *Michael Bronstein, Joan Bruna, Taco Cohen, Petar Veličković @ AMMI*](https://www.youtube.com/watch?v=5c_-KX1sRDQ&list=PLn2-dEmQeTfSLXW8yXP4q_Ii58wFdxb3C)
* [**CSC 2547: Current Topics in Machine Learning Methods in 3D and Geometric Deep Learning** (2021) <br /> *Animesh Garg @ University of Toronto*](https://youtube.com/playlist?list=PLki3HkfgNEsLrbI_r2iqNogmL5DW6HJXF)
* [**An Introduction to Group-Equivariant Deep Learning** (2022) <br /> *Erik Bekkers @ UvA*](https://www.youtube.com/playlist?list=PL8FnQMH2k7jzPrxqdYufoiYVHim8PyZWd)
* [**Italian Summer School on Geometric Deep Learning** (2022) <br /> *Cristian Bodnar, Michael Bronstein, Francesco Di Giovanni, Pim de Haan, Maurice Weiler*](https://www.youtube.com/playlist?list=PLn2-dEmQeTfRQXLKf9Fmlk3HmReGg3YZZ)
* [**COMP760: Geometry and Generative Models** (2022) <br /> *Joey Bose and Prakash Panangaden @ MILA*](https://joeybose.github.io/Blog/GenCourse)


#### Notebooks and Blogposts
* [**Geometric foundations of Deep Learning** <br /> *Michael Bronstein, Joan Bruna, Taco Cohen, and Petar Veličković*](https://towardsdatascience.com/geometric-foundations-of-deep-learning-94cdd45b451d)
* [**What does 2022 hold for Geometric & Graph ML?** <br /> *Michael Bronstein*](https://towardsdatascience.com/predictions-and-hopes-for-geometric-graph-ml-in-2022-aa3b8b79f5cc)
* [**Geometric Machine Learning for Shape Analysis with Jupyter Notebooks** <br /> *Nina Miolane*](https://github.com/bioshape-lab/ece594n/tree/main/lectures)

<br />

<a name="neuro-resources" />

### Computational Neuroscience

#### Textbooks
* [**Introduction to the Theory of Neural Computation** (1991) <br /> *John Hertz, Anders Krogh, Richard G Palmer*](https://drive.google.com/file/d/1jjAHNSZld1tjH0wiqXc9wCv3Y6h5sjok/view?usp=sharing)
* [**Theoretical Neuroscience** (2001) <br /> *Peter Dayan*](http://www.gatsby.ucl.ac.uk/~lmate/biblio/dayanabbott.pdf)
* [**Dynamical Systems in Neuroscience: The Geometry of Excitability and Bursting** (2006) <br /> *Eugene M. Izhikevich*](https://drive.google.com/file/d/1CXQCPl6MN8XSmoyo6J0TbdlWhBmaib62/view?usp=sharing)
* [**Neuronal Dynamics: From single neurons to networks and models of cognition** (2014) <br /> *Wulfram Gerstner, Werner M. Kistler, Richard Naud and Liam Paninsky*](https://neuronaldynamics.epfl.ch/)
* [**Principles of Neural Design** (2015) <br /> *Peter Sterling & Simon Laughlin*](https://drive.google.com/file/d/1cskdlUJBjAY5wH7GeZa2IxT9iSXZ_3_0/view?usp=sharing)


#### Books - General Audience
* [**Rhythms of the Brain** (2006) <br /> *Gyorgy Buzsaki*](https://drive.google.com/file/d/1DtGEb54qJNS2wkny1FXM4b_dfT-b140y/view?usp=sharing)
* [**Networks of the Brain** (2010) <br /> *Olaf Sporns*](https://drive.google.com/file/d/1MsGNsFVF7AxPtnyv1WnH-YnZMGvhUkHb/view?usp=sharing)
* [**Models of the Mind: How Physics, Engineering and Mathematics Have Shaped Our Understanding of the Brain** (2021) <br /> *Grace Lindsay*](https://www.goodreads.com/en/book/show/50884536-models-of-the-mind)

#### Tutorials
* [**Generative Models for Neural Data Analysis** <br /> *COSYNE Workshops 2023*](https://github.com/davindicode/cosyne-2023-generative-models)

#### Courses, Lectures, and Videos
* [**Neural Computation VS265** <br /> *Bruno Olshausen @ UC Berkeley*](https://redwood.berkeley.edu/courses/vs265/)


<br /><br />

<a name="datasets" />

# Datasets

### Open-Source Neuroscience Datasets
* [**OpenNeuro**](https://openneuro.org/)
* [**NeuroVault**](https://neurovault.org/)
* [**CRCNS**](https://crcns.org/data-sets)
* [**NeuroData Without Borders**](https://www.nwb.org/example-datasets/)
* [**Allen Brain Atlas**](https://portal.brain-map.org/)
* [**Kavli Institute for Systems Neuroscience Grid Cell Database**](https://www.ntnu.edu/kavli/research/grid-cell-data)
* [**The Natural Scenes Dataset**](http://naturalscenesdataset.org/)

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
  * Python library for computations involving spherical harmonics
* [**LieConv**](https://github.com/mfinzi/LieConv)
  * Generalizing convolutional neural networks for equivariance to Lie groups on arbitrary continuous data
* [**Open Neuroscience**](https://open-neuroscience.com/)
  * A database of open-source tools and software for neuroscience
* [**LieTorch**](https://gitlab.com/bsmetsjr/lietorch)
  * Geometric machine learning and Lie analysis tools for PyTorch
* [**pyRiemann**](https://github.com/pyRiemann/pyRiemann)
  * Machine learning for multivariate data through the Riemannian geometry of positive definite matrices



<br /><br />

<a name="conferences" />

# Conferences and Workshops

* [**NeurIPS Workshop on Symmetry and Geometry in Neural Representations** (2023)](https://neurreps.org)
* [**ICML Workshop on Topology, Algebra and Geometry in Machine Learning** (2023)](https://www.tagds.com/events/conference-workshops/tag-ml23)
* [**RSS Workshop on Symmetries in Robot Learning** (2023)](https://sites.google.com/view/rss23-sym)
* [**NeurIPS Workshop on Symmetry and Geometry in Neural Representations** (2022)](https://www.neurreps.org/past-workshops)
* [**ICML Workshop on Topology, Algebra and Geometry in Machine Learning** (2022)](https://www.tagds.com/events/conference-workshops/tag-ml22)
* [**ICLR Workshop on Geometrical and Topological Representation Learning** (2022)](https://gt-rl.github.io/)
* [**Workshop on Symmetry, Invariance and Neural Representations @ The Bernstein Conference** (2022)](https://bernstein-network.de/bernstein-conference/program/satellite-workshops/symmetry-invariance-and-neural-representations/)

