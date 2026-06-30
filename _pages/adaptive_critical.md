---
layout: project
title: "Adaptive-Critical: Identifying Critical States for Risk-Sensitive Navigation via Distributional Reinforcement Learning"
description: ""
permalink: /projects/adaptive-critical/
nav: false
---

<!-- _pages/adaptive_critical.md：Adaptive-Critical 项目详情页（居中式学术项目页，参照 FLUX 风格） -->

<style>
  /* 标题与整页居中 */
  .post-header {
    text-align: center;
  }
  .post-header .post-title {
    font-size: 1.9rem;
    line-height: 1.3;
    margin: 0 auto;
    max-width: 60rem;
  }
  .project-page {
    max-width: 60rem;
    margin: 0 auto;
  }
  .project-page .authors {
    font-size: 1.15rem;
    margin-bottom: 0.4rem;
  }
  .project-page .authors a {
    color: var(--global-theme-color);
  }
  .project-page .affiliations,
  .project-page .corr {
    color: var(--global-text-color-light);
    margin-bottom: 0.3rem;
  }
  .project-page .venue {
    margin-top: 0.6rem;
    margin-bottom: 1.2rem;
  }
  /* 链接按钮居中 */
  .project-page .project-links {
    text-align: center;
    margin-bottom: 1rem;
  }
  .project-page .project-links a.btn {
    margin: 0.2rem 0.15rem;
  }
  /* 分节标题居中 + 分隔线 */
  .project-page h2 {
    text-align: center;
    margin-top: 2.5rem;
    margin-bottom: 1rem;
  }
  .project-page .section-text {
    text-align: justify;
  }
  /* BibTeX + Copy 按钮 */
  .bibtex-box {
    position: relative;
    text-align: left;
  }
  .bibtex-box pre {
    background-color: var(--global-code-bg-color);
    border-radius: 8px;
    padding: 1rem;
    overflow-x: auto;
  }
  .bibtex-box .copy-btn {
    position: absolute;
    top: 0.5rem;
    right: 0.5rem;
  }
</style>

<div class="project-page">
  <!-- 作者 -->
  <p class="authors">
    <a href="https://scholar.google.com/citations?user=ssxvQwcAAAAJ&hl=en">Zhaofan Zhang</a><sup>1</sup>,
    <a href="https://sihongxie.github.io/">Sihong Xie</a><sup>1,&#9993;</sup>,
    <a href="https://scholar.google.com/citations?hl=zh-CN&user=cVDF1tkAAAAJ">Hui Xiong</a><sup>1,&#9993;</sup>
  </p>
  <!-- 机构 -->
  <p class="affiliations"><sup>1</sup> The Hong Kong University of Science and Technology (Guangzhou)</p>
  <p class="corr"><sup>&#9993;</sup> Corresponding authors</p>
  <!-- 会议 -->
  <p class="venue"><em>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2026</em></p>

  <!-- 链接按钮 -->
  <div class="publications">
    <div class="links project-links">
      <a href="#" class="btn btn-sm z-depth-0" role="button">Paper</a>
      <a href="#" class="btn btn-sm z-depth-0" role="button">arXiv</a>
      <a href="#" class="btn btn-sm z-depth-0" role="button">Code</a>
      <a href="#" class="btn btn-sm z-depth-0" role="button">Video</a>
    </div>
  </div>

  <!-- 主图 -->
  <div class="row justify-content-center mt-3">
    <div class="col-12">
      <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/projects/adaptive-critical-intro.png' | relative_url }}" alt="Adaptive-Critical overview" />
    </div>
  </div>
  <div class="caption">
    Adaptive-Critical adapts its conservatism to state-dependent criticality signals estimated from a distributional value
    function, rather than relying on a fixed risk heuristic, producing safer trajectories under uncertainty.
  </div>

  <h2>Abstract</h2>
  <div class="section-text">
    <p>
      Adaptive-Critical is a state-dependent risk-sensitive framework that transcends fixed heuristics by integrating
      distributional criticality signals with sensory cues, enabling robust navigation under partial observability and
      environmental uncertainty. By estimating the full return distribution, the agent identifies decision-critical states
      where errors are most costly and modulates its risk preference accordingly, yielding safer trajectories without
      sacrificing efficiency in benign regions.
    </p>
  </div>

  <h2>Overview</h2>
  <div class="section-text">
    <p>
      <!-- TODO: 替换为方法/框架的文字说明与配图。可放到 assets/img/projects/ 下，然后用下面的写法插入。 -->
      Placeholder for the method overview. Describe the distributional critic, the state-dependent criticality estimator,
      and how the risk preference is modulated during navigation.
    </p>
  </div>
  <!-- 方法配图示例（取消注释并替换文件名）
  <div class="row justify-content-center mt-3">
    <div class="col-12">
      <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/projects/adaptive-critical-framework.png' | relative_url }}" alt="Framework" />
    </div>
  </div>
  -->

  <!-- 视频分节（取消注释并把视频放到 assets/video/projects/ 下）
  <h2>Video</h2>
  <div class="row justify-content-center mt-3">
    <div class="col-12">
      {% include video.liquid path="assets/video/projects/adaptive-critical-demo.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
  </div>
  -->

  <h2>Citation</h2>
  <div class="bibtex-box">
    <button class="btn btn-sm z-depth-0 copy-btn" role="button" onclick="navigator.clipboard.writeText(document.getElementById('bibtex-adaptive-critical').innerText)">Copy</button>
    <pre id="bibtex-adaptive-critical"><code>@inproceedings{zhang2026adaptivecritical,
  title     = {Adaptive-Critical: Identifying Critical States for Risk-Sensitive Navigation via Distributional Reinforcement Learning},
  author    = {Zhang, Zhaofan and Xie, Sihong and Xiong, Hui},
  booktitle = {IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  year      = {2026},
}</code></pre>
  </div>
</div>
