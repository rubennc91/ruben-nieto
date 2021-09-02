---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Aplicación de Unidad Vectorial NEON para la Implementación de un Transmultiplexor
  FBMC con Estimador e Igualador de Canal
subtitle: ''
summary: ''
authors:
- Rubén Nieto
- Álvaro Hernández
- Raúl Mateo
tags: []
categories: []
date: '2019-01-01'
lastmod: 2021-09-02T13:46:08+02:00
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
publishDate: '2021-09-02T12:20:19.592185Z'
publication_types:
- '1'
abstract: Las modulaciones multiportadora usadas en las comunicaciones PLC (Power-Line
  Communications), como Filter- Bank Multi-Carrier (FBMC), permiten enlaces de comunicación
  de banda ancha y mejoran la comunicación a través del canal PLC, a expensas de añadir
  complejidad al sistema. El principal inconventiente de las mismas es el canal de
  comunicación PLC, rudioso y con notables interferencias. Para compensar esos efectos
  adversos introducidos en el canal, en la etapa de recepción se incluye en ocasiones
  un estimador de canal y un igualador, a costa de incrementar la carga computacional
  y la complejidad del sistema en la etapa de recepción. Este trabajo propone el uso
  de la unidad vectorial NEON, disponible en ciertos Systems-on-Chip (SoC), para realizar
  el cálculo de la estimación de canal PLC, con el objetivo de estudiar la viabilidad
  de alcanzar una arquitectura HW/SW para la implementación de un transmultiplexor
  FBMC con estimador e igualador de canal. Los resultados de este estudio incluyen
  la evaluación del tiempo que consume la unidad vectorial NEON en el cálculo de la
  FFT (Fast Fourier Transform) y diferentes operaciones vectoriales, como la suma
  o multiplicación entre vectores. Se presenta la aceleración que supone el uso de
  la unidad vectorial NEON frente a la codificación en C sin uso de la misma. Por
  último, se proporciona el consumo de recursos que tendría el cálculo de una FFT
  similar implementada en hardware específico para completar la comparación.
publication: '*2019 XXVI Seminario Anual de Automática, Electrónica Industrial e Instrumentación
  (SAAEI)*'
---
