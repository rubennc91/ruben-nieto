---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Design of SoC Architecture for the Local Implementation of NILM Techniques
subtitle: ''
summary: ''
authors:
- Álvaro Hernández
- Rubén Nieto
- David Fuentes
- Jesús Ureña
tags: []
categories: []
date: '2020-11-01'
lastmod: 2021-09-02T13:46:14+02:00
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
publishDate: '2021-09-02T12:20:22.878920Z'
publication_types:
- '1'
abstract: In recent years the development and deployment of commercial Smart Meters
  in most households in developed countries have spread the appearance of certain
  applications and methods, mainly related to the fields of Smart Grids and Internet
  of Things, where Non-Intrusive Load Monitoring (NILM) is one of the most well-known.
  It takes advantage of the capability of Smart Meters to acquire the electrical signals
  of a household or building in real time, in order to implement a set of techniques
  oriented to disaggregate the power consumption, according to the different electrical
  loads plugged in the facility. Previous works are often based on a cloud-computing
  approach, where samples are transferred straightforwardly from the local meter to
  the cloud for further analysis. This implies that the sampling rates are low in
  order to keep the required bandwidth reduced, thus constraining the final performance
  achieved in the load identification. This work presents the design of a System-on-Chip
  (SoC) architecture based on a Field-Programmable Gate Array (FPGA) device that can
  be installed locally at the input of the electrical installation from a house or
  building. It is able to manage data rates at high sampling frequencies and to implement
  in real time those algorithms proposed for the electrical signal processing and
  load classification. Experimental results have preliminary validated the proposed
  architecture.
publication: '*XXXVII Conference on Design of Circuits and Integrated Systems (DCIS
  2020)*'
doi: 10.1109/DCIS51330.2020.9268626
---
