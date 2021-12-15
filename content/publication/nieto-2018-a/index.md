---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Finite Precision Analysis of FPGA-based Architecture for FBMC Transmultiplexers
  in Broadband PLC
subtitle: ''
summary: ''
authors:
- Rubén Nieto
- Edel Díaz
- Raúl Mateos
- Álvaro Hernández
tags: []
categories: []
date: '2018-11-01'
lastmod: 2021-09-02T13:46:15+02:00
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
publishDate: '2021-12-15T14:55:13.735425Z'
publication_types:
- '1'
abstract: Power-Line Communications (PLC) systems are becoming more and more relevant
  in certain environments since they take advantage of the infrastructure already
  installed to provide broadband data access. Previous proposals have developed different
  medium access techniques based on a Multi-Carrier Modulation (MCM) for the transmission
  of information, such as Filter-Bank Multi-Carrier (FBMC). These transmultiplexers
  present a receiver, where an equalizer is involved to compensate the effects coming
  from the PLC channel. Due to their high computational load, the definition of suitable
  hardware architectures for the real-time implementation of these proposals is still
  an ongoing issue. Currently, Field-Programmable Gate Array (FPGA) devices support
  implementations based on floating- or a fixed-point representation. This work presents
  an analysis between a fixed- and a floating-point architecture for the real-time
  implementation of a FBMC receiver, including an Adaptive SMFB/CMFB Equalizer for
  Transmultiplexers (ASCET), applied to broadband PLC. The study deals with every
  block from the FBMC scheme, analyzing which representation (fixed- or single floating-point)
  is more suitable in terms of performance and resource consumption. For that purpose,
  the Signal-Noise Ratio (SNR) and Root-Mean-Square Error (RMSE) for the whole system
  have been estimated. The final architecture has been particularized for a Zynq UltraScale+
  device, taking into account the internal DSP cells and memory blocks.
publication: '*XXXV Conference on Design of Circuits and Integrated Systems (DCIS
  2018)*'
doi: 10.1109/dcis.2018.8681466
---
