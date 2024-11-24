---
layout: post
title: 完全グラフ
cover-img: /assets/img/graph-header.png
thumbnail-img: /assets/img/graph-thumb.png
share-img: /assets/img/graph-thumb.png
tags: [グラフ]
mathjax: true
---


完全グラフとは, 有限集合$V$に対して$(V,\binom{V}{2})$で表されるグラフを指します. 多くの文献では$n$頂点の完全グラフは$K_n$で表記されます.

## 性質
- $n$頂点の完全グラフは$(n-1)$-正則です.
  - 特に完全グラフ上の単純ランダムウォークの定常分布は頂点集合$V$上の一様分布となります.
- 隣接行列$A$は対角成分が全て$0$で残りの成分は全て$1$となります.