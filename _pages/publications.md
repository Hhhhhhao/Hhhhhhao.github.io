---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 2
---
<!-- _pages/publications.md -->

#### Preprints

- ControlVAR: Exploring Controllable Visual Autoregressive Modeling. Xiang Li, Kai Qiu, Hao Chen, Jason Kuen, Zhe Lin, Rita Singh, Bhiksha Raj. [[arxiv](https://arxiv.org/abs/2406.09750)]
- Slight Corruption in Pre-training Data Makes Better Diffusion Models. Hao Chen, Yujin Han, Diganta Misra, Xiang Li, Kai Hu, Difan Zou, Masashi Sugiyama, Jindong Wang, Bhiksha Raj. [[arxiv](https://arxiv.org/abs/2405.20494)]
- RTGen: Generating Region-Text Pairs for Open-Vocabulary Object Detection. Fangyi Chen, Han Zhang, Zhantao Yang, Hao Chen, Kai Hu, Marios Savvides. [[arxiv](https://arxiv.org/abs/2405.19854)]
- AgentReview: Exploring Peer Review Dynamics with LLM Agents. Yiqiao Jin, Qinlin Zhao, Yiyang Wang, Hao Chen, Kaijie Zhu, Yijia Xiao, Jindong Wang. [[arxiv](https://arxiv.org/abs/2406.12708)]
- Learning with Noisy Foundation Models. Hao Chen, Jindong Wang, Zihan Wang, Ran Tao, Hongxin Wei, Xing Xie, Masashi Sugiyama, Bhiksha Raj. [[arxiv](https://arxiv.org/abs/2403.06869)]
- Imprecise label learning: A unified framework for learning with various imprecise label configurations. Hao Chen, Ankit Shah, Jindong Wang, Ran Tao, Yidong Wang, Xing Xie, Masashi Sugiyama, Rita Singh, Bhiksha Raj. [[arxiv](https://arxiv.org/abs/2305.12715)]


#### Papers

<div class="publications">

{% for y in page.years %}
  <div>{{y}}</div>
  {% bibliography -f pubs -q @*[year={{y}}]* %}
{% endfor %}

</div>
