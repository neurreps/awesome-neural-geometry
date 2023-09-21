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
- [**Research Papers**](#research)
  - [Neuroscience](#neuro)
    - [Theory and Perspectives](#theory)
    - [Vision](#vision)
    - [Motor Control](#motor)
    - [Spatial Navigation](#navigation)
    - [Abstract Representations](#abstract)
    - [Methods](#methods)
  - [Geometric Machine Learning](#gdl)
    - [Theory](#theory)
    - [Estimation on Manifolds](#estimation)
    - [Dimensionality Reduction and Disentangling](#disentangling)
    - [Deep Network Interpretability](#interpretability)
    - [Group-Invariant Representation Learning](#invariance)
    - [Generalized Convolutional Neural Networks](#convolution)



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



<br /><br />

<a name="conferences" />

# Conferences and Workshops

* [**NeurIPS Workshop on Symmetry and Geometry in Neural Representations** (2022)](https://neurreps.org)
* [**ICML Workshop on Topology, Algebra and Geometry in Machine Learning** (2022)](https://www.tagds.com/events/conferences/tag-in-machine-learning)
* [**ICLR Workshop on Geometrical and Topological Representation Learning** (2022)](https://gt-rl.github.io/)
* [**Workshop on Symmetry, Invariance and Neural Representations @ The Bernstein Conference** (2022)](https://bernstein-network.de/bernstein-conference/program/satellite-workshops/symmetry-invariance-and-neural-representations/)

<br /><br />


<a name="research" />

# Research Papers

**Math Tags**

<img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />
<img src="https://img.shields.io/badge/-groups-DCEDC2" />
<img src="https://img.shields.io/badge/-topology-FFD3B5" />
<img src="https://img.shields.io/badge/-graphs-FFAAA6" />
<img src="https://img.shields.io/badge/-PDEs-blue" />


<br />

<a name="neuro" />

### Neuroscience

<a name="theory" />

#### Theory and Perspectives

* [**Brain graphs: graphical models of the human brain connectome.** (2011) <br /> *Edward T. Bullmore and Danielle S. Bassett* <br /><img src="https://img.shields.io/badge/-graphs-FFAAA6" /> <img src="https://img.shields.io/badge/-topology-FFD3B5" />](https://pubmed.ncbi.nlm.nih.gov/21128784/)
* [**What can topology tell us about the neural code?** (2017) <br /> *Carina Curto* <br /><img src="https://img.shields.io/badge/-topology-FFD3B5" />
](https://www.ams.org/journals/bull/2017-54-01/S0273-0979-2016-01554-0/S0273-0979-2016-01554-0.pdf)
* [**Network Neuroscience** (2017) <br /> *Danielle S. Bassett, and Olaf Sporns.* <br /><img src="https://img.shields.io/badge/-graphs-FFAAA6" /> <img src="https://img.shields.io/badge/-topology-FFD3B5" />](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5485642/)
* [**Navigating the neural space in search of the neural code.** (2017) <br /> *Jazayeri, M., & Afraz, A.*](https://www.sciencedirect.com/science/article/pii/S0896627317301034)
* [**A theory of multineuronal dimensionality, dynamics and measurement.** (2017) <br /> *Gao, P., Trautmann, E., Yu, B., Santhanam, G., Ryu, S., Shenoy, K., & Ganguli, S.*](https://www.biorxiv.org/content/biorxiv/early/2017/11/05/214262.full.pdf)
* [**Computation through neural population dynamics.** (2020) <br /> *Saurabh Vyas, Matthew D. Golub, David Sussillo, and Krishna V. Shenoy*](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7402639/)
* [**Neural population geometry: An approach for understanding biological and artificial neural networks.** (2021) <br /> *SueYeon Chung, and L. F. Abbott.*](https://www.sciencedirect.com/science/article/pii/S0959438821001227)
* [**Symmetry-based representations for artificial and biological general intelligence** (2022)  <br /> *Irina Higgins, Sébastien Racanière, Danilo Rezende.* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://www.frontiersin.org/articles/10.3389/fncom.2022.836498/full)


<a name="vision" />

#### Vision

* [**Mathematical analysis of binocular vision** (1947)  <br /> *Rudolf Karl Luneburg*  <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />](https://psycnet.apa.org/record/1948-00132-000)
* [**The Lie algebra of visual perception** (1966)  <br /> *William C.Hoffman*  <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://www.sciencedirect.com/science/article/abs/pii/0022249666900058)
* [**Representation of local geometry in the visual system** (1987)  <br /> *Jan Koenderink*](https://link.springer.com/article/10.1007/BF00318371)
* [**Operational Significance of Receptive Fields Assemblies** (1989)  <br /> *Jan Koenderink*](https://link.springer.com/content/pdf/10.1007/BF00364136.pdf)
* [**The Visual Cortex is a Contact Bundle** (1989)  <br /> *William C. Hoffman*  <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />](http://www.its.caltech.edu/~matilde/VisualCortexContactBundle.pdf)
* [**Geometric visual hallucinations, Euclidean symmetry and the functional architecture of striate cortex** (2001)  <br /> *Paul C. Bressloff, Jack D. Cowan, Martin Golubitsky, Peter J. Thomas and Matthew C. Wiener*](https://royalsocietypublishing.org/doi/10.1098/rstb.2000.0769)
* [**The neurogeometry of pinwheels as a sub-Riemannian contact structure** (2003)  <br /> *Jean Petitot* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />](https://www.sciencedirect.com/science/article/abs/pii/S092842570300072X?casa_token=0mRpfL4cgoQAAAAA:qqV8dNcjLcg7xS1XScDlk20agI3Aa0d_vzvihKM5seCNU-PVuMzTEiI8xaAeTJH5QATLFFo)
* [**Untangling invariant object recognition.** (2007) <br /> *James DiCarlo and David Cox*](https://www.sciencedirect.com/science/article/pii/S1364661307001593?casa_token=l3bhfMi1IegAAAAA:jBCwbfa7nMTOI4n7gAEijevBf4Op2fI2-kGmj0QYGYSscddxuehUoVQ-Wti8_UTd-YAS2z0)
* [**Parsimony, Exhaustivity and Balanced Detection in Neocortex** (2015)  <br /> *Alberto Romagnoni, Jérôme Ribot, Daniel Bennequin, Jonathan Touboul*](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004623)
* [**High-dimensional geometry of population responses in visual cortex.** (2019) <br /> *Stringer, Carsen, Marius Pachitariu, Nicholas Steinmetz, Matteo Carandini, and Kenneth D. Harris.*](https://www.nature.com/articles/s41586-019-1346-5)
* [**Evolving images for visual neurons using a deep generative network reveals coding principles and neuronal preferences.** (2019) <br /> *Carlos R. Ponce, Will Xiao, Peter F. Schade, Till S. Hartmann, Gabriel Kreiman, and Margaret S. Livingstone.*](https://www.sciencedirect.com/science/article/pii/S0092867419303915)
* [**Predicting the retinotopic organization of human visual cortex from anatomy using geometric deep learning** (2021)  <br /> *Fernanda L. Ribeiro, Steffen Bollmann, Alexander M. Puckett*](https://www.sciencedirect.com/science/article/pii/S1053811921008971)
* [**Primary visual cortex straightens natural video trajectories** (2021)  <br /> *Olivier J. Hénaff, Yoon Bai, Julie A. Charlton, Ian Nauhaus, Eero P. Simoncelli & Robbe L. T. Goris*](https://www.nature.com/articles/s41467-021-25939-z)
* [**Unsupervised deep learning identifies semantic disentanglement in single inferotemporal face patch neurons.** (2021) <br /> *Higgins, I., Chang, L., Langston, V., Hassabis, D., Summerfield, C., Tsao, D., & Botvinick, M.*](https://www.nature.com/articles/s41467-021-26751-5)


<a name="motor" />

#### Motor Control

* [**Neural manifolds for the control of movement** (2017) <br /> *Juan Gallego, Matthew Perich, Lee Miller, Sara Solla*](https://www.sciencedirect.com/science/article/pii/S0896627317304634)
* [**Accurate estimation of neural population dynamics without spike sorting.** (2019) <br /> *Eric M. Trautmann, Sergey D. Stavisky, Subhaneil Lahiri, Katherine C. Ames, Matthew T. Kaufman, Daniel J. O’Shea, Saurabh Vyas et al.*](https://www.sciencedirect.com/science/article/pii/S0896627319304283)


<a name="navigation" />

#### Spatial Navigation

* [**Ring attractor dynamics in the Drosophila central brain** (2017) <br /> *Sung Soo Kim, Hervé Rouault, Shaul Druckmann, and Vivek Jayaraman*](https://www.science.org/doi/full/10.1126/science.aal4835?casa_token=y5cbQEVl0BoAAAAA:4hvdRNzkyIx_IFjEugUZGDc_1dJprHduwRYUSbKZ7Ffh_oHBh6KIzPTvSDFELKZ_mW7Fw2in1ljKR4A)
* [**The intrinsic attractor manifold and population dynamics of a canonical cognitive circuit across waking and sleep** (2019)  <br /> *Rishidev Chaudhuri, Berk Gerçek, Biraj Pandey, Adrien Peyrache & Ila Fiete* <br /> <img src="https://img.shields.io/badge/-topology-FFD3B5" />
](https://www.nature.com/articles/s41593-019-0460-x)
* [**Toroidal topology of population activity in grid cells** (2022)  <br /> *Richard J. Gardner, Erik Hermansen, Marius Pachitariu, Yoram Burak, Nils A. Baas, Benjamin A. Dunn, May-Britt Moser & Edvard I. Moser* <br /> <img src="https://img.shields.io/badge/-topology-FFD3B5" />](https://www.nature.com/articles/s41586-021-04268-7)
* [**Hippocampal spatial representations exhibit a hyperbolic geometry that expands with experience** (2022)  <br /> *Huanqiu Zhang, P. Dylan Rich, Albert K. Lee & Tatyana O. Sharpee* <br /> <img src="https://img.shields.io/badge/-topology-FFD3B5" />](https://www.nature.com/articles/s41593-022-01212-4)

<a name="abstract" />

#### Abstract Representations

* [**The Geometry of Abstraction in the Hippocampus and Prefrontal Cortex** (2020) <br /> *Silvia Bernardi, Marcus K.Benna, Matti Rigotti, Jérôme Munuera, Stefano Fusi, Daniel Salzman*](https://www.sciencedirect.com/science/article/pii/S0092867420312289)
* [**Geometry of abstract learned knowledge in the hippocampus** (2021) <br /> Edward Nieh, et al.](https://www.nature.com/articles/s41586-021-03652-7)


<a name="methods" />

#### Methods
* [**Clique topology reveals intrinsic geometric structure in neural correlations.** (2015) <br /> *Chad Giusti, Eva Pastalkova, Carina Curto, and Vladimir Itskov* <br /><img src="https://img.shields.io/badge/-topology-FFD3B5" />](https://www.pnas.org/doi/full/10.1073/pnas.1506407112)
* [**Two’s company, three (or more) is a simplex.** (2016) <br /> *Chad Giusti, Robert Ghrist, and Danielle S. Bassett.* <br /><img src="https://img.shields.io/badge/-topology-FFD3B5" />](https://link.springer.com/article/10.1007/s10827-016-0608-6)
* [**Inferring single-trial neural population dynamics using sequential auto-encoders.** (2018) <br /> *Pandarinath, C., O’Shea, D. J., Collins, J., Jozefowicz, R., Stavisky, S. D., Kao, J. C., ... & Sussillo, D.*](https://www.nature.com/articles/s41592-018-0109-9)
* [**Manifold GPLVMs for discovering non-Euclidean latent structure in neural data** (2020) <br /> *Kristopher Jensen, Ta-Chu Kao, Marco Tripodi, and Guillaume Hennequin* <br /> <img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://proceedings.neurips.cc/paper/2020/file/fedc604da8b0f9af74b6cfc0fab2163c-Paper.pdf)
* [**Interpreting neural computations by examining intrinsic and embedding dimensionality of neural activity** (2021) <br /> *Mehrdad Jazayeri, Srdjan Ostojic*](https://arxiv.org/abs/2107.04084)
* [**Generalized shape metrics on neural representations.** (2021) <br /> *Williams, A. H., Kunz, E., Kornblith, S., & Linderman, S.* <br /> <img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />](https://proceedings.neurips.cc/paper/2021/file/252a3dbaeb32e7690242ad3b556e626b-Paper.pdf)
* [**Learnable latent embeddings for joint behavioural and neural analysis** (2023) <br /> *Schneider, S.*, Lee, J.H.*, Mathis, M.W.* <br />](https://www.nature.com/articles/s41586-023-06031-6)

<br />

<a name="gdl" />

### Geometric Machine Learning

<a name="theory" />

#### Theory
* [**On the Local Behavior of Spaces of Natural Images** (2006) <br /> *Gunnar Carlsson, Tigran Ishkhanov, Vin De Silva, and Afra Zomorodian* <br /><img src="https://img.shields.io/badge/-topology-FFD3B5" />](https://link.springer.com/content/pdf/10.1007/s11263-007-0056-x.pdf)
* [**The Riemannian Geometry of Deep Generative Models** (2018) <br /> *Hang Shao, Abhishek Kumar, P. Thomas Fletcher* <br /> <img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />](https://drive.google.com/file/d/1Nxq-lLG1txHy6cYjOM3fMM3D5yIZx6hd/view?usp=sharing)
* [**The Geometry of Deep Generative Image Models and its Applications** (2021) <br /> *Binxu Wang, Carlos R. Ponce* <br /> <img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />](https://arxiv.org/abs/2101.06006)
* [**Universal Approximation Theorems for Differentiable Geometric Deep Learning** (2022)  <br /> *Anastasis Kratsios, L´eonie Papon* <br /> <img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />
](https://www.jmlr.org/papers/volume23/21-0716/21-0716.pdf)
* [**A Statistical Manifold Framework for Point Cloud Data** (2022)  <br /> *Yonghyeon Lee, Seungyeon Kim, Jinwon Choi, Frank C. Park* <br /> <img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />
](https://drive.google.com/file/d/1SynnbbJH7NSP_TaYDwsSH5QMUJK1YzSA/view)

<a name="estimation" />

#### Estimation on Manifolds
* [**Intrinsic Statistics on Riemannian Manifolds** (2011) <br /> *Xavier Pennec* <br /> <img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />](https://hal.inria.fr/inria-00614994/document)
* [**Geometric Statistics for Computational Anatomy** (2016) <br /> *Nina Miolane, PhD Thesis* <br /> <img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />](https://tel.archives-ouvertes.fr/tel-01411886v2/document)
* [**Maximum Likelihood Estimators on Manifolds** (2017) <br /> *Hatem Hajri, Salem Said, Yannick Berthoumieu* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />](https://hal.archives-ouvertes.fr/hal-01500284/document)

<a name="disentangling" />

#### Dimensionality Reduction and Disentangling

* [**Hyperspherical Variational Auto-Encoders** (2018) <br /> *Tim R. Davidson, Luca Falorsi, Nicola De Cao, Thomas Kipf, Jakub M. Tomczak* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://drive.google.com/file/d/1tGGqozCte2XmdzIETYu33LFSGgMvK774/view?usp=sharing)
* [**Addressing the Topological Defects of Disentanglement via Distributed Operators** (2021)  <br /> *Diane Bouchacourt, Mark Ibrahim, Stéphane Deny* <br /> <img src="https://img.shields.io/badge/-topology-FFD3B5" />
](https://arxiv.org/abs/2102.05623v1)
* [**Visualizing Riemannian Data with Rie-SNE** (2022) <br /> *Andri Bergsson and Soren Hauberg* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />](https://arxiv.org/pdf/2203.09253.pdf)
* [**Regularized Autoencoders for Isometric Representation Learning** (2022)  <br /> *Yonghyeon Lee, Sangwoong Yoon, Minjun Son, Frank C. Park* <br /> <img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />
](https://drive.google.com/file/d/1XFdHcPMFDFF-7H10LwLg7N_6d0_cIJmE/view)

<a name="interpretability" />

#### Deep Network Interpretability

* [**Separability and geometry of object manifolds in deep neural networks.** (2020) <br /> *Uri Cohen, SueYeon Chung, Daniel D. Lee, and Haim Sompolinsky.*](https://www.nature.com/articles/s41467-020-14578-5)
* [**Naturally occurring equivariance in neural networks.** (2020) <br /> *Chris Olah, Nick Cammarata, Chelsea Voss, Ludwig Schubert, and Gabriel Goh.*](https://distill.pub/2020/circuits/equivariance/)
* [**The Geometry of Deep Generative Image Models and its Applications** (2021) <br /> *Binxu Wang, Carlos R. Ponce* <br /> <img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />](https://arxiv.org/abs/2101.06006)

<a name="invariance" />

#### Group-Invariant Representation Learning

* [**How we know universals** (1947)  <br /> *Walter Pitts & Warren S. McCulloch* <br /><img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://link.springer.com/content/pdf/10.1007/BF02478291.pdf)
* [**Learning Symmetry Groups with Hidden Units: Beyond the Perceptron** (1986) <br /> *Terrence Sejnowski, Paul K. Kienker, Geoffrey Hinton* <br /><img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://drive.google.com/file/d/1P3QhDIw9vTgYUA-cTMDlRAoXOgpsPQom/view?usp=sharing)
* [**Learning Lie groups for invariant visual perception** (1999) <br /> *Rajesh Rao, Daniel Ruderman* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://proceedings.neurips.cc/paper/1998/file/277281aada22045c03945dcb2ca6f2ec-Paper.pdf)
* [**Learning the Lie groups of visual invariance** (2007) <br /> *Xu Miao, Rajesh Rao* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://direct.mit.edu/neco/article-abstract/19/10/2665/7221/Learning-the-Lie-Groups-of-Visual-Invariance)
* [**An unsupervised algorithm for learning Lie group transformations.** (2010) <br /> Jascha Sohl-Dickstein, Ching Ming Wang, Bruno Olshausen <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://arxiv.org/pdf/1001.1027.pdf)
* [**Learning the irreducible representations of commutative Lie groups** (2014) <br /> *Taco Cohen & Max Welling* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](http://proceedings.mlr.press/v32/cohen14.pdf)
* [**Bispectral Neural Networks** (2022) <br /> *Sophia Sanborn, Christian Shewmake, Bruno Olshausen, Christopher Hillar* <br /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://arxiv.org/abs/2209.03416)


<a name="convolution" />


#### Generalized Convolutional Neural Networks

##### Groups and Homogeneous Spaces
* [**Group equivariant convolutional networks** (2016) <br /> *Taco Cohen & Max Welling* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://drive.google.com/file/d/10JqJrqRysF3c4_ruLe8ad0ijFdVlpjdp/view?usp=sharing)
* [**Steerable CNNs** (2016) <br /> *Taco Cohen & Max Welling* <br /> <img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />
](https://arxiv.org/pdf/1612.08498.pdf)
* [**Harmonic Networks** (2017) <br /> *Daniel E. Worrall, Stephan J. Garbin, Daniyar Turmukhambetov, and Gabriel J. Brostow.* <br /><img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://openaccess.thecvf.com/content_cvpr_2017/papers/Worrall_Harmonic_Networks_Deep_CVPR_2017_paper.pdf)
* [**Spherical CNNs** (2018) <br /> *Taco Cohen, Mario Geiger, Jonas Kohler, & Max Welling* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://drive.google.com/file/d/186hhjJl_fQwEM9_lWpU6Dvac-S1ZTa3A/view?usp=sharing)
* [**Clebsch–Gordan nets: a fully Fourier space spherical convolutional neural network** (2018) <br /> *Risi Kondor, Zhen Lin, Shubhendu Trivedi* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://drive.google.com/file/d/1-NuvFpo0VkY-NDbt89oGDroz23yQ9nhL/view?usp=sharing)
* [**Tensor field networks: Rotation-and translation-equivariant neural networks for 3d point clouds** (2018) <br /> *Nathaniel Thomas, Tess Smidt, Steven Kearnes, Lusann Yang, Li Li, Kai Kohlhoff, Patrick Riley* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://drive.google.com/file/d/1nwbEb9FIJ04aSX40BIZtAxH5ujTQ7Lfv/view?usp=sharing)
* [**A General Theory of Equivariant CNNs on Homogeneous Spaces** (2019)<br /> *Taco Cohen, Mario Geiger, & Maurice Weiler* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://drive.google.com/file/d/1Vd6ID_HsY9PTHFqCEmPv4iTDlLsoBqVr/view?usp=sharing)
* [**Generalizing convolutional neural networks for equivariance to Lie groups on arbitrary continuous data** (2020) <br /> *Marc Finzi, Samuel Stanton, Pavel Izmailov, Andrew Gordon Wilson* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-groups-DCEDC2" />](https://drive.google.com/file/d/1Xzvq2s7Oj3XXftHFcvrI5IhZklS7tt7L/view?usp=sharing)
* [**PDE-Based Group Equivariant Convolutional Neural Networks** (2022) <br /> *Bart M. N. Smets, Jim Portegies, Erik J. Bekkers & Remco Duits* <br />  <img src="https://img.shields.io/badge/-groups-DCEDC2" /> <img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-PDEs-blue" />](https://link.springer.com/article/10.1007/s10851-022-01114-x)


##### Geodesics and Riemannian Manifolds
* [**Geodesic convolutional neural networks on Riemannian manifolds** (2015) <br /> *Jonathan Masci, Davide Boscaini, Michael Bronstein, and Pierre Vandergheynst* <br /><img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />](https://www.cv-foundation.org/openaccess/content_iccv_2015_workshops/w22/papers/Masci_Geodesic_Convolutional_Neural_ICCV_2015_paper.pdf)
* [**Geometric deep learning on graphs and manifolds using mixture model CNNs** (2017) <br /> *Federico Monti, Davide Boscaini, Jonathan Masci, Emanuele Rodola, Jan Svoboda, and Michael M. Bronstein* <br /> <img src="https://img.shields.io/badge/-differential geometry-A8E6CE" /> <img src="https://img.shields.io/badge/-graphs-FFAAA6" />](https://openaccess.thecvf.com/content_cvpr_2017/papers/Monti_Geometric_Deep_Learning_CVPR_2017_paper.pdf)

##### Gauges and Bundles
* [**Gauge equivariant convolutional networks and the icosahedral CNN** (2019) <br /> *Taco Cohen, Maurice Weiler, Berkay Kicanaoglu, and Max Welling* <br /> <img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />](http://proceedings.mlr.press/v97/cohen19d/cohen19d.pdf)
* [**Coordinate Independent Convolutional Networks - Isometry and Gauge Equivariant Convolutions on Riemannian Manifolds** (2021) <br /> *Maurice Weiler, Patrick Forré, Erik Verlinde, Max Welling* <br /> <img src="https://img.shields.io/badge/-differential geometry-A8E6CE" />
](https://arxiv.org/pdf/2106.06020.pdf)
