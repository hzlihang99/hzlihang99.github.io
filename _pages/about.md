---
permalink: /
title: "Hang Li"
excerpt: "Hang Li — Ph.D. candidate in Computer Science at Michigan State University"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Ph.D. candidate in Computer Science at **Michigan State University**, advised by [Prof. Jiliang Tang](https://www.cse.msu.edu/~tangjili/) in the [Data Science and Engineering (DSE) Lab](https://dse.cse.msu.edu/). I also work closely with Prof. Hui Liu. My research is on **large language models (LLMs) and LLM-based multi-agent systems**, with a focus on making them **reliable for education**. I study how LLMs reason and where they fail, and I build systems for automated grading, error diagnosis and teacher professional development.

I have published in venues including **ACL, EMNLP, AAAI/IAAI, IJCAI, WWW, TMLR, ICASSP, INTERSPEECH, AIED** and **EDM**, and my work has been cited more than 2,000 times ([Google Scholar](https://scholar.google.com/citations?user=25Vx5UIAAAAJ&hl=en)). Our work on LLM-based knowledge tagging received the **IAAI 2025 Innovative Application Award**. I helped design and write three grant proposals with Prof. Tang: two funded by the **NSF** and one by the **Gates Foundation**.

I was a research intern at **Capital One** (2026) and **Squirrel AI Learning** (2024). Before my Ph.D., I was a Machine Learning Scientist at **TAL Education Group**, building multimodal learning systems for online classrooms. I hold an M.S. in Statistics from the **University of Illinois Urbana-Champaign** and a B.S. in Information and Computing Science from **Beijing Jiaotong University**.

<p class="contact-line">
<i class="fas fa-envelope" aria-hidden="true"></i> lihang4 [at] msu [dot] edu &nbsp;·&nbsp;
<a href="/files/HangLi_CV.pdf"><i class="fas fa-file-pdf" aria-hidden="true"></i> CV (PDF)</a>
</p>

## Research Interests

<div class="research-grid">
  <div class="research-card">
    <h3>Reliable LLMs for Assessment</h3>
    <p>LLM-based automated grading that is accurate, calibrated and robust: rubric and demonstration optimization, uncertainty quantification, human-in-the-loop grading, and prompt injection attacks on graders.</p>
  </div>
  <div class="research-card">
    <h3>LLM Reasoning &amp; Multi-Agent Systems</h3>
    <p>How LLMs solve problems and detect errors: solution divergence, conformity bias and prompt optimization for long-context reasoning. Multi-agent systems for knowledge tagging and teacher professional development.</p>
  </div>
  <div class="research-card">
    <h3>Machine Learning on Graphs</h3>
    <p>Diffusion models on graphs, LLMs for learning on graphs, graph representation learning, and graph-based retrieval and generation.</p>
  </div>
  <div class="research-card">
    <h3>Multimodal Learning</h3>
    <p>Audio-and-language pre-training and multimodal representation learning for speech, emotion and classroom understanding.</p>
  </div>
</div>

## News

<ul class="news">
  <li><span class="news__date">Oct 2026</span> Invited talk on LLM-driven multi-agent systems for teacher professional development at the Department of Educational Psychology, University of Georgia.</li>
  <li><span class="news__date">2026</span> Two first-author papers accepted to <strong>Findings of EMNLP 2026</strong>: <a href="https://arxiv.org/abs/2606.03090">prompt injection attacks on LLM graders</a> and <a href="https://arxiv.org/abs/2509.22480">solution divergence in LLM problem solving</a>.</li>
  <li><span class="news__date">2026</span> <em>MEMO</em>, on prompt optimization for long-context reasoning, accepted to the <strong>NeurIPS 2026</strong> Workshop on Test-time Continual Learning Agents.</li>
  <li><span class="news__date">Jun 2026</span> Started a research internship at <strong>Capital One</strong> (June–August 2026).</li>
  <li><span class="news__date">Jun 2026</span> Two oral presentations at <strong>AIED 2026</strong>, including our multi-agent system <em>i-VIP</em>.</li>
  <li><span class="news__date">2025</span> Our knowledge tagging paper received the <strong>IAAI 2025 Innovative Application Award</strong>.</li>
  <li><span class="news__date">2025</span> A proposal I co-designed and drafted on AI long-form grading was funded by the <strong>Gates Foundation</strong>.</li>
  <li><span class="news__date">Jun 2025</span> Gave a tutorial on <em>Bringing GenAI to Education</em> and co-organized the GenAI4EDU workshop at <strong>EDM 2025</strong>.</li>
  <li><span class="news__date">2025</span> <em>Ask-Before-Detection</em> accepted to <strong>ACL 2025</strong>.</li>
</ul>

## Selected Publications

<p class="section-note">* denotes equal contribution. Full list on the <a href="/publications/">publications page</a>.</p>

<ul class="pub-list">{% for p in site.data.publications %}{% if p.selected %}{% include pub-item.html pub=p %}{% endif %}{% endfor %}</ul>

## Honors & Awards

- **IAAI Innovative Application Award**, AAAI/IAAI 2025
- **2nd Place**, OGB-LSC Node Classification Track, NeurIPS 2022
- **1st Place** (Task 3) and **2nd Place** (Task 4 & overall), NeurIPS 2020 Education Challenge
- **2nd Place**, ClariQ Challenge (Clarifying Questions for Dialogue), EMNLP 2020
- **1st Place**, STABILO Time-Series Classification Challenge, ACM UbiComp 2020

## Media Coverage

- [A new equation for teacher + student success](https://rossier.usc.edu/news-insights/news/new-equation-teacher-student-success), USC Rossier School of Education
- [A new spin on AI offers more PD opportunities for elementary math teachers](https://engineering.msu.edu/news/new-spin-ai-offers-more-pd-opportunities-elementary-math-teachers), MSU College of Engineering, 2024
- [MSU studying AI use in elementary math education](https://www.wilx.com/2024/10/15/mid-michigan-matters-msu-studying-ai-use-elementary-math-education/) (video), WILX News 10, 2024
