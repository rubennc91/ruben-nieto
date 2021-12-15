---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Evaluación de una Arquitectura CNN para la Identificación de Cargas en NILM
subtitle: ''
summary: ''
authors:
- Laura de Diego Otón
- Álvaro Hernández Alonso
- Rubén Nieto Capuchino
- Mª Carmen Pérez Rubio
tags: []
categories: []
date: '2021-01-01'
lastmod: 2021-09-02T13:59:02+02:00
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
publishDate: '2021-12-15T10:42:00.946097Z'
publication_types:
- '1'
abstract: Las técnicas utilizadas para la desagregación de energía a menudo buscan
  identificar el uso de las diferentes cargas de una instalación con el objetivo de
  optimizar su eficiencia energética. La posibilidad de monitorizar de forma no intrusiva
  el grado de autonomía o independencia de una persona a través de la inferencia de
  sus rutinas dentro de la vivienda, tomando como fuente de información el uso de
  los distintos electrodomésticos, ofrece un nuevo enfoque en el desarrollo de herramientas
  de soporte para la supervisión de personas de edad avanzada o con leve deterioro
  cognitivo dentro de sus hogares. Dentro de este contexto, este trabajo se centra
  en la fase de identificación de los electrodomésticos (cargas) en uso de la vivienda.
  En él se expone una nueva propuesta en la que, a partir de la señal de corriente
  eléctrica muestreada a alta frecuencia (en el rango de kHz) en un único punto a
  la entrada de la vivienda (normalmente mediante un contador inteligente), el proceso
  de clasificación de cargas se lleva a cabo por medio de una red neuronal convolucional
  (Convolutional Neural Network, CNN), diseñada de forma que su carga computacional
  asociada sea la mínima posible. Para la validación de la propuesta se han utilizado
  las muestras ofrecidas por la base de datos BLUED (Building-Level fUlly labeled
  Electricity Disaggregation), habiéndose obtenido valores del parámetro F1 que alcanzan
  el 90 % en los resultados experimentales.
publication: '*2021 XXVIII Seminario Anual de Automática, Electrónica Industrial e
  Instrumentación (SAAEI)*'
---
