---
title: Integrating the BIDS Neuroimaging Data Format and Workflow Optimization for
  Large-Scale Medical Image Analysis
authors:
- Shunxing Bao
- Brian D. Boyd
- Praitayini Kanakaraj
- Karthik Ramadass
- Francisco A. C. Meyer
- Yuqian Liu
- William E. Duett
- Yuankai Huo
- Ilwoo Lyu
- David H. Zald
- Seth A. Smith
- Baxter P. Rogers
- Bennett A. Landman
date: '2022-12-01'
publishDate: '2024-07-05T12:03:55.097470Z'
publication_types:
- article-journal
publication: '*Journal of Digital Imaging*'
doi: 10.1007/s10278-022-00679-8
abstract: A robust medical image computing infrastructure must host massive multimodal
  archives, perform extensive analysis pipelines, and execute scalable job management.
  An emerging data format standard, the Brain Imaging Data Structure (BIDS), introduces
  complexities for interfacing with XNAT archives. Moreover, workflow integration
  is combinatorically problematic when matching large amount of processing to large
  datasets. Historically, workflow engines have been focused on refining workflows
  themselves instead of actual job generation. However, such an approach is incompatible
  with data centric architecture that hosts heterogeneous medical image computing.
  Distributed automation for XNAT toolkit (DAX) provides large-scale image storage
  and analysis pipelines with an optimized job management tool. Herein, we describe
  developments for DAX that allows for integration of XNAT and BIDS standards. We
  also improve DAX’s efficiencies of diverse containerized workflows in a high-performance
  computing (HPC) environment. Briefly, we integrate YAML configuration processor
  scripts to abstract workflow data inputs, data outputs, commands, and job attributes.
  Finally, we propose an online database–driven mechanism for DAX to efficiently identify
  the most recent updated sessions, thereby improving job building efficiency on large
  projects. We refer the proposed overall DAX development in this work as DAX-1 (DAX
  version 1). To validate the effectiveness of the new features, we verified (1) the
  efficiency of converting XNAT data to BIDS format and the correctness of the conversion
  using a collection of BIDS standard containerized neuroimaging workflows, (2) how
  YAML-based processor simplified configuration setup via a sequence of application
  pipelines, and (3) the productivity of DAX-1 on generating actual HPC processing
  jobs compared with earlier DAX baseline method. The empirical results show that
  (1) DAX-1 converting XNAT data to BIDS has similar speed as accessing XNAT data
  only; (2) YAML can integrate to the DAX-1 with shallow learning curve for users,
  and (3) DAX-1 reduced the job/assessor generation latency by finding recent modified
  sessions. Herein, we present approaches for efficiently integrating XNAT and modern
  image formats with a scalable workflow engine for the large-scale dataset access
  and processing.
links:
- name: URL
  url: https://link.springer.com/10.1007/s10278-022-00679-8
---
