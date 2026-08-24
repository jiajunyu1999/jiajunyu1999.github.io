---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

I am a Ph.D. student jointly trained by Zhejiang University and Shanghai Innovation Institute, working on AI for Science, large language models, and graph neural networks.

[Download Chinese CV (PDF)]({{ base_path }}/files/Jiajun_Yu_中文简历_优化版.pdf){: .btn .btn--primary}

Education
======
* **Zhejiang University & Shanghai Innovation Institute** — Ph.D. in Artificial Intelligence, 2024.09-2028.03. Advisors: Prof. Haishuai Wang and Associate Prof. Yu Kang.
* **China Agricultural University** — M.Sc. in Computer Science and Technology, 2021.09-2024.06. National Scholarship recipient twice (top 0.2%).
* **China Agricultural University** — B.Sc. in Computer Science and Technology, 2017.08-2021.05. Team leader of the university's first MCM/ICM Finalist team.

Research interests
======
* AI for Science, LLM agents, scientific idea generation, molecular optimization, virtual screening, molecular and structure prediction, and protein-protein interaction prediction.
* Graph neural networks, graph learning, retrieval-augmented generation, and large-scale data engineering.

Work experience
======
* **Shanghai Artificial Intelligence Laboratory**, Life Science Foundation Model Intern, 2025.02-2025.09
* **Ant Group / Alipay**, Algorithm Intern, 2024.08-2024.12
* **CUHK-Shenzhen / Shenzhen Institute of Big Data**, Research Intern, 2023.06-2023.12
* **Kuaishou Technology**, Algorithm Intern, 2021.03-2021.09

Honors and awards
======
* CAST Young Science and Technology Talent Development Program, Ph.D. Track (2025)
* Bronze Award, Stanford RNA 3D Folding Competition (2025; 89/1,489)
* National Scholarship (2022, 2023)
* MCM/ICM Finalist (2020); Minsheng Cup Mathematical Modeling Competition First Prize (2019)

Publications
======
`*` and `+` denote co-first author and corresponding author, respectively.

{% for section in site.data.publications.sections %}
## {{ section.title }}

{% for paper in section.items %}
{{ forloop.index }}. {{ paper.authors | markdownify | remove: '<p>' | remove: '</p>' }}. **{{ paper.title }}** {{ paper.venue }}{% if paper.note %} ({{ paper.note }}){% endif %}.
{% endfor %}

{% endfor %}

Academic service
======
Reviewer for KDD, WWW, AAAI, ICML, IJCAI, ICLR, NeurIPS, ACM MM, Pattern Recognition, Neural Networks, Knowledge-Based Systems, and Neurocomputing.
