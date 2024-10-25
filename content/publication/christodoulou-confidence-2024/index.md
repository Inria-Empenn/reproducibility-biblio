---
title: 'Confidence intervals uncovered: Are we ready for real-world medical imaging
  AI?'
authors:
- Evangelia Christodoulou
- Annika Reinke
- Rola Houhou
- Piotr Kalinowski
- Selen Erkan
- Carole H. Sudre
- Ninon Burgos
- Sofiène Boutaj
- Sophie Loizillon
- Maëlys Solal
- Nicola Rieke
- Veronika Cheplygina
- Michela Antonelli
- Leon D. Mayer
- Minu D. Tizabi
- M. Jorge Cardoso
- Amber Simpson
- Paul F. Jäger
- Annette Kopp-Schneider
- Gaël Varoquaux
- Olivier Colliot
- Lena Maier-Hein
date: '2024-09-01'
publishDate: '2024-10-25T13:25:50.225704Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: Medical imaging is spearheading the AI transformation of healthcare. Performance
  reporting is key to determine which methods should be translated into clinical practice.
  Frequently, broad conclusions are simply derived from mean performance values. In
  this paper, we argue that this common practice is often a misleading simplification
  as it ignores performance variability. Our contribution is threefold. (1) Analyzing
  all MICCAI segmentation papers (n = 221) published in 2023, we first observe that
  more than 50% of papers do not assess performance variability at all. Moreover,
  only one (0.5%) paper reported confidence intervals (CIs) for model performance.
  (2) To address the reporting bottleneck, we show that the unreported standard deviation
  (SD) in segmentation papers can be approximated by a second-order polynomial function
  of the mean Dice similarity coefficient (DSC). Based on external validation data
  from 56 previous MICCAI challenges, we demonstrate that this approximation can accurately
  reconstruct the CI of a method using information provided in publications. (3) Finally,
  we reconstructed 95% CIs around the mean DSC of MICCAI 2023 segmentation papers.
  The median CI width was 0.03 which is three times larger than the median performance
  gap between the first and second ranked method. For more than 60% of papers, the
  mean performance of the second-ranked method was within the CI of the first-ranked
  method. We conclude that current publications typically do not provide sufficient
  evidence to support which models could potentially be translated into clinical practice.
tags:
- Computer Science - Artificial Intelligence
- Computer Science - Computer Vision and Pattern Recognition
- Computer Science - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2409.17763
---
