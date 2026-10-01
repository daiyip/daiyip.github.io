---
layout: default
---

<div class="intro">
  <h1>Daiyi Peng</h1>
  <p class="lede">I retired from Google in 2026 to start an experiment for&nbsp;<em>post-AGI living</em>.</p>
  <p class="bio">Former research engineer at <b>Google DeepMind</b>, working on long-term LLM research, especially agents. Before that, at <b>Google Brain</b>, working on AutoML. Before that, at <b>Microsoft</b>, working on distributed systems and search engines.</p>
  <div class="links mono">
    <a href="https://github.com/daiyip">GitHub</a>
    <a href="https://scholar.google.com/citations?user=3PGBcLsAAAAJ&amp;hl=en">Google Scholar</a>
  </div>
</div>

<section class="oss">
  <div class="label">Open source</div>
  <a href="https://github.com/google/pyglove"><span class="name">PyGlove</span><span class="desc"> — manipulating Python programs for ML, AutoML and beyond</span></a>
  <a href="https://github.com/google/langfun"><span class="name">Langfun</span><span class="desc"> — object-oriented programming with LLMs</span></a>
  <a href="https://github.com/Microsoft/napajs"><span class="name">Napa.js</span><span class="desc"> — a multi-threaded JavaScript runtime</span></a>
</section>

<section>
  <div class="label">Selected publications</div>
  {% assign recent = site.data.publications | slice: 0, 5 %}
  {% include publication-titles.html items=recent %}
  <div class="more mono"><a href="{{ '/publications' | relative_url }}">All publications →</a></div>
</section>

<section>
  <div class="label">Earlier writing</div>
  <a href="https://www.linkedin.com/pulse/napajs-multi-threaded-javascript-runtime-daiyi-peng/">Napa.js: A multi-threaded JavaScript runtime</a>
  <a href="https://www.linkedin.com/pulse/wineryjs-framework-service-experimentation-daiyi-peng">Winery.js: A framework for service experimentation</a>
  <a href="https://www.linkedin.com/pulse/continuous-modification-process-build-services-constantly-daiyi-peng/">Continuous modification: a process to build services that constantly evolve</a>
</section>
