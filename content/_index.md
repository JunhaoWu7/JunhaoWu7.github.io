---
title: 'Home'
date: 2023-10-24
type: landing
seo:
  title: 'Junhao Wu'

design:
  # Default section spacing
  spacing: '3rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: junhao-wu
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: /uploads/JunHao_Wu.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: background.jpg
        
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
      # Avatar customization
      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: About Me
      text: |-
        <div class="academic-about">
          <p>I am an incoming PhD student at the <strong>College of AI, Tsinghua University</strong>, starting in Fall 2027. My research focuses on <strong>embodied intelligence</strong> and <strong>general-purpose robot foundation models</strong>, particularly Vision-Language-Action (VLA) models, World-Action Models (WAM), and robot policy learning that integrates agent-based approaches with the capabilities of large models.</p>

          <p>Currently, I am a Research Intern at Tsinghua, working on robot learning and real-world manipulation. My goal is to improve robot robustness, long-horizon decision-making, policy generalization, and zero-shot transfer in complex open-world environments. I deploy and evaluate models on a dual-arm <strong>Franka Research 3</strong> platform to validate their performance on real robots.</p>

          <p>My earlier research explored VLA robustness under visual distribution shifts and open-vocabulary recognition. In parallel with my work at Tsinghua, I am an Algorithm Intern at <strong>Apex Intelligence</strong>, contributing to the development of autonomous scientific research agents, large-model training, and evaluation benchmarks.</p>
        </div>
  - block: markdown
    content:
      title: News
      text: |-
        <div class="academic-news" role="list">
          <article class="academic-news__item" role="listitem">
            <time datetime="2026-07">Jul 2026</time>
            <p>Served on the Program Committee and as a reviewer, organizer, and session chair for the <a href="/academic/">FM4RoboPlan Workshop at RSS 2026</a>.</p>
          </article>
          <article class="academic-news__item" role="listitem">
            <time datetime="2026-06">Jun 2026</time>
            <p>Joined <strong>Apex Intelligence</strong> as an Algorithm Intern, working on Auto Research agents and evaluation benchmarks.</p>
          </article>
          <article class="academic-news__item" role="listitem">
            <time datetime="2026-03">Mar 2026</time>
            <p>Joined the <strong>College of AI, Tsinghua University</strong> as a Research Intern in embodied intelligence and robot learning.</p>
          </article>
          <article class="academic-news__item" role="listitem">
            <time datetime="2025-11">Nov 2025</time>
            <p>Joined <strong>OV<sup>3</sup>Lab at Peking University</strong> to study robust VLA models under visual distribution shifts.</p>
          </article>
        </div>
  - block: markdown
    content:
      title: Selected Publications
      text: |-
        <div class="selected-publications">
          <article class="publication-card publication-card--paper publication-card--libero">
            <a class="publication-card__visual" href="https://arxiv.org/abs/2610.24587" target="_blank" rel="noopener">
              <img src="/images/publications/libero-pro2-overview.png" alt="Overview of LIBERO-Pro2.0 static distribution shifts and runtime interventions" loading="lazy">
            </a>
            <div class="publication-card__content">
              <div class="publication-card__meta">
                <span class="publication-card__status">arXiv</span>
                <span>Robotics · 2026</span>
              </div>
              <h3>LIBERO-Pro2.0: A Benchmark for Evaluating the Robustness of Embodied Foundation Models</h3>
              <p class="publication-card__authors"><span>Xueyang Zhou,</span> <span>Yangming Xu,</span> <span>Qianjiang Li,</span> <span>Guiyao Tie,</span> <span><strong>Junhao Wu</strong>, et al.</span></p>
              <p class="publication-card__summary">Evaluating robot foundation model robustness across 42 static and runtime perturbations.</p>
              <div class="publication-card__links">
                <a class="publication-card__link" href="https://arxiv.org/abs/2610.24587" target="_blank" rel="noopener">Paper <span aria-hidden="true">↗</span></a>
                <a class="publication-card__link" href="https://racingemperor.github.io/LIBERO-Pro2.0/index.html" target="_blank" rel="noopener">Project <span aria-hidden="true">↗</span></a>
                <a class="publication-card__link" href="https://github.com/LIBERO-Pro-Team/LIBERO-Pro2.0" target="_blank" rel="noopener">GitHub <span aria-hidden="true">↗</span></a>
                <a class="publication-card__link" href="https://huggingface.co/datasets/zhouxueyang/LIBERO-Pro2.0-Eval" target="_blank" rel="noopener" aria-label="Huggingface evaluation dataset">Huggingface <span aria-hidden="true">↗</span></a>
              </div>
            </div>
          </article>

          <article class="publication-card publication-card--paper publication-card--asi">
            <a class="publication-card__visual publication-figure--asi-overview" href="https://arxiv.org/abs/2608.17271" target="_blank" rel="noopener">
              <span class="publication-figure__crop"><img src="/images/publications/asi-bench-overview.png" alt="Overview of ASI-Bench scientific domains and research tasks" loading="lazy"></span>
            </a>
            <div class="publication-card__content">
              <div class="publication-card__meta">
                <span class="publication-card__status">arXiv</span>
                <span>AI for Science · 2026</span>
              </div>
              <h3>ASI-Bench: At the Dawn of Artificial Superintelligence</h3>
              <p class="publication-card__authors"><span>Junwei Zhou,</span> <span>Zhen Sun,</span> <span>Binyu Li,</span> …, <span><strong>Junhao Wu</strong>, et al.</span></p>
              <p class="publication-card__summary">Evaluating autonomous research across 60 scientific projects in 11 domains.</p>
              <div class="publication-card__links">
                <a class="publication-card__link" href="https://arxiv.org/abs/2608.17271" target="_blank" rel="noopener">Paper <span aria-hidden="true">↗</span></a>
                <a class="publication-card__link" href="https://asibench.apexin.ai/" target="_blank" rel="noopener">Project <span aria-hidden="true">↗</span></a>
                <a class="publication-card__link" href="https://github.com/apexin-ai/ASI-Bench" target="_blank" rel="noopener">GitHub <span aria-hidden="true">↗</span></a>
                <a class="publication-card__link" href="https://huggingface.co/datasets/Apexintelligence-AI/ASI-Bench-seed42" target="_blank" rel="noopener" aria-label="Huggingface seed42 dataset">Huggingface <span aria-hidden="true">↗</span></a>
              </div>
            </div>
          </article>

        </div>

        <p class="selected-publications__more"><a href="/publications/">View all publications <span aria-hidden="true">→</span></a></p>
    design:
      css_class: publications-section
  - block: markdown
    content:
      title: Research Experience
      text: |-
        <div id="research-experience" class="experience-grid research-gallery">
          <article class="research-entry research-entry--tsinghua">
            <figure class="research-entry__image">
              <img src="/images/experience/tsinghua-college-ai.png" alt="College of AI, Tsinghua University" loading="lazy">
            </figure>
            <header class="research-entry__header">
              <div>
                <h3>Research Intern</h3>
                <p>College of AI, Tsinghua University</p>
              </div>
              <time datetime="2026-03">Mar 2026 – Present</time>
            </header>
            <div class="research-entry__summary">
              <p>Researching <strong class="research-entry__emphasis">world-model-driven robot learning</strong> and embodied intelligence under <strong>Assistant Professor Yongchao Chen</strong>, with a focus on VLA and world-action models. Responsible for the <strong>dual-arm Franka Research 3 platform</strong>, including deployment, teleoperation, demonstration-data collection, model reproduction, and real-robot evaluation.</p>
            </div>
          </article>

          <article class="research-entry research-entry--apex">
            <figure class="research-entry__image">
              <img src="/images/experience/apex-intelligence.jpg" alt="Apex Intelligence" loading="lazy">
            </figure>
            <header class="research-entry__header">
              <div>
                <h3>Algorithm Intern</h3>
                <p>Apex Intelligence</p>
              </div>
              <time datetime="2026-06">Jun 2026 – Present</time>
            </header>
            <div class="research-entry__summary">
              <p>Worked on <strong class="research-entry__emphasis">Auto Research agents</strong> and evaluation benchmarks, covering Harness optimization, CoT analysis, and internal evaluation of Apex Research. Contributed to <strong>ASI-Bench</strong> task construction and large-model testing, as well as research submissions, technical writing, and product communication.</p>
            </div>
          </article>

          <article class="research-entry research-entry--wict">
            <figure class="research-entry__image">
              <img src="/images/experience/wict.png" alt="Wangxuan Institute of Computer Technology, Peking University" loading="lazy">
            </figure>
            <header class="research-entry__header">
              <div>
                <h3>Research Intern</h3>
                <p>Wangxuan Institute of Computer Technology, Peking University</p>
              </div>
              <time datetime="2025-11/2026-02">Nov 2025 – Feb 2026</time>
            </header>
            <div class="research-entry__summary">
              <p>Studied the robustness of VLA models under <strong>visual distribution shifts</strong> at <strong>OV³Lab</strong>, supervised by <strong>Professor Jiahuan Zhou</strong>. Developed a <strong class="research-entry__emphasis">self-supervised prompt-learning framework</strong> that improves robustness and zero-shot generalization under lighting, background, and layout changes.</p>
            </div>
          </article>

          <article class="research-entry research-entry--meiya">
            <figure class="research-entry__image">
              <img src="/images/experience/meiya-pico.png" alt="SDIC Intelligence Xiamen Information Co., Ltd" loading="lazy">
            </figure>
            <header class="research-entry__header">
              <div>
                <h3>Algorithm Intern</h3>
                <p>SDIC Intelligence Xiamen Information Co., Ltd (AI Institute)</p>
              </div>
              <time datetime="2025-03/2025-08">Mar 2025 – Aug 2025</time>
            </header>
            <div class="research-entry__summary">
              <p>Worked on open-vocabulary pedestrian attribute recognition, contributing to the <strong>OV-MSP60K, OV-RAP2, and OV-CelebPAR</strong> benchmarks and the <strong>MGTSM</strong> framework. Also developed a multimodal deepfake-detection system evaluated on <strong>100,000+ samples</strong>, achieving <strong>0.97 AUC</strong> and <strong>93%+ accuracy</strong>.</p>
            </div>
          </article>
        </div>
  - block: collection
    id: academic-projects
    content:
      title: Projects
      subtitle: ""
      page_type: projects
      count: 3
      filters:
        tags: []
        categories: []
        exclude_featured: false
      sort_by: Weight
      sort_ascending: true
    design:
      view: academic-row
      css_class: academic-list-section
      columns: 1
      full_width: true

  - block: collection
    id: academic-events
    content:
      title: Events
      subtitle: ""
      # 告诉它读取哪类内容
      page_type: events
      archive:
        text: View all events
        link: /events/
      # 显示数量
      count: 3
      # 过滤
      filters:
        tags: []
        categories: []
        featured_only: false
    design:
      view: academic-row
      css_class: academic-list-section
      columns: 1
      full_width: true
  - block: awards
    content:
      title: Awards
      username: junhao-wu
---
