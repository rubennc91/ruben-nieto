---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Dual-Core Architecture for PLC Channel Estimator and ASCET Equalizer in a FBMC
  Transmultiplexer
subtitle: ''
summary: ''
authors:
- Rubén Nieto
- Raúl Mateos
- Álvaro Hernández
- Edel Díaz
tags: []
categories: []
date: '2019-09-01'
lastmod: 2021-09-02T13:45:55+02:00
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
publishDate: '2021-09-02T12:20:12.008412Z'
publication_types:
- '1'
abstract: Multi-carrier modulations used in Power-Line Communications (PLC), such
  as Filter-Bank Multi-Carrier (FBMC), allow broadband links and improve communications
  through the PLC channel, at the expense of adding complexity to the system. Although
  they perform suitably in most cases, the main drawback is often the PLC channel,
  noisy and with significant interferences. To compensate these adverse effects introduced
  by the channel, the reception stage includes a channel estimator and an equalizer,
  which also implies a higher computational load and complexity of the system at this
  stage, becoming difficult to achieve feasible architectures for real-time implementations.
  This work proposes an efficient dual-core solution to carry out the channel estimation
  and calculation of ASCET coefficients in the ARM processor of the Zynq-7000 System-on-Chip
  (SoC), with the objective of studying the feasibility of reaching a hardware/software
  architecture for the implementation of an FBMC transmultiplexer with channel estimator
  and equalizer. Preliminary results shown here include the evaluation of the time
  consumed by each part of the algorithm, and present the acceleration obtained by
  the dual-core proposal, depending on the order of L-ASCET equalizer considered.
publication: '*2019 24th IEEE International Conference on Emerging Technologies and
  Factory Automation (ETFA)*'
doi: 10.1109/etfa.2019.8869476
---
