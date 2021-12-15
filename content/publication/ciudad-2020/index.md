---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Diseño de una Arquitectura SoC con Periféricos Específicos para un Sistema
  dePosicionamiento Ultrasónico
subtitle: ''
summary: ''
authors:
- Francisco Ciudad
- Álvaro Hernández
- Rubén Nieto
- David Gualda
tags: []
categories: []
date: '2020-01-01'
lastmod: 2021-09-02T13:46:11+02:00
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
publishDate: '2021-12-15T14:55:10.807136Z'
publication_types:
- '1'
abstract: Las arquitecturas SoC están teniendo un avance muy significativo en los
  últimos años debido a la posibilidad de flexibilizar los sistemas para adaptarlos
  a una gran variedad de aplicaciones. En este trabajo se presenta un sistema de posicionamiento
  ultrasónico en el que la recepción y procesamiento de la señal se lleva a cabo en
  un dispositivo SoC. El sistema recibe las transmisiones ultrasónicas, moduladas
  y codificadas por secuencias binarias, a una frecuencia de adquisición de 100 kHz.
  La señal capturada se envía a un periférico específico incluido en la arquitectura
  SoC, cuyo funcionamiento se basa en la realización de las correlaciones con las
  secuencias que se han emitido y la obtención de los picos de esas correlaciones.
  Una vez que se obtienen estos datos, se trasladan al procesador de la arquitectura
  SoC, para lo cual se ha desarrollado el correspondiente device driver. A partir
  de este driver, la aplicación de usuario obtiene las diferencias en tiempos de vuelo
  de las señales recibidas, para, posteriormente, estimar la posición del receptor
  móvil a partir de un algoritmo de posicionamiento hiperbólico en función de la localización
  de las balizas ultrasónicas que se hayan empleado.
publication: '*2020 XXVII Seminario Anual de Automática, Electrónica Industrial e
  Instrumentación (SAAEI)*'
---
