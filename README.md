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
### Universidade Federal do Rio Grande do Norte
### Instituto Metrópole Digital - UFRN

{% assign instructors = site.staffers | where: 'role', 'Professor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

Bem vindo ao curso Linguagem de Programação I (IMD0030) oferecido pelo Instituto Metrópole Digital no semestre 2024.1.

Este curso foi desenvolvido para capacitar o estudante a utilizar a linguagem de programação C++ para a implementação de programas visando a solução de problemas. Iremos abordar os seguintes temas:: Operadores de alocação dinâmica; Formas de implementação de TADs (Tipos Abstratos de Dados); Funções e Recursividade; Tipos de recursão; Recursão x Interação; Performance, Expressividade; Introdução a Classes; Construtores e Destrutores; Tipos compostos; Tipos recursivos; Gerenciamento de memória; Modularização de Programas; Depuração e Profiling; Aplicações em estruturas e algoritmos presentes em EDB1.

## Aulas

{% for module in site.modules %}
{{ module }}
{% endfor %}

## Horário de Aula

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}

## Bibliografia
Os principais recursos bibliográficos para esta disciplina estão disponíveis gratuitamente na Internet:

[learncpp.com](https://www.learncpp.com/)

[cplusplus.com](https://cplusplus.com/)

[cppreference.com](https://en.cppreference.com/w/)

[roadmap.sh/cpp](https://roadmap.sh/cpp)


<p class="text-small text-grey-dk-100 mb-0">Template by Kevin Lin &copy; 2023 <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a></p>