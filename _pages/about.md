---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I joined the School of Computer Science and Technology at Soochow University in 2024, where I am currently an Associate Professor. My research lies at the intersection of information retrieval, natural language processing, and large language models. I am particularly interested in conversational search and retrieval-augmented generation, memory and reasoning for LLM-based agents, long-document retrieval and reranking, legal AI, and efficient and trustworthy LLM systems.

I received my B.S. degree from Xi’an Jiaotong University, my M.S. degree from Xidian University, and my Ph.D. degree from [Université Grenoble Alpes](https://www.univ-grenoble-alpes.fr/), France, where I was advised by Prof. [Eric Gaussier](https://scholar.google.com/citations?user=rCpJslsAAAAJ). If you are interested in academic collaboration, student supervision, or research discussions, please feel free to contact me by [email](mailto:{{ site.author.email }}).


<a class="group-invitation" href="{{ '/group/' | relative_url }}"><span><small>RESEARCH GROUP</small><strong>{{ site.data.group.tagline }}</strong><span>{{ site.data.group.name }} ({{ site.data.group.short_name }})</span></span><span aria-hidden="true">↗</span></a>

# 🔥 News

{% include recent-news.html %}

# 📝 Selected Publications

<small><sup>*</sup> Corresponding author; <sup>†</sup> Co-first author.</small>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge venue-tag">Information Fusion 2026</div>
      <img src='../images/inffusion.png' alt="Dual-Layer Prompt Ensembles" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[Dual-Layer Prompt Ensembles: Leveraging System-and User-Level Instructions for Robust LLM-Based Query Expansion and Rank Fusion](#)

**Minghan Li**<sup>*</sup>, Ercong Nie, Huiping Huang, Xinxuan Lv, Guodong Zhou

*Information Fusion*, 2026 (JCR Q1, CAAI-A journal, IF 17.4)

- Robust query expansion and rank fusion via dual-layer prompt ensembles.

</div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge venue-tag">ACL 2026</div>
      <img src='../images/glier.png' alt="GLIER" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[GLIER: Generative Legal Inference and Evidence Ranking for Legal Case Retrieval](#)

**Minghan Li**<sup>*†</sup>, Tianrui Lv<sup>†</sup>, Chao Zhang, Guodong Zhou

*ACL 2026 Main Conference*

- Generative legal inference and evidence ranking for legal case retrieval.

</div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge venue-tag">ACL 2026</div>
      <img src='../images/s2gRag.png' alt="S2G-RAG" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[S2G-RAG: Structured Sufficiency and Gap Judging for Iterative Retrieval-Augmented QA](#)

**Minghan Li**<sup>*†</sup>, Junjie Zou<sup>†</sup>, Xinxuan Lv, Chao Zhang, Guodong Zhou

*ACL 2026 Main Conference*

- Iterative RAG with structured sufficiency judgment and gap-guided retrieval.

</div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge venue-tag">TOIS 2023</div>
      <img src='../images/KeyB-TOIS.png' alt="TOIS 2023" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[The Power of Selecting Key Blocks with Local Pre-ranking for Long Document Information Retrieval](#)

**Minghan Li**, Diana Nicoleta Popa, Johan Chagnon, Yagmur Gizem Cinar, Eric Gaussier

*ACM Transactions on Information Systems*, 2023 (JCR Q1, **CCF-A journal**, IF 11.2)

- Key-block selection with local pre-ranking for long-document retrieval.

</div>
</div>

## 📚 Conference and Journal Papers

<small><sup>*</sup> Corresponding author; <sup>†</sup> Co-first author.</small>

- <span class="venue-tag">TOIS 2026</span> A Survey of Long-Document Retrieval in the PLM and LLM Era<br>
  <span class="paper-authors">**Minghan Li**<sup>*</sup>, Yishuai Zhang, Tianrui Lv, Siqi Zhao, Miyang Luo, Ercong Nie, Guodong Zhou (JCR Q1, **CCF-A journal**, IF 11.2)</span>
- <span class="venue-tag">TOIS 2026</span> Query Expansion in the Age of Pre-trained and Large Language Models: A Comprehensive Survey<br>
  <span class="paper-authors">**Minghan Li**<sup>*</sup>, Xinxuan Lv, Junjie Zou, Tongna Chen, Chao Zhang, Suchao An, Ercong Nie, Guodong Zhou (JCR Q1, **CCF-A journal**, IF 11.2)</span>
- <span class="venue-tag">Information Fusion 2026</span> Dual-Layer Prompt Ensembles: Leveraging System-and User-Level Instructions for Robust LLM-Based Query Expansion and Rank Fusion<br>
  <span class="paper-authors">**Minghan Li**<sup>*</sup>, Ercong Nie, Huiping Huang, Xinxuan Lv, Guodong Zhou (JCR Q1, CAAI-A journal, IF 17.4)</span>
- <span class="venue-tag">ACL 2026 Main Conference</span> GLIER: Generative Legal Inference and Evidence Ranking for Legal Case Retrieval<br>
  <span class="paper-authors">**Minghan Li**<sup>*†</sup>, Tianrui Lv<sup>†</sup>, Chao Zhang, Guodong Zhou</span>
- <span class="venue-tag">ACL 2026 Main Conference</span> S2G-RAG: Structured Sufficiency and Gap Judging for Iterative Retrieval-Augmented QA<br>
  <span class="paper-authors">**Minghan Li**<sup>*†</sup>, Junjie Zou<sup>†</sup>, Xinxuan Lv, Chao Zhang, Guodong Zhou</span>
- <span class="venue-tag">EMNLP 2026 Main Conference</span> SAGA: Structured Applicability-Guided Alignment for Conversational Legal Retrieval<br>
  <span class="paper-authors">Xinxuan Lv<sup>†</sup>, **Minghan Li**<sup>*†</sup>, Guodong Zhou</span>
- <span class="venue-tag">EMNLP 2026 Main Conference</span> Cascade-SC: A Pareto-Efficient Cross-Model Cascade for Test-Time Reasoning<br>
  <span class="paper-authors">**Minghan Li**<sup>*†</sup>, Siqi Zhao<sup>†</sup>, Luoliang Hua, Guodong Zhou</span>
- <span class="venue-tag">EMNLP 2026 Findings</span> EviRerank: Adaptive Evidence Construction for Long-Document LLM Reranking<br>
  <span class="paper-authors">**Minghan Li**<sup>*</sup>, Eric Gaussier, Juntao Li, Guodong Zhou</span>
- <span class="venue-tag">NLPCC 2026 Conference Oral</span> Retrieval-Feedback Aligned Distillation for Deployable LLM Query Expansion<br>
  <span class="paper-authors">**Minghan Li**, Guodong Zhou</span>
- <span class="venue-tag">AAAI 2026</span> RFKG-CoT: Relation-Driven Adaptive Hop-count Selection and Few-Shot Path Guidance for Knowledge-Aware QA<br>
  <span class="paper-authors">Chao Zhang, **Minghan Li**<sup>*</sup>, Tianrui Lv, Guodong Zhou</span>
- <span class="venue-tag">COLING 2024</span> Domain Adaptation for Dense Retrieval and Conversational Dense Retrieval through Self-Supervision by Meticulous Pseudo-Relevance Labeling<br>
  <span class="paper-authors">**Minghan Li**, Eric Gaussier</span>
- <span class="venue-tag">TOIS 2023</span> The Power of Selecting Key Blocks with Local Pre-ranking for Long Document Information Retrieval<br>
  <span class="paper-authors">**Minghan Li**, Diana Nicoleta Popa, Johan Chagnon, Yagmur Gizem Cinar, Eric Gaussier (JCR Q1, **CCF-A journal**, IF 11.2)</span>
- <span class="venue-tag">SIGIR 2022</span> BERT-based Dense Intra-ranking and Contextualized Late Interaction via Multi-task Learning for Long Document Retrieval<br>
  <span class="paper-authors">**Minghan Li**, Eric Gaussier</span>
- <span class="venue-tag">AAAI 2022</span> Listwise Learning to Rank Based on Approximate Rank Indicators<br>
  <span class="paper-authors">Thibaut Thonet, Yagmur Gizem Cinar, Éric Gaussier, **Minghan Li**, Jean-Michel Renders</span>
- <span class="venue-tag">SIGIR 2021</span> KeyBLD: Selecting Key Blocks with Local Pre-ranking for Long Document Information Retrieval<br>
  <span class="paper-authors">**Minghan Li**, Eric Gaussier</span>
- <span class="venue-tag">ICPR 2020</span> Learning to Rank for Active Learning: A Listwise Approach<br>
  <span class="paper-authors">**Minghan Li**, Xialei Liu, Joost van de Weijer, Bogdan Raducanu</span>

## 🗂 Preprints and Surveys

- `arXiv 2026` Automatic In-Domain Exemplar Construction and LLM-Based Refinement of Multi-LLM Expansions for Query Expansion, **Minghan Li**, Ercong Nie, Siqi Zhao, Tongna Chen, Huiping Huang, Guodong Zhou
- `arXiv 2026` GenState-AI: State-Aware Dataset for Text-to-Video Retrieval on AI-Generated Videos, **Minghan Li**, Tongna Chen, Tianrui Lv, Yishuai Zhang, Suchao An, Guodong Zhou
- `arXiv 2026` Retrieval-Feedback-Driven Distillation and Preference Alignment for Efficient LLM-based Query Expansion, **Minghan Li**, Guodong Zhou
- `arXiv 2025` Enhanced Retrieval of Long Documents: Leveraging Fine-Grained Block Representations with Large Language Models, **Minghan Li**, Eric Gaussier, Guodong Zhou

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 📖 Educations
- Ph.D. in Computer Science, Université Grenoble Alpes, France.
- M.S. in Computer Technology, [Xidian University](https://en.xidian.edu.cn/), China.
- B.E. in Information Engineering, [Xi’an Jiaotong University](https://en.xjtu.edu.cn/), China. -->

# 💰 Research Grants

- National Natural Science Foundation of China (NSFC) grant: **Research on Causality-Enhanced Memory Mechanisms for Long-Term Conversational Agents**, **Principal Investigator**.
- Soochow University Academic Start-up Fund, **Principal Investigator**.
- *2023* — **Domain Transfer for Conversational Search**, IDEX Université Grenoble Alpes, for a research visit to the National University of Singapore (NUS), **Principal Investigator**.

# 📖 Educations
- Ph.D. in Computer Science, <img src="../images/uga.png" width="18" style="vertical-align:middle;"> [Université Grenoble Alpes](https://www.univ-grenoble-alpes.fr/), France.
- M.S. in Computer Technology, <img src="../images/xidian.png" width="18" style="vertical-align:middle;"> [Xidian University](https://en.xidian.edu.cn/), China.
- B.S. in Information Engineering, <img src="../images/xjtu.jpg" width="18" style="vertical-align:middle;"> [Xi’an Jiaotong University](https://en.xjtu.edu.cn/), China.

<div style="text-align: center; margin: 2em 0;">
  <script type="text/javascript" id="mapmyvisitors" src="//mapmyvisitors.com/map.js?d=R-I7z2n6MSwVEribHa1-rRgzE-ZtESbqU188cHjuTs8&amp;cl=ffffff&amp;w=300"></script>
</div>

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
