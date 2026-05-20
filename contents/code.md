---
layout: page
title: Code
nav_order: 5
---

{% include lang_switcher.html active_lang="ja" %}

# コード

システムソフトウェアを研究するグループとして，私たちは研究成果としての公開に加え，研究全体の効率化に資するものとして，オープンソースソフトウェアの公開に強い関心を持っています．今後さらに追加していく予定です．

## 研究

  * [MassiveThreads](https://github.com/massivethreads/massivethreads) は，Pthreads 互換 API を備え，数百万スレッドを扱える高性能マルチスレッドライブラリです．
  * [GXP](https://github.com/qnu/gxp/) は，クラスター，スーパーコンピュータ，分散システム向けの並列シェルで，並列／分散 make もサポートしています．
  * [sshfsmux](https://github.com/qnu/sshfsmux/) は，1つのマウントポイント上で SSH 経由で複数ホストをマウントできる，FUSE ベースのファイルシステムです． 
  * [paratrac](https://github.com/qnu/paratrac/) は，FUSE ベースのファイルシステムプロファイリングツールです．
  * [Itoyori](https://github.com/itoyori/itoyori) は，グローバルビューの fork-join タスク並列性のための分散マルチスレッドランタイムシステムです．

## 小規模ツール

  * [textshot](https://github.com/taura/textshot) は，jumpshot-4（slog2）性能可視化ツールのシンプルなラッパーで，非常に簡単なテキストベースのログ形式をサポートします．
  * [cpulock](https://github.com/taura/cpulock) は，複数プロセス（マルチスレッドかどうかを問わない）を実行する際に，各プロセスへ CPU セットを排他的に割り当てるユーティリティです．
  * [smart-gnuplotter](https://github.com/taura/smart_gnuplotter) は，大量の gnuplot グラフを簡単に描画するための Python ライブラリで，グラフの多い TeX 論文・スライドの自動生成に便利です．
  * [MassiveLogger](https://github.com/massivethreads/massivelogger) は C で書かれたマルチスレッド向け軽量ロギングライブラリで，[bokeh](https://docs.bokeh.org/en/latest/index.html) 製の専用ビューアが付属します．

## その他

  * [mdoch](https://github.com/qnu/mdoch/) は，Chapel プログラミング言語で分子動力学シミュレーションを書くための進行中プロジェクトであり，Chapel 自体の評価にも役立っています．
