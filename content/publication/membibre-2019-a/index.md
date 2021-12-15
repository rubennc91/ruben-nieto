---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Design of FPGA-based Architecture for an Analog Front-End in Broadband PLC
subtitle: ''
summary: ''
authors:
- Francisco Membibre
- Rubén Nieto
- Álvaro Hernández
tags: []
categories: []
date: '2019-09-01'
lastmod: 2021-09-02T13:45:56+02:00
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
publishDate: '2021-12-15T14:54:55.936518Z'
publication_types:
- '1'
abstract: Power-Line Communications have spread worldwide in recent years, mainly
  due to their increasing importance as a feasible alternative to provide broadband
  data access in certain domains, such as Smart Grids, Internet of Things or industrial
  environments in general, where the mains are available. Broadband PLC implies significant
  computational requirements, often related to multi-carrier modulations and high
  data rates that should be managed in parallel. Furthermore, these data rates also
  involve the necessity of specific analog front-ends (AFE), capable of tackling the
  corresponding high sampling frequencies in A/D and D/A converters. This work describes
  the design of an FPGA-based (Field-Programmable Gate Array) architecture, in charge
  of managing an ad-hoc AFE for broadband PLC. The proposal also implements a Filter-Bank
  Multi-Carrier (FBMC) modulation as medium access technique and a synchronism based
  on pilot sequences. A dedicated peripheral has been designed for that purpose, which
  has been integrated in a System-on-Chip (SoC). The proposal has been verified experimentally,
  validating the expected functionality.
publication: '*2019 24th IEEE International Conference on Emerging Technologies and
  Factory Automation (ETFA)*'
doi: 10.1109/etfa.2019.8869166
---
