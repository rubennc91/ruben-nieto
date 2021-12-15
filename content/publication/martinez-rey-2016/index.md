---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Smart laser scanner for event-based state estimation applied to indoor positioning
subtitle: ''
summary: ''
authors:
- Miguel Martinez-Rey
- Enrique Santiso
- Felipe Espinosa
- Rubén Nieto
- Alfredo Gardel
tags: []
categories: []
date: '2016-10-01'
lastmod: 2021-09-02T13:46:01+02:00
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
publishDate: '2021-12-15T10:41:39.601152Z'
publication_types:
- '1'
abstract: Event-based strategies for control and estimation can offer great benefits
  to the field of indoor localisation. They achieve a more efficient use of resources,
  especially in network communications. In this paper we present the implementation
  of an event-based state estimator for indoor positioning of a mobile robot. The
  detection is carried out by a laser scanner attached to a mini-PC, that has not
  any knowledge of the robot’s kinematics. This PC processes the laser data, obtains
  measurements of the robot position and then decides which samples are transmitted
  to a remote centre where the event-based estimation is carried out. The decision
  is made based on the distance between the actual measurement and the predicted position.
  We tested the performance of different event-based sampling methods and compared
  them with the periodic sampling. Additionally, we tested how the tuning the noise
  covariance matrices of the filter influences the estimation accuracy.
publication: '*2016 International Conference on Indoor Positioning and Indoor Navigation
  (IPIN)*'
doi: 10.1109/ipin.2016.7743613
---
