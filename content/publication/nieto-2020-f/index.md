---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Arquitectura Mixta HW/SW para el Igualador de Canal L-ASCET en Comunicaciones
  PLC
subtitle: ''
summary: ''
authors:
- Rubén Nieto
- Raúl Mateos
- Álvaro Hernández
tags: []
categories: []
date: '2020-01-01'
lastmod: 2021-09-02T13:46:12+02:00
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
publishDate: '2021-12-15T10:41:51.204518Z'
publication_types:
- '1'
abstract: Los enlaces de comunicaci´on de banda ancha para comunicaciones PLC (Power-Line
  Communications) utilizan t´ecnicas de modulaci´on multiportadora basadas en banco
  de filtros (Filter-Bank Multi-Carrier, FBMC), las cuales permiten mejorar la comunicaci´on
  a trav´es del canal PLC. Para compensar los efectos adversos introducidos por el
  canal, en la etapa de recepci´on se incluyen estimadores e igualadores de canal,
  a costa de aumentar la complejidad del sistema receptor. Entre los igualadores de
  canal para sistemas FBMC, el igualador L-ASCET (Adaptive Sine-modulated/Cosine-modulated
  filter bank Equalizer for Transmultiplexers) es uno de los m´as utilizados. Este
  trabajo propone una arquitectura mixta hardware/software (HW/SW) para la implementaci´on
  de un igualador de canal L-ASCET con el c´alculo de coeficientes del igualador.
  Esta propuesta mixta HW/SW hace uso de m´ ultiples n´ ucleos en el desarrollo software,
  acelerando las tareas implementadas en esta parte.
publication: '*2020 XXVII Seminario Anual de Automática, Electrónica Industrial e
  Instrumentación (SAAEI)*'
---
