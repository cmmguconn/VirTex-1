About
=====

***************
Introduction
***************

VirTex - a set of python scripts to perform texture analysis for atomistic data (MD). It generates several texture-related properties such as Euler angles, rotation matrix, angle-axis pairs, orientation, misorientation angles, and Schmid Factor that can complement experimental observations. 

VirTex utilizes the following packages-

* VirTex is written in **python** (I/O by pandas)
* Quaternion angles are generated by permoring Polyhedral Template Matching (PMT) using `LAMMPS <https://www.lammps.org/#gsc.tab=0>`_ or `Ovito <https://www.ovito.org/>`_

VirTex is developed at `Department of Materials Science and Engineering <https://mse.engr.uconn.edu/>`_, and `Institute of Materials Science <https://www.ims.uconn.edu/>`_, `University of Connecticut <https://uconn.edu/>`_, CT, USA in the group of Prof. Avinash M Dongare (`Computational Materials and Mechanics Group <https://dongare.group.uconn.edu/>`_). The article associated with VirTex proposes its application for finding orientation, misorientation, and angle-axis pairs. Still, for the package release, it is extended to calculate the Schmid Factor and automatic identification of peaks in angle-axis pair distribution. VirTex will be released in 2022 as an open-source package. We welcome collaborators for future development of the package; we would also focus on developing VirTex sister packages. Sister packages of VirTex are `pyMAINS <https://github.com/mrcavam/pyMAINS>`_ (*python-pandas package to analyze MD data*) and VirDi (**Virtual diffraction package** is *under development*). 

***************
Getting Help
***************

Any issues that are not self-resolved by our tutorials and FAQ or development questions could be directed to `virtex@gmail.com  <virtex@gmail.com>`_. Please check the already published article to explore the methodology. 

***************
Release history
***************

Release 0.0.1 (2022)
~~~~~~~~~~~~~~~~~~~~
* initial version of VirTex in the form of python scripts
