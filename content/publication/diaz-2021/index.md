---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Enabling Parallelized-QEMU for Hardware/Software Co-Simulation Virtual Platforms
subtitle: ''
summary: ''
authors:
- Edel Díaz
- Raúl Mateos
- Emilio J. Bueno
- Rubén Nieto
tags: []
categories: []
date: '2021-03-01'
lastmod: 2021-09-02T13:46:16+02:00
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
publishDate: '2021-12-15T10:38:30.347359Z'
publication_types:
- '2'
abstract: 'Presently, the trend is to increase the number of cores per chip. This
  growth is appreciated in Multi-Processor System-On-Chips (MPSoC), composed of more
  cores in heterogeneous and homogeneous architectures in recent years. Thus, the
  difficulty of verification of this type of system has been great. The hardware/software
  co-simulation Virtual Platforms (VP) are presented as a perfect solution to address
  this complexity, allowing verification by simulation/emulation of software and hardware
  in the same environment. Some works parallelized the software emulator to reduce
  the verification times. An example of this parallelization is the QEMU (Quick EMUlator)
  tool. However, there is no solution to synchronize QEMU with the hardware simulator
  in this new parallel mode. This work analyzes the current software emulators and
  presents a new method to allow an external synchronization of QEMU in its parallelized
  mode. Timing details of the cores are taken into account. In addition, performance
  analysis of the software emulator with the new synchronization mechanism is presented,
  using: (1) a boot Linux for MPSoC Zynq-7000 (dual-core ARM Cortex-A9) (Xilinx, San
  Jose, CA, USA); (2) an FPGA-Linux co-simulation of a power grid monitoring system
  that is subsequently implemented in an industrial application. The results show
  that the novel synchronization mechanism does not add any appreciable computational
  load and enables parallelized-QEMU in hardware/software co-simulation virtual platforms.'
publication: '*Electronics*'
doi: 10.3390/electronics10060759
---
