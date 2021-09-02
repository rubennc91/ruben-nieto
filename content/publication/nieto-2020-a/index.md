---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Evaluation of Software Inter-Processor Synchronization Methods for the Zynq-UltraScale+
  Architecture
subtitle: ''
summary: ''
authors:
- Rubén Nieto
- Edel Diaz
- Raúl Mateos
- Álvaro Hernández
tags: []
categories: []
date: '2020-11-01'
lastmod: 2021-09-02T13:46:19+02:00
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
publishDate: '2021-09-02T12:20:25.568931Z'
publication_types:
- '1'
abstract: Current embedded systems provide diverse functionalities and their features
  are evolving constantly. This is the case of the Zynq-UltraScale+ (US+) MPSoC family,
  where it is possible to find a System-on-Chip (SoC) architecture with an Application
  Processor Unit (APU) containing up to four Cortex A53 processing units, as well
  as Graphics Processor Units (GPUs) or Real-Time Processor Units (RPUs) in the same
  device. Nevertheless, the synchronization among these different units is crucial
  whether tackling a multi-core approach, especially in applications in standalone
  mode, without an Operating System (OS). In this work, two methods of synchronization
  among the four cores of the APU in a Zynq-US+ MPSoC device are presented. One of
  them is based on sending interrupts using the InterProcessor Interrupt (IPI), whereas
  the other is based on the use of atomic instructions and mutual exclusion variables
  (mutex). Both methods are managed by the exchange of messages between the processors,
  previously defined by and for the application. The experimental results presented
  here allow both proposals to be compared in terms of running times, also considering
  the particular cases of either a cascaded synchronization among the different cores
  or a broadcast synchronization among processors.
publication: '*2020 XXXV Conference on Design of Circuits and Integrated Systems (DCIS)*'
doi: 10.1109/dcis51330.2020.9268616
---
