---
layout: page
title: Research
nav_order: 3
---

{% include lang_switcher.html active_lang="ja" %}

# 研究紹介

最近の学位論文の題名一覧は[こちら](/contents/thesis_titles)を見てください. 

## 進行中のトピック

{% for topic in site.data.research_topics.ongoing %}
  * [{{ topic.title_ja }}]({{ topic.url }}){% if topic.researchers %} <span class="research-authors">by {% for r in topic.researchers %}{{ r.name }}{% if forloop.last %}{% else %}, {% endif %}{% endfor %}</span>{% endif %}<span class="tags-container">{% for tag in topic.tags %}<span class="research-tag">#{{ tag }}</span>{% endfor %}</span>
{% endfor %}
  
## 過去のトピック

### 高水準・高性能な汎用プログラミングフレームワーク

  * [MassiveThreads: 超軽量スレッドライブラリ](/contents/research/massivethreads)
  * [高性能なタスク並列スケジューラ](research/高性能なタスク並列スケジューラ)
  * [分散共有メモリ](research/分散共有メモリ)
  * [PerformanceAnalysisTools](research/performanceanalysistools)
  * [MPI+ULT](research/mpi_ult)
  * [Lightweight Threading Library and OpenMP Runtime System](research/lightweight_threading_library_and_openmp_runtime_system)
  * [GXP並列シェル・スクリプティング環境](/contents/research/gxp)

### 超高水準・高性能なドメイン特化型プログラミングフレームワーク

  * [大規模な文字列データ向けのアドホックな並列処理系](research/大規模な文字列データ向けのアドホックな並列処理系)
  * [CFG構文解析](research/cfg構文解析)
  * [ParaLite: 並列データベース](/contents/research/paralite)

### 深層学習

  * [Analysis of Large Mini-Batch Training of Neural Networks](research/analysis_of_large_mini-batch_training_of_neural_networks)
  * Accelerating Neural Networks Having Dynamic Computation Graphs
  * [深層学習フレームワークの性能解析](research/深層学習フレームワークの性能解析)

### ストレージとOS

  * [次世代SSDによるVMMを用いたメモリ空間の拡張](research/次世代ssdによるvmmを用いたメモリ空間の拡張)
