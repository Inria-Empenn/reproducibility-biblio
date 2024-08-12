---
title: A reproducible benchmark of resting-state fMRIdenoising strategies using fMRIPrep
  and Nilearn
authors:
- Hao-Ting Wang
- Steven L Meisler
- Hanad Sharmarke
- Natasha Clarke
- François Paugam
- Nicolas Gensollen
- Christopher J Markiewicz
- Bertrand Thirion
- Pierre Bellec
date: '2023-06-01'
publishDate: '2024-08-12T09:30:40.871960Z'
publication_types:
- manuscript
doi: 10.55458/neurolibre.00012
abstract: Reducing contributions from non-neuronal sources is a crucial step in functional
  magnetic resonance imaging (fMRI) connectivity analyses. Many viable strategies
  for denoising fMRI are used in the literature, and practitioners rely on denoising
  benchmarks for guidance in the selection of an appropriate choice for their study.
  However, fMRI denoising software is an ever-evolving field, and the benchmarks can
  quickly become obsolete as the techniques or implementations change. In this work,
  we present a fully reproducible denoising benchmark featuring a range of denoising
  strategies and evaluation metrics for connectivity analyses, built primarily on
  the fMRIPrep (Esteban et al., 2018) and Nilearn (Abraham et al., 2014) software
  packages. We apply this reproducible benchmark to investigate the robustness of
  the conclusions across two different datasets and two versions of fMRIPrep. The
  majority of benchmark results were consistent with prior literature. Scrubbing,
  a technique which excludes time points with excessive motion, combined with global
  signal regression, is generally effective at noise removal. Scrubbing however disrupts
  the continuous sampling of brain images and is incompatible with some statistical
  analyses, e.g. auto-regressive modeling. In this case, a simple strategy using motion
  parameters, average activity in select brain compartments, and global signal regression
  should be preferred. Importantly, we found that certain denoising strategies behave
  inconsistently across datasets and/or versions of fMRIPrep, or had a different behavior
  than in previously published benchmarks. These results demonstrate that a reproducible
  denoising benchmark can effectively assess the robustness of conclusions across
  multiple datasets and software versions. In addition to reproducing core computations,
  interested readers can also reproduce or modify the figures of the article using
  the Jupyter Book project (Granger & Pérez, 2021) and the Neurolibre (Karakuzu et
  al., 2022) reproducible preprint server. With the denoising benchmark, we hope to
  provide useful guidelines for the community, and that our software infrastructure
  will facilitate continued development as the state-of-the-art advances.
links:
- name: URL
  url: https://neurolibre.org/papers/10.55458/neurolibre.00012
---
