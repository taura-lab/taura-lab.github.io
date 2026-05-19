---
layout: page
title: Research
nav_order: 3
---

{% include lang_switcher.html active_lang="en" %}

# Research

You can see recent thesis titles [here](/en/contents/thesis_titles).

## On-going topics

{% for topic in site.data.research_topics.ongoing %}

- [{{ topic.title }}]({{ topic.url }}){% if topic.researchers %} <span class="research-authors">by {% for r in topic.researchers %}{{ r.name }}{% if forloop.last %}{% else %}, {% endif %}{% endfor %}</span>{% endif %}<span class="tags-container">{% for tag in topic.tags %}<span class="research-tag">#{{ tag }}</span>{% endfor %}</span>
  {% endfor %}

## Past topics

### High-Level, High-Performance General-Purpose Programming Frameworks

- [MassiveThreads: Super Lightweight Thread Library](/en/contents/research/massivethreads)
- [高性能なタスク並列スケジューラ](/contents/research/高性能なタスク並列スケジューラ)
- [分散共有メモリ](/contents/research/分散共有メモリ)
- [Performance Analysis Tools](/contents/research/performanceanalysistools)
- [MPI+ULT](/contents/research/mpi_ult)
- [Lightweight Threading Library and OpenMP Runtime System](/contents/research/lightweight_threading_library_and_openmp_runtime_system)
- [GXP Parallel Shell/Scripting Tool](/en/contents/research/gxp)

### Very High-Level, High-Performance Domain-Specific Programming Frameworks

- [大規模な文字列データ向けのアドホックな並列処理系](/contents/research/大規模な文字列データ向けのアドホックな並列処理系)
- [CFG構文解析](/contents/research/cfg構文解析)
- [ParaLite: Parallel Database](/en/contents/research/paralite)

### Deep Learning

- [Analysis of Large Mini-Batch Training of Neural Networks](/contents/research/analysis_of_large_mini-batch_training_of_neural_networks)
- Accelerating Neural Networks Having Dynamic Computation Graphs
- [深層学習フレームワークの性能解析](/contents/research/深層学習フレームワークの性能解析)

### Storage and Operating System

- [次世代SSDによるVMMを用いたメモリ空間の拡張](/contents/research/次世代ssdによるvmmを用いたメモリ空間の拡張)
