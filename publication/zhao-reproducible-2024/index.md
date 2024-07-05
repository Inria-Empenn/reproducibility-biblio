---
title: A reproducible and generalizable software workflow for analysis of large-scale
  neuroimaging data collections using BIDS Apps
authors:
- Chenying Zhao
- Dorota Jarecka
- Sydney Covitz
- Yibei Chen
- Simon B. Eickhoff
- Damien A. Fair
- Alexandre R. Franco
- Yaroslav O. Halchenko
- Timothy J. Hendrickson
- Felix Hoffstaedter
- Audrey Houghton
- Gregory Kiar
- Austin Macdonald
- Kahini Mehta
- Michael P. Milham
- Taylor Salo
- Michael Hanke
- Satrajit S. Ghosh
- Matthew Cieslak
- Theodore D. Satterthwaite
date: '2024-01-01'
publishDate: '2024-07-05T12:03:55.082403Z'
publication_types:
- article-journal
publication: '*Imaging Neuroscience*'
doi: 10.1162/imag_a_00074
abstract: Abstract Neuroimaging research faces a crisis of reproducibility. With massive
  sample sizes and greater data complexity, this problem becomes more acute. Software
  that operates on imaging data defined using the Brain Imaging Data Structure (BIDS)—the
  BIDS App—has provided a substantial advance. However, even using BIDS Apps, a full
  audit trail of data processing is a necessary prerequisite for fully reproducible
  research. Obtaining a faithful record of the audit trail is challenging—especially
  for large datasets. Recently, the FAIRly big framework was introduced as a way to
  facilitate reproducible processing of large-scale data by leveraging DataLad—a version
  control system for data management. However, the current implementation of this
  framework was more of a proof of concept, and could not be immediately reused by
  other investigators for different use cases. Here, we introduce the BIDS App Bootstrap
  (BABS), a user-friendly and generalizable Python package for reproducible image
  processing at scale. BABS facilitates the reproducible application of BIDS Apps
  to large-scale datasets. Leveraging DataLad and the FAIRly big framework, BABS tracks
  the full audit trail of data processing in a scalable way by automatically preparing
  all scripts necessary for data processing and version tracking on high performance
  computing (HPC) systems. Currently, BABS supports jobs submissions and audits on
  Sun Grid Engine (SGE) and Slurm HPCs with a parsimonious set of programs. To demonstrate
  its scalability, we applied BABS to data from the Healthy Brain Network (HBN; n
  = 2,565). Taken together, BABS allows reproducible and scalable image processing
  and is broadly extensible via an open-source development model.
tags:
- Important
links:
- name: URL
  url: 
    https://direct.mit.edu/imag/article/doi/10.1162/imag_a_00074/119046/A-reproducible-and-generalizable-software-workflow
---
