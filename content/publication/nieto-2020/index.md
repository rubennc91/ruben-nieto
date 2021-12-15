---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Finite Precision Analysis for an FPGA-based NILM Event-Detector
subtitle: ''
summary: ''
authors:
- Rubén Nieto
- Laura de Diego-Otón
- Álvaro Hernández
- Jesús Ureña
tags: []
categories: []
date: '2020-11-01'
lastmod: 2021-09-02T13:46:20+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-12-15T10:38:34.834668Z'
publication_types:
- '1'
abstract: Most Non-Intrusive Load Monitoring (NILM) techniques often require a correct
  detection of the events that occur in the mains, in order to carry out a correct
  identification of the corresponding appliances. For that performance, event-detectors
  are normally based on signals, such as voltages and currents, acquired by a smart
  meter at the entrance of the household. In this work, a finite precision analysis
  is performed for an event detector implemented on a System-on-Chip (SoC) based on
  a Field-Programmable Gate Array (FPGA) for NILM applications. The proposal employs
  an integrated circuit (ADE9153A) to perform the signal acquisition at 4 ksamples/s,
  higher than those used in common smart meters installed at homes nowadays. The purpose
  of the finite precision analysis is to reduce the hardware resource consumption
  of the FPGA, while the precision of the event detector is maintained. To validate
  the design, a comparison is carried out in terms of accuracy and specificity against
  previous works, as well as a comparison of the event detector using finite precision
  (fixed-point) and single-precision floating-point resolution. Finally, the hardware
  resource consumption obtained for the proposed architecture is discussed.
publication: '*Proceedings of the 5th International Workshop on Non-Intrusive Load
  Monitoring*'
doi: 10.1145/3427771.3427849
---
