---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Recurrent LSTM Architecture for Appliance Identification in Non-Intrusive Load
  Monitoring
subtitle: ''
summary: ''
authors:
- Laura de Diego-Oton
- David Fuentes-Jimenez
- Álvaro Hernández
- Rubén Nieto
tags: []
categories: []
date: '2021-05-01'
lastmod: 2021-09-02T13:46:18+02:00
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
publishDate: '2021-09-02T12:20:25.032795Z'
publication_types:
- '1'
abstract: Non-Intrusive Load Monitoring (NILM) techniques are commonly used to measure
  and identify the power consumption of different types of household appliances, starting
  from an aggregated signal obtained from a single measurement point. Currently, they
  are often based on the extended deployment of smart meters (SM) carried out in most
  developed countries in the last decade. Based on the measurements acquired by SMs,
  it is possible to disaggregate energy consumption, and then to identity the corresponding
  loads plugged to the mains of a house or building. NILM techniques can be applied
  in different application fields, such as energy efficiency, active demand response
  management, or even as a way to infer the behaviour patterns of the people living
  in a certain household under monitoring, in the context of Ambient Intelligence
  for Independent Living (AIIL). This paper presents a new approach for energy disaggregation
  through the use of Recurrent Neural Networks (RNN) based on measurements from a
  single point at low sampling rates. The proposed framework takes the power signals
  acquired by an SM as inputs, then pre-processes and detects the on/off switching
  events of the different appliances considered, and finally classifies them using
  two different Long Short Term Memory (LSTM)-based topologies. The proposal validation
  is carried out through the use of the well-known public dataset Building Level fUlly
  labelled for Electricity Disaggregation (BLUED). Several configurations of classification
  topologies have been compared, obtaining an average classification accuracy in the
  experimental results that exceeds 85%.
publication: '*2021 IEEE International Instrumentation and Measurement Technology
  Conference (I2MTC)*'
doi: 10.1109/i2mtc50364.2021.9460046
---
