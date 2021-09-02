---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Data Collection and Cloud Processing Architecture Applied to NILM Techniques
  for Independent Living
subtitle: ''
summary: ''
authors:
- Rubén Nieto
- Laura de Diego-Oton
- Álvaro Hernández
- Jesús Ureña
tags: []
categories: []
date: '2021-05-01'
lastmod: 2021-09-02T13:46:17+02:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: 'General aspect of the smart meter implemented to carry out the different tests in the laboratory.'
  focal_point: 'Center'
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-09-02T12:20:24.481820Z'
publication_types:
- '1'
abstract: Non-intrusive load monitoring (NILM) concerns those techniques used to disaggregate
  the individual consumption of the different appliances from the aggregated measurements
  of the electrical power supply. A knowledge about which appliances are used during
  a time interval may help improve the energy efficiency at home. Furthermore, it
  may be useful to assist and support the development of independent living of elderly
  or people with mild cognitive impairments, since it is possible to follow the behaviour
  of these persons from their energy consumption and the identification of the appliances
  used over time. In order to reach these objectives, it is necessary to capture the
  aggregate voltage and current signals at the entrance of the home using a smart
  meter or a third-party device. Furthermore, the behaviour analysis of a person requires
  that the collected data are sent to a central node (e.g. a remote server), which
  carries out the post-processing, thus implying a significant bandwidth. In this
  work, a proposal for data collection and processing on the edge, as well as the
  communication and processing on the cloud are presented for a NILM application,
  which aims to provide assistance in the development of independent living for elderly.
  For this purpose, the network communication of the smart meter installed at home
  is described, together with the processing and event detection on the edge. After
  an event is detected, data are sent to the cloud platform, where the energy disaggregation
  algorithms are performed, as well as the management of the cloud server. The data
  acquisition of the voltage and current signals is carried out at 4 ksamples/s and
  a window of 900 samples around the event for each signal (voltage and current) is
  sent to the remote server. This reduces the bandwidth required in the cloud communication,
  sending only the data related to the event while keeping the information required
  for the energy disaggregation algorithms implemented in the cloud server.
publication: '*2021 IEEE International Instrumentation and Measurement Technology
  Conference (I2MTC)*'
doi: 10.1109/i2mtc50364.2021.9460010
---
