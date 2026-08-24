---
permalink: /
title: "Jiajun Yu"
author_profile: true
classes: home-page
redirect_from:
  - /about/
  - /about.html
---

> **Jiajun Yu**<br />
> <i class="fa fa-envelope" aria-hidden="true"></i> [jiajunyu@zju.edu.cn](mailto:jiajunyu@zju.edu.cn) &nbsp;|&nbsp; <i class="fa fa-phone" aria-hidden="true"></i> +86 13031180113 &nbsp;|&nbsp; <i class="fa fa-graduation-cap" aria-hidden="true"></i> [Google Scholar](https://scholar.google.com/citations?user=tCtMGUAAAAAJ) &nbsp;|&nbsp; <i class="fa fa-map-marker" aria-hidden="true"></i> Shanghai, China

## <i class="fa fa-user-circle" aria-hidden="true"></i> Summary

I am a second-year Ph.D. student jointly trained by Zhejiang University and Shanghai Innovation Institute. My research focuses on **AI for Science**, large language models (LLMs), and graph neural networks (GNNs), with recent work on LLM agents, scientific idea generation, molecular optimization, virtual screening, molecular property prediction, structure prediction, and protein-protein interaction (PPI) prediction. I also have strong large-scale data engineering and model training experience, including building TB-scale datasets from scratch and training and evaluating models on billions of examples.

---

## <i class="fa fa-briefcase" aria-hidden="true"></i> Professional Experience

<div class="experience-list">
  <div class="experience-item">
    <div class="experience-time">2024.08 - 2024.12</div>
    <div class="experience-body">
      <div class="experience-company">Ant Group / Alipay</div>
      <div class="experience-role">Algorithm Intern · Shanghai</div>
      <ul>
        <li>Fine-tuned Llama 3.1, Qwen 2.5, GLM-4, and DeepSeek for QA extraction in an employee assistant scenario; the system was shipped to production and led to a SIGIR 2026 paper.</li>
        <li>Designed an entity-extraction-based RAG algorithm that improved multi-task QA extraction performance and led to an ACL 2025 paper.</li>
      </ul>
    </div>
  </div>

  <div class="experience-item">
    <div class="experience-time">2023.06 - 2023.12</div>
    <div class="experience-body">
      <div class="experience-company">CUHK-Shenzhen / Shenzhen Institute of Big Data</div>
      <div class="experience-role">Research Intern</div>
      <ul>
        <li>Improved readout functions for molecular property prediction from a kernel-method perspective, leading to an IJCAI 2024 paper.</li>
      </ul>
    </div>
  </div>

  <div class="experience-item">
    <div class="experience-time">2021.03 - 2021.09</div>
    <div class="experience-body">
      <div class="experience-company">Kuaishou Technology</div>
      <div class="experience-role">Algorithm Intern · Beijing</div>
      <ul>
        <li>Led data collection and maintenance for multimodal video retrieval algorithms.</li>
        <li>Built a news short-video generation pipeline from scratch, including 100 million Chinese image pairs and 5 million video-text pairs.</li>
        <li>Participated in the TRECVID 2021 video retrieval track; the team won second place.</li>
      </ul>
    </div>
  </div>
</div>

---

## <i class="fa fa-university" aria-hidden="true"></i> Education

<div class="education-list">
  <div class="education-item">
    <div class="education-time">2024.09 - 2028.03</div>
    <div class="education-body">
      <div class="education-school">Zhejiang University & Shanghai Innovation Institute</div>
      <div class="education-degree">Ph.D. in Artificial Intelligence</div>
      <div class="education-note">Advisors: Prof. Haishuai Wang and Associate Prof. Yu Kang.</div>
    </div>
  </div>

  <div class="education-item">
    <div class="education-time">2021.09 - 2024.06</div>
    <div class="education-body">
      <div class="education-school">China Agricultural University</div>
      <div class="education-degree">M.Sc. in Computer Science and Technology</div>
      <div class="education-note">Recipient of the National Scholarship twice (top 0.2%).</div>
    </div>
  </div>

  <div class="education-item">
    <div class="education-time">2017.08 - 2021.05</div>
    <div class="education-body">
      <div class="education-school">China Agricultural University</div>
      <div class="education-degree">B.Sc. in Computer Science and Technology</div>
      <div class="education-note">Team leader of the university's first MCM/ICM Finalist team in 2020.</div>
    </div>
  </div>
</div>

---

## <i class="fa fa-file-text" aria-hidden="true"></i> Publications

> `*` and `+` denote co-first author and corresponding author, respectively.

{% for section in site.data.publications.sections %}
### {{ section.title }}

<div class="publication-list">
{% for paper in section.items %}
  <div class="publication-item{% if section.title contains 'First-Author' %} primary-paper{% endif %}">
    <div class="publication-topline">
      <span class="publication-venue">{{ paper.venue }}</span>
      {% if paper.note %}<span class="publication-rank{% if paper.note contains 'Q1' or paper.note contains 'Under review' or paper.note contains 'preprint' %} muted{% endif %}">{{ paper.note }}</span>{% endif %}
    </div>
    <div class="publication-title">{{ paper.title }}</div>
    <div class="publication-authors">{{ paper.authors | replace: '**Jiajun Yu**', '<strong>Jiajun Yu</strong>' | replace: '**Jiajun Yu***', '<strong>Jiajun Yu</strong>*' }}</div>
  </div>
{% endfor %}
</div>

{% endfor %}

---

## <i class="fa fa-trophy" aria-hidden="true"></i> Honors and Awards

- Young Science and Technology Talent Development Program, Ph.D. Track, CAST, 2025.
- Bronze Award, Stanford RNA 3D Folding Competition 2025 (89/1,489).
- National Scholarship (2022, 2023).
- Outstanding Student Award, China Agricultural University (2022, 2023).
- First-Class Graduate Scholarship (2022, 2023).
- Finalist, MCM/ICM 2020.
- First Prize, Minsheng Cup Mathematical Modeling Competition 2019.
- First Prize, National Undergraduate Mathematical Contest in Modeling, Beijing Division, 2019.
- Honorable Mention, MCM/ICM 2019.

---

## <i class="fa fa-handshake-o" aria-hidden="true"></i> Academic Service

Reviewer for KDD 2025-2026, WWW 2025-2026, AAAI 2026, ICML 2024-2026, IJCAI 2025-2026, ICLR 2025-2026, NeurIPS 2024-2026, ACM MM 2024-2026, *Pattern Recognition*, *Neural Networks*, *Knowledge-Based Systems*, and *Neurocomputing*.

<div class="notice--info">
  <strong><i class="fa fa-bar-chart" aria-hidden="true"></i> Visitor Stats:</strong>
  <span class="busuanzi_container_page_pv">This page <span id="busuanzi_value_page_pv"></span> views</span>
  &nbsp;|&nbsp;
  <span class="busuanzi_container_site_pv">Site total <span id="busuanzi_value_site_pv"></span> views</span>
  &nbsp;|&nbsp;
  <span class="busuanzi_container_site_uv"><span id="busuanzi_value_site_uv"></span> visitors</span>
</div>
