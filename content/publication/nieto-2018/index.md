---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Modelado HLS de un Transmultiplexor Multiportadora para PLC: Comparativa dePrestaciones'
subtitle: ''
summary: ''
authors:
- Rubén Nieto
- Álvaro Hernández
- Raúl Mateos
tags: []
categories: []
date: '2018-01-01'
lastmod: 2021-09-02T13:46:03+02:00
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
publishDate: '2021-12-15T10:38:20.283630Z'
publication_types:
- '1'
abstract: 'Los sistemas de comunicación PLC (Power Line Communications) tienen gran
  aceptación en el ámbito industrial, comercial y doméstico, debido a que aprovechan
  la infraestructura ya instalada en el entorno para proporcionar enlaces de banda
  ancha. Para ello, las distintas propuestas suelen desarrollar una técnica de acceso
  al medio basada en una modulación multiportadora para la transmisión de información.
  Una de las alternativas posibles es el empleo de una modulación multiportadora basada
  en bancos de filtros polifásicos (FBMC, Filter-Bank Multi- Carrier), la cual incorpora
  dicho banco tras la Transformada Discreta del Coseno (DCT, Discrete Cosine Transform),
  en aras de una mejor separación espectral y de mejorar la interferencia entre portadoras
  (ICI, Inter-Carrier Interference). Sin embargo, exige una alta carga computacional,
  con cierta complejidad, lo que lleva a que a menudo se empleen dispositivos FPGA
  (Field- Programmable Gate Arrays) para acometer el diseño de arquitecturas para
  la implementación de las propuestas en tiempo real, con un consumo de recursos eficiente.
  Actualmente, el uso de herramientas de síntesis de alto nivel (HLS, High-Level Synthesis),
  mediante lenguajes de alto nivel, permite generar de forma automática la arquitectura
  hardware a partir de una descripción funcional del sistema, reduciendo el tiempo
  de desarrollo. En este trabajo se presenta una comparativa de un sistema de comunicaciones
  multiportadora FBMC para PLC modelado con HLS, con respecto a la misma algoritmia
  abordada con un enfoque más clásico a partir de modelado en HDL (Hardware Description
  Language). La comparativa analiza los factores que determinan las prestaciones del
  diseño relativos a: tiempo/esfuerzo de desarrollo, consumos de recursos (eficiencia),
  velocidad de computo (dato/ciclo) y frecuencia máxima de operación.'
publication: '*2018 XXV Seminario Anual de Automática, Electrónica Industrial e Instrumentación
  (SAAEI)*'
---
