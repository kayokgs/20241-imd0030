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

Bem vindo ao curso Linguagem de Programação I (IMD0030) oferecido pelo Instituto Metrópole Digital no semestre 2024.1.

Este curso foi desenvolvido para capacitar o estudante a utilizar a linguagem de programação C++ para a implementação de programas visando a solução de problemas. Iremos abordar os seguintes temas:: Operadores de alocação dinâmica; Formas de implementação de TADs (Tipos Abstratos de Dados); Funções e Recursividade; Tipos de recursão; Recursão x Interação; Performance, Expressividade; Introdução a Classes; Construtores e Destrutores; Tipos compostos; Tipos recursivos; Gerenciamento de memória; Modularização de Programas; Depuração e Profiling; Aplicações em estruturas e algoritmos presentes em EDB1.

### Materiais

{% for module in site.modules %}
{{ module }}
{% endfor %}
