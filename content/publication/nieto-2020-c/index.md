---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Performance Improvement of PLC Channel Estimator and ASCET Equalizer in a FBMC
  Transmultiplexer Based on a Multi-Core Solution
subtitle: ''
summary: ''
authors:
- Rubén Nieto
- Raúl Mateos
- Álvaro Hernández
tags: []
categories: []
date: '2020-01-01'
lastmod: 2021-09-02T13:45:53+02:00
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
publishDate: '2021-09-02T12:20:10.802453Z'
publication_types:
- '2'
abstract: Power-Line Communication (PLC) employs multi-carrier modulations, such as
  Filter-Bank Multi-Carrier (FBMC), to improve communications through the PLC channel
  and provide an efficient use of the spectrum, thus allowing higher data rates. Since
  one of the main drawbacks is the noisy channel with multipath and frequency-selective
  fading, the receiver typically includes a channel estimator and equalizer, at the
  expense of increasing the computational load and complexity of that receiver and
  making it difficult to obtain real-time solutions. In this context, this work proposes
  a heterogeneous System-on-Chip (SoC) architecture for the real-time implementation
  of a FBMC transmultiplexer that involves the channel estimation and equalization
  at the reception stage. For that purpose, the performance of a multi-core approach
  is evaluated for both the Zynq® 7000 SoC and theZynq®UltraScale+ (US+) devices,
  by using a single-, dual- and quad-core solution to perform the channel estimation
  and the calculation of the equalizer coefficients in the ARM processor available
  in the proposed architecture. Two approaches have been analysed for the necessary
  synchronization among cores; one based on atomic instructions and the other one
  on interrupts. The dual-core proposal in both Zynq® 7000 and Zynq® US+ provides
  a x2 acceleration compared to the single-core proposal, whereas the quad-core one
  inZynq®US+ does not provide a x4 acceleration as expected, due to the timing overheads
  of the synchronization among cores imposed by the data dependencies existing in
  these tasks. Experimental results include the evaluation of the processing times
  for each task in the algorithm, as well as the acceleration obtained by each proposal.
  The proposed architecture can be easily applied to other processing algorithms that
  may take advantage of the parallelism provided by the multi-core approach in a more
  efficient way, depending on their data dependencies.
publication: '*IEEE Access*'
doi: 10.1109/access.2020.3031476
---
