---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Arquitectura para Comunicaciones PLC de Banda Ancha basada en un AnalogFront-End
subtitle: ''
summary: ''
authors:
- Francisco Membibre
- Rubén Nieto
- Álvaro Hernández
tags: []
categories: []
date: '2019-01-01'
lastmod: 2021-09-02T13:46:07+02:00
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
publishDate: '2021-12-15T14:55:06.170724Z'
publication_types:
- '1'
abstract: Las comunicaciones PLC (Power-Line Communications) son una importante línea
  de investigación hoy en día debido a la creciente importancia que han ido adquiriendo
  en ciertos ámbitos, como el Internet-of-Things (IoT) o las Smart Grids. Su relevancia
  se debe también en parte al amplio despliegue actual de la red eléctrica, de forma
  que, al realizar las comunicaciones por medio de este canal, se evita la implementación
  de otra red de comunicación paralela con las ventajas que esto conlleva. Las comunicaciones
  PLC de banda ancha, como cualquier otra, requieren en su capa de acceso al medio
  de la implementación de modulaciones multi-portadora, y otras técnicas (sincronismo,
  estimación e igualación de canal, etc.), normalmente de una elevada complejidad
  computacional. A esto se une la necesidad de disponer de los correspondientes conversores
  analógico/digital, y viceversa, así como las necesarias etapas de acondicionamiento,
  normalmente englobados en los módulos Analog Front-End (AFE). En este sentido, este
  trabajo propone una arquitectura capaz de realizar comunicaciones PLC de banda ancha,
  empleando como técnica de acceso al medio una modulación multi-portadora basada
  en banco de filtros (FBMC, Filter-Bank Multi-Carrier) y un sincronismo basado en
  secuencias piloto. Dicha arquitectura, diseñada en un dispositivo FPGA (Field-Programmable
  Gate Array) e integrada en un SoC (Systemon- Chip), realiza el control y gestión
  digital del correspondiente módulo AFE. La propuesta ha sido verificada satisfactoriamente
  mediante un conjunto de pruebas experimentales, validando la funcionalidad prevista.
publication: '*2019 XXVI Seminario Anual de Automática, Electrónica Industrial e Instrumentación
  (SAAEI)*'
---
