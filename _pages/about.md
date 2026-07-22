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

I am a first-year Ph.D. student in Computer Science at the [University of California, Santa Barbara](http://nlp.cs.ucsb.edu), advised by Prof. [Xin (Eric) Wang](https://eric-xw.github.io). 
I received my M.S. in Computer Science from the University of Southern California, where I was honored with the **Best Computer Science Research Award**. 
Prior to that, I earned my B.E. in Software Engineering from Tsinghua University and graduated with the distinction of **Outstanding Undergraduate**.

At USC, I was fortunate to be advised by Prof. [Jieyu Zhao](https://jyzhao.net) and Prof. [Kuan-Hao Huang](https://khhuang.me).

My research interests primarily lie in **multimodal learning** and **AI agents**. Recently, I have been particularly interested in improving the **fine-grained reasoning capabilities of multimodal models** and in developing **open-ended self-improving agents**.

# 😊 Collaboration
I’m always excited to collaborate on research projects. If you are a PhD student or researcher and think our interests align, feel free to reach out via email!

I’m also happy to mentor undergraduate and master’s students interested in research. If you are interested in working together, please don’t hesitate to contact me by email.





# 🔥 News
- **2026.06**: &nbsp;🎉🎉 I’ve joined Amazon as an Applied Scientist Intern, working on self-improving AI and agents. Excited for the opportunity and looking forward to a great summer!
- **2026.01**: &nbsp;🎉🎉 one paper accepted at <span style="color:#a32020; font-weight:700;">EACL 2026 as an Oral Presentation!</span> Check [What's Missing in Vision-Language Models? Probing Their Struggles with Causal Order Reasoning](https://arxiv.org/abs/2506.00869) for more details!
- **2025.09**: Started my Ph.D. in Computer Science at UCSB.
- **2024.05**: &nbsp;🎉🎉 Honored to receive the <span style="color:#a32020; font-weight:700;">Best Computer Science Research Award</span> at USC.

# 📝 Selected Publications

<style>
.pub { display:flex; gap:18px; align-items:flex-start; margin:0 0 26px; }
.pub-media { flex:0 0 300px; max-width:300px; }
.pub-media img, .pub-media video { width:100%; border:1px solid #e2e2e2; border-radius:8px; display:block; }
.pub-body { flex:1 1 auto; min-width:0; }
.pub-title { font-size:1.08em; font-weight:700; line-height:1.35; }
.pub-authors { margin:4px 0 3px; }
.pub-venue { font-weight:700; color:#a32020; }
.pub-venue.preprint { color:#666; }
.pub-links { margin-top:5px; font-size:0.95em; }
.pub-links a { text-decoration:none; }
@media (max-width:640px){
  .pub { flex-direction:column; gap:10px; }
  .pub-media { flex-basis:auto; max-width:100%; }
}
</style>

<div class="pub">
  <div class="pub-media">
    <video src="{{ '/images/COLM2026.mp4' | relative_url }}" muted autoplay loop playsinline controls></video>
  </div>
  <div class="pub-body">
    <div class="pub-title">Group-Evolving Agents: Open-Ended Self-Improvement via Experience Sharing</div>
    <div class="pub-authors"><strong>Zhaotian Weng</strong>, Antonis Antoniades, Deepak Nathani, Zhen Zhang, Sophia Xiao Pu, Xin (Eric) Wang</div>
    <div class="pub-venue">COLM 2026</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2602.04837">Paper</a> · <a href="https://group-evolving-agents.github.io/">Website</a> · <a href="https://venturebeat.com/orchestration/new-agent-framework-matches-human-engineered-ai-systems-and-adds-zero">VentureBeat</a> · <a href="https://x.com/wengzhaoti39773/status/2077063215826301438">X</a> · <a href="https://x.com/xwang_lk/status/2019454179400642788">X</a></div>
  </div>
</div>

<div class="pub">
  <div class="pub-media">
    <img src="{{ '/images/LVM2026.jpg' | relative_url }}" alt="Length Value Model teaser">
  </div>
  <div class="pub-body">
    <div class="pub-title">Length Value Model: Scalable Value Pretraining for Token-Level Length Modeling</div>
    <div class="pub-authors">Zhen Zhang, Changyi Yang, Zijie Xia, Zhen Yang, Chengzhi Liu, <strong>Zhaotian Weng</strong>, Yepeng Liu, Haobo Chen, Jin Pan, Chenyang Zhao, Yuheng Bu, Alkesh Patel, Zhe Gan, Xin Eric Wang</div>
    <div class="pub-venue">COLM 2026</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2604.27039">Paper</a></div>
  </div>
</div>

<div class="pub">
  <div class="pub-media">
    <img src="{{ '/images/EACL2026.jpg' | relative_url }}" alt="EACL 2026 paper figure">
  </div>
  <div class="pub-body">
    <div class="pub-title">What's Missing in Vision-Language Models? Probing Their Struggles with Causal Order Reasoning</div>
    <div class="pub-authors"><strong>Zhaotian Weng</strong>, Haoxuan Li, Xin (Eric) Wang, Kuan-Hao Huang, Jieyu Zhao</div>
    <div class="pub-venue">EACL 2026 (Oral)</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2506.00869">Paper</a></div>
  </div>
</div>

<div class="pub">
  <div class="pub-media">
    <img src="{{ '/images/EMNLP2024.jpg' | relative_url }}" alt="EMNLP 2024 paper figure">
  </div>
  <div class="pub-body">
    <div class="pub-title">Images Speak Louder than Words: Understanding and Mitigating Bias in Vision-Language Models from a Causal Mediation Perspective</div>
    <div class="pub-authors"><strong>Zhaotian Weng</strong>, Zijun Gao, Jerone Andrews, Jieyu Zhao</div>
    <div class="pub-venue">EMNLP 2024</div>
  </div>
</div>

<div class="pub">
  <div class="pub-media">
    <img src="{{ '/images/Heuresis.jpg' | relative_url }}" alt="Heuresis teaser">
  </div>
  <div class="pub-body">
    <div class="pub-title">Heuresis: Search Strategies for Autonomous AI Research Agents Across Quality, Diversity and Novelty</div>
    <div class="pub-authors">Antonis Antoniades, Deepak Nathani, Ritam Saha, Alfonso Amayuelas, Ivan Bercovich, <strong>Zhaotian Weng</strong>, Vignesh Baskaran, Kunal Bhatia, William Yang Wang</div>
    <div class="pub-venue preprint">arXiv preprint</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2606.25198">Paper</a></div>
  </div>
</div>

<div class="pub">
  <div class="pub-media">
    <img src="{{ '/images/Survive.jpg' | relative_url }}" alt="Survive or Collapse teaser">
  </div>
  <div class="pub-body">
    <div class="pub-title">Survive or Collapse: The Asymmetric Roles of Data Gating and Reward Grounding in Self-Play RL</div>
    <div class="pub-authors">Sophia Xiao Pu, <strong>Zhaotian Weng</strong>, Chengzhi Liu, Jayanth Srinivasa, Gaowen Liu, William Yang Wang, Xin Eric Wang</div>
    <div class="pub-venue preprint">arXiv preprint</div>
    <div class="pub-links"><a href="https://arxiv.org/abs/2605.22217">Paper</a></div>
  </div>
</div>


# 🎖 Honors and Awards

- **Best Computer Science Research Award**, University of Southern California
- **Outstanding Undergraduate Graduate Honor**, Tsinghua University
- **Scholarships:** Academic Excellence; Scientific Research Excellence; Sports Excellence (Tsinghua University)
- **Competitions:** 1st prize, National College Students Physics Competition (2020); Honorable Mention, MCM (2022); 1st prize, Tsinghua University Software Development Competition


# 🎓 Education

- **University of California, Santa Barbara**  
  Ph.D. in Computer Science, *Sep. 2025 – Present*  
  Advisor: Prof. Xin (Eric) Wang

- **University of Southern California**  
  M.S. in Computer Science, *Aug. 2023 – May. 2025*  
  Advisors: Prof. Jieyu Zhao, Prof. Kuan-Hao Huang  
  Honor: **Best Computer Science Research Award**

- **Tsinghua University**  
  B.Eng. in Software Engineering, *Sep. 2019 – Jun. 2023*  
  Honor: **Outstanding Undergraduate Graduate Honor**

# 📘 Teaching

- **Teaching Assistant**, CS 16: Problem Solving (C++)  
  University of California, Santa Barbara, Winter 2026

- **Course Producer**, CSCI 585: Database Systems  
  University of Southern California, Fall 2024

# 🧑‍⚖️ Service

- **Conference Reviewer**: EMNLP 2024, ARR 2024 (August, October, December), ACL 2025, EMNLP 2025, ARR 2025 October.
- **Conference Volunteer**: EMNLP 2024


# 💻 Internships
- **Machine Learning Engineer**, MockAI  
  Los Angeles, CA · *Feb. 2024 – May. 2024*
