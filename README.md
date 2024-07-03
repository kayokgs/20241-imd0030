---
layout: minimal
title: Lógica de Programação
nav_enabled: false
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: Lógica de Programação I
---

# Linguagem de Programação I
### Instituto Metrópole Digital - UFRN

{% assign instructors = site.staffers | where: 'role', 'Professor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

Esta é a disciplina de 2024.1 - LP1

### Materiais

{% for module in site.modules %}
{{ module }}
{% endfor %}
