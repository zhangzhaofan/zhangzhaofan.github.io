---
layout: page
title: "Adaptive-Critical"
description: "Identifying Critical States for Risk-Sensitive Navigation via Distributional Reinforcement Learning"
permalink: /projects/adaptive-critical/
nav: false
---

<!-- _pages/adaptive_critical.md：Adaptive-Critical 项目详情页 -->

<div class="project-page">
  <!-- 作者 / 会议 -->
  <p class="text-center author-line">
    <a href="https://scholar.google.com/citations?user=ssxvQwcAAAAJ&hl=en"><strong>Zhaofan Zhang</strong></a>,
    <a href="https://sihongxie.github.io/">Sihong Xie</a>&dagger;,
    <a href="https://scholar.google.com/citations?hl=zh-CN&user=cVDF1tkAAAAJ">Hui Xiong</a>&dagger;
  </p>
  <p class="text-center venue-line"><em>IROS, 2026</em></p>

  <!-- 链接按钮 -->
  <div class="publications">
    <div class="links text-center">
      <a href="#" class="btn btn-sm z-depth-0" role="button">Paper</a>
      <a href="#" class="btn btn-sm z-depth-0" role="button">arXiv</a>
      <a href="#" class="btn btn-sm z-depth-0" role="button">Code</a>
      <a href="#" class="btn btn-sm z-depth-0" role="button">Video</a>
    </div>
  </div>
</div>

<!-- 主图 -->
<div class="row justify-content-center mt-4">
  <div class="col-md-9">
    <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/projects/adaptive-critical-intro.png' | relative_url }}" alt="Adaptive-Critical overview" />
  </div>
</div>
<div class="caption">
  Adaptive-Critical performs risk-sensitive navigation by adapting its conservatism to state-dependent criticality signals
  estimated from a distributional value function, rather than relying on a fixed risk heuristic.
</div>

## Abstract

Adaptive-Critical is a state-dependent risk-sensitive framework that transcends fixed heuristics by integrating
distributional criticality signals with sensory cues, enabling robust navigation under partial observability and
environmental uncertainty. By estimating the full return distribution, the agent identifies decision-critical states
where errors are most costly and modulates its risk preference accordingly, yielding safer trajectories without
sacrificing efficiency in benign regions.

<!-- 视频(可选):把视频放到 assets/video/projects/ 下,取消下面注释并改文件名
<div class="row justify-content-center mt-4">
  <div class="col-md-9">
    {% include video.liquid path="assets/video/projects/adaptive-critical-demo.mp4" class="img-fluid rounded z-depth-1" controls=true %}
  </div>
</div>
-->

## BibTeX

{% raw %}

```bibtex
@inproceedings{zhang2026adaptivecritical,
  title     = {Adaptive-Critical: Identifying Critical States for Risk-Sensitive Navigation via Distributional Reinforcement Learning},
  author    = {Zhang, Zhaofan and Xie, Sihong and Xiong, Hui},
  booktitle = {IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  year      = {2026},
}
```

{% endraw %}
