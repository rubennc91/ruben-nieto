---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: CEO
    company: GenCoin
    company_url: ''
    company_logo: org-gc
    location: California
    date_start: '2021-01-01'
    date_end: ''
    description: |2-
        Responsibilities include:
        
        * Analysing
        * Modelling
        * Deploying
        
  - title: Professor of Semiconductor Physics
    company: University X
    company_url: ''
    company_logo: org-x
    location: California
    date_start: '2016-01-01'
    date_end: '2020-12-31'
    description: Taught electronic engineering and researched semiconductor physics.

design:
  columns: '2'
---

+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 28  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Visiting Professor"
  company = "Rey Juan Carlos University"
  company_url = "www.urjc.es"
  location = "Móstoles (Madrid) - Spain"
  date_start = "2021-01-16"
  date_end = "" 
  description = """In the 2020-21 academic year I have taught: Hospital Engineering for the Bachelors Degree in Biomedical Engineering; Electrical Engineering and Electronics for the Bachelor's Degrees in Industrial Organization Engineering, Materials Engineering and Mechanical Engineering; Analog Electronics, Fundamentals of Engineering of Electrical Engineering and Automatic Regulation I of the Bachelors Degree in Industrial Electronics and Automation Engineering."""
# date_end = "2021-04-30"
[[experience]]
  title = "Postdoctoral Research"
  company = "University of Alcala"
  company_url = "www.uah.es"
  location = "Alcala de Henares (Madrid) - Spain"
  date_start = "2020-05-01"
  date_end = "2021-01-15" 
  description = """SoC implementation for NILM techniques."""
# date_end = "2021-04-30"

[[experience]]
  title = "Research staff"
  company = "University of Alcala"
  company_url = "www.uah.es"
  location = "Alcala de Henares (Madrid) - Spain"
  date_start = "2017-02-15"
  date_end = "2020-01-14"
  description = """PhD in Electronics: Advanced Electronic Systems. Intelligent Systems. Thesis entitled: "Design of Efficient Heterogeneous Architectures for Broadband Power-Line Communications". Thesis grade: Cum-Laude."""

+++
