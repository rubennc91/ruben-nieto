---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Arquitectura SoC para la Implementación de Técnicas NILM en Contadores Inteligentes
subtitle: ''
summary: ''
authors:
- Álvaro Hernández
- Jesús Ureña
- Rubén Nieto
- David Fuentes
tags: []
categories: []
date: '2020-01-01'
lastmod: 2021-09-02T13:46:10+02:00
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
publishDate: '2021-12-15T10:38:25.958436Z'
publication_types:
- '1'
abstract: En las últimas décadas, con el desarrollo a nivel mundial de las redes inteligentes
  de energía, los contadores inteligentes (Smart Meters) se han convertido en una
  pieza clave en un gran número de aplicaciones y servicios finales ofrecidos a los
  usuarios, principalmente debido a su capacidad para medir en tiempo real la energía
  consumida en una vivienda. La disponibilidad de estas medidas ha llevado al desarrollo
  de técnicas para la monitorización de cargas de forma no intrusiva (NILM, Non-Intrusive
  Load Monitoring), en aras de una mayor eficiencia energética, o incluso en aplicaciones
  para la supervisión de la vida independiente en personas de avanzada edad. El rendimiento
  y los resultados finales que pueden obtener las técnicas NILM en la desagregación
  de la energía dependen en gran medida de la frecuencia de muestreo existente en
  el contador inteligente, y el tipo de análisis realizado posteriormente. En este
  sentido, cuanto mayor sea esta frecuencia, mejor suele ser la identificación de
  las cargas, pero también implica una mayor carga computacional. Por ello, este trabajo
  presenta el diseño de una arquitectura SoC (System-on-Chip) basada en un dispositivo
  FPGA (Field-Programmable Gate Array) para la implementación de técnicas NILM en
  un contador inteligente, capaz de manejar el flujo de datos a elevadas frecuencias
  de muestreo e implementar las sucesivas tareas del procesamiento de señal necesarias
  para identificar las cargas. Los resultados experimentales mostrados han permitido
  validar, preliminar y satisfactoriamente, la propuesta.
publication: '*2020 XXVII Seminario Anual de Automática, Electrónica Industrial e
  Instrumentación (SAAEI)*'
---
