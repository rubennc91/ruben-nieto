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
lastmod: 2020-12-28T16:44:58+01:00
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
publishDate: '2020-12-28T15:44:55.287776Z'
publication_types:
- '1'
abstract: 'Los enlaces de comunicación de banda ancha para comunicaciones PLC (Power-Line Communications) utilizan técnicas de modulación multiportadora basadas en banco de filtros (Filter-Bank Multi-Carrier, FBMC), las cuales permiten mejorar la comunicación a través del canal PLC. Para compensar los efectos adversos introducidos por el canal, en la etapa de recepción se incluyen estimadores e igualadores de canal, a costa de aumentar la complejidad del sistema receptor. Entre los igualadores de canal para sistemas FBMC, el igualador L-ASCET (Adaptive Sine-modulated/Cosine-modulated filter bank Equalizer for Transmultiplexers) es uno de los más utilizados. Este trabajo propone una arquitectura mixta hardware/software (HW/SW) para la implementación de un igualador de canal L-ASCET con el cálculo de coeficientes del igualador. Esta propuesta mixta HW/SW hace uso de múltiples núcleos en el desarrollo software, acelerando las tareas implementadas en esta parte.'
publication: "*2020 XXVII Seminario Anual de Automática, Electrńica Industrial e Instrumentaci'\
  \ ́(SAAEI)*"
---
