---
# Documentation: https://wowchemy.com/docs/managing-content/

title: HW/SW Architecture for a Broadband Power-Line Communication System With LS
  Channel Estimator and ASCET Equalizer
subtitle: ''
summary: ''
authors:
- Rubén Nieto
- Raúl Mateos
- Álvaro Hernández
tags: []
categories: []
date: '2020-11-01'
lastmod: 2021-09-02T13:45:54+02:00
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
publishDate: '2021-12-15T14:54:54.101534Z'
publication_types:
- '2'
abstract: Power-line communication (PLC) systems are used for data transmission through
  the mains. The deployment of intelligent networks and the high demand for broadband
  communications have made this technology spread worldwide in recent years. Multicarrier
  modulations, such as filter-bank multicarrier (FBMC), allow broadband links to be
  achieved by improving intercarrier interference, at the cost of adding complexity
  to the system. Nevertheless, the main disadvantage of PLC is the medium, commonly
  with significant noise and interference. To compensate these effects inserted by
  the channel, channel estimators and equalizers are often included at the reception
  stage, at the expense of increasing the computational load and complexity of the
  resulting receiver. This article proposes a hardware/software (HW/SW) architecture
  for the real-time implementation of an FBMC transmultiplexer with a channel estimator
  and an L-Adaptive sine/cosine modulated filter bank equalizer for transmultiplexers
  (L-ASCET) equalizer. The FBMC transmultiplexer and the L-ASCET equalizer are implemented
  in HW, whereas the channel estimation and the determination of the equalizer coefficients
  are specified in SW, all forming a system-on-chip architecture. The performance
  provided by the proposal has been evaluated in terms of the signal-to-noise ratio,
  the root-mean-square error, and the bit error rate.
publication: '*IEEE Transactions on Industrial Informatics*'
doi: 10.1109/tii.2020.2969448
---
