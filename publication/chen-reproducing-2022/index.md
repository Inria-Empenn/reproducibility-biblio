---
title: "Reproducing FSL's fMRI data analysis via Nipype: Relevance, challenges, and
  solutions"
authors:
- Yibei Chen
- Frederic R. Hopp
- Musa Malik
- Paula T. Wang
- Kylie Woodman
- Sungbin Youk
- René Weber
date: '2022-07-01'
publishDate: '2024-07-05T12:03:55.119437Z'
publication_types:
- article-journal
publication: '*Frontiers in Neuroimaging*'
doi: 10.3389/fnimg.2022.953215
abstract: The “replication crisis” in neuroscientific research has led to calls for
  improving reproducibility. In traditional neuroscience analyses, irreproducibility
  may occur as a result of issues across various stages of the methodological process.
  For example, different operating systems, different software packages, and even
  different versions of the same package can lead to variable results. Nipype, an
  open-source Python project, integrates different neuroimaging software packages
  uniformly to improve the reproducibility of neuroimaging analyses. Nipype has the
  advantage over traditional software packages (e.g., FSL, ANFI, SPM, etc.) by (1)
  providing comprehensive software development frameworks and usage information, (2)
  improving computational efficiency, (3) facilitating reproducibility through sufficient
  details, and (4) easing the steep learning curve. Despite the rich tutorials it
  has provided, the Nipype community lacks a standard three-level GLM tutorial for
  FSL. Using the classical Flanker task dataset, we first precisely reproduce a three-level
  GLM analysis with FSL via Nipype. Next, we point out some undocumented discrepancies
  between Nipype and FSL functions that led to substantial differences in results.
  Finally, we provide revised Nipype code in re-executable notebooks that assure result
  invariability between FSL and Nipype. Our analyses, notebooks, and operating software
  specifications (e.g., docker build files) are available on the Open Science Framework
  platform.
links:
- name: URL
  url: https://www.frontiersin.org/articles/10.3389/fnimg.2022.953215/full
---
