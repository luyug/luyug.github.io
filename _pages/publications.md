---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



* Modularized transfomer-based ranking framework
**Luyu Gao**, Zhuyun Dai, and Jamie Callan 
In Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing

* Improving Target-side Lexical Transfer in Multilingual Neural Machine Translation
**Luyu Gao**, Xinyi Wang, Graham Neubig
Findings of the 2020 Conference on Empirical Methods in Natural Language Processing

* Understanding BERT rankers under distillation
**Luyu Gao**, Zhuyun Dai, and Jamie Callan. 
In Proceedings of the 2020 ACM SIGIR International Conference on the Theory of Information Retrieval. **Best Short Paper**

* EARL: Speedup transformer-based rankers with pre-computed representation
**Luyu Gao**, Zhuyun Dai, and Jamie Callan 
arXiv:2004.13313. 2020.

* Complementing lexical retrieval with semantic residual embedding
**Luyu Gao**, Zhuyun Dai, Zhen Fan, and Jamie Callan 
arXiv:2004.13969. 2020.



