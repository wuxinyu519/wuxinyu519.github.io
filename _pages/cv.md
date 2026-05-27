---
layout: archive
title: "About Me"
permalink: /
author_profile: true
redirect_from:
  - /cv
---

{% include base_path %}

I am currently a Ph.D. student in the Department of Computer Science at Baylor University, under the supervision of [**Dr. Chen Zhao**](https://charliezhaoyinpeng.github.io/homepage/). Prior to this, I received my M.S. in Artificial Intelligence from Dongguk University (DGU), South Korea, in March 2024, under the guidance of [Prof. Hyerung Jang](https://sites.google.com/view/hrjang/home). My research focuses on generative modeling, image synthesis and reconstruction, AI-generated content detection, explainable artificial intelligence, and computational pathology. My work has been published or accepted by venues including IJCAI, TMLR, KAIS, and Expert Systems with Applications.

Outside of my academic life, I have a cat named Taurus, who has accompanied me across South Korea, China, and the United States. I also enjoy watching comedy series, learning new hobbies, and swimming.

<style>
  .news-update {
    color: #d93025;
    font-size: 0.72em;
    animation: news-pulse 1.4s ease-in-out infinite;
  }

  @keyframes news-pulse {
    0%, 100% {
      opacity: 1;
    }
    50% {
      opacity: 0.35;
    }
  }
</style>

<h2>News <span class="news-update">[Update!]</span></h2>

{% assign current_year = site.time | date: "%Y" %}
{% assign current_news = site.data.news | where: "year", current_year %}

{% for item in current_news %}
- [{{ item.date }}] {{ item.text }}
{% endfor %}

Research Interests
======
- Representation Learning with Generative Models  
- Optimization in Generative Modeling  
- Image Synthesis and Reconstruction  
- Deepfake and AI-generated Content Detection  
- Explainable Artificial Intelligence (XAI)

Education
======
* Ph.D. in Computer Science, Baylor University (September 2024 – Present)
* M.S. in Artificial Intelligence, Dongguk University (September 2021 – March 2024)
* B.S. in Computer Science, Xinyu College (September 2017 – June 2021)

Work experience
======
* Spring 2024: [**HITS (에이치아이티에스)**](http://highimage.co.kr/)
  * Object detection
  * Semi-conductor packing
  <!-- * <ul http://highimage.co.kr/ > -->

* Summar 2023: [**Asleep (Internship)**](https://www.asleep.ai/en/company)
  * Time-series based prediction
  * Sleep stage dection

  
Skills
======
* Torch/Tensorfloww
* Python
