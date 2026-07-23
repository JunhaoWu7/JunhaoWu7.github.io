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
        text: Download Resume
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
  - block: languages
    content:
      title: Languages
      username: junhao-wu
  - block: markdown
    content:
      title: Experience
      text: |-
        <div class="experience-grid">
          <article class="experience-card experience-card--tsinghua">
            <header class="experience-card__header">
              <div>
                <h3>Research Intern</h3>
                <p>College of AI, Tsinghua University</p>
              </div>
              <time datetime="2026-03">Mar 2026 – Present</time>
            </header>
            <figure class="experience-card__media experience-card__media--contain">
              <img src="/images/experience/tsinghua-college-ai.png" alt="College of AI, Tsinghua University" loading="lazy">
            </figure>
            <div class="experience-card__body">
              <p>Under the supervision of <strong>Assistant Professor Yongchao Chen</strong>, I work on <strong class="experience-card__highlight">world-model-driven robot learning</strong> and <strong>embodied intelligence</strong>. My research interests include <strong>VLA, world action models, humanoid robot motion retargeting, and multimodal synthetic data generation</strong>. I am also responsible for the deployment, maintenance, and experimental operation of the lab’s <strong class="experience-card__highlight">dual-arm Franka platform</strong>. This work aims to combine the temporal prediction capability of world models with the semantic understanding of foundation models, improving robots’ <strong>action generation, policy generalization, and execution robustness</strong> in complex real-world environments.</p>
            </div>
          </article>

          <article class="experience-card experience-card--apex">
            <header class="experience-card__header">
              <div>
                <h3>Algorithm Intern</h3>
                <p>Apex Intelligence</p>
              </div>
              <time datetime="2026-06">Jun 2026 – Present</time>
            </header>
            <figure class="experience-card__media experience-card__media--contain">
              <img src="/images/experience/apex-intelligence.jpg" alt="Apex Intelligence" loading="lazy">
            </figure>
            <div class="experience-card__body">
              <p>During my internship at <strong>Apex Intelligence</strong>, I worked on <strong class="experience-card__highlight">Auto Research agents</strong> and <strong>evaluation benchmarks</strong>. My work included <strong>Harness optimization</strong>, <strong>CoT analysis model development</strong>, and internal testing of <strong>Apex Research</strong>. I also contributed to several research and engineering deliverables, including <strong>CoRL and EMNLP submission support</strong> for Auto Research, <strong>Apex Research PR and technical report writing</strong>, and the construction, contribution, and full-scale testing of <strong><span class="experience-card__highlight">ASI</span> benchmark tasks</strong>. These evaluations covered multiple models, including Claude Opus 4.8, Claude Sonnet, and MiniMax.</p>
              <p>Overall, my work focused on <strong>automated research</strong>, <strong>agent evaluation</strong>, and <strong>platform capability building</strong>, reflecting my long-term interest in advancing <strong class="experience-card__highlight">self-evolving models</strong> and the realization of <strong class="experience-card__highlight">ASI</strong>.</p>
            </div>
          </article>

          <article class="experience-card experience-card--wict">
            <header class="experience-card__header">
              <div>
                <h3>Research Intern</h3>
                <p>Wangxuan Institute of Computer Technology, Peking University</p>
              </div>
              <time datetime="2025-11/2026-02">Nov 2025 – Feb 2026</time>
            </header>
            <figure class="experience-card__media experience-card__media--contain">
              <img src="/images/experience/wict.png" alt="Wangxuan Institute of Computer Technology, Peking University" loading="lazy">
            </figure>
            <div class="experience-card__body">
              <p>Serving as a Research Intern at <strong>OV3Lab</strong>, under the supervision of <strong>Professor Jiahuan Zhou</strong>. We systematically analyzed the performance degradation of OpenVLA under <strong>visual distribution shifts</strong> and attributed it to environmental perturbations in visual representations. Based on this insight, we developed a <strong class="experience-card__highlight">self-supervised training framework</strong> for the vision encoder, introducing a <strong>small number of learnable prompt tokens</strong> optimized with a <strong>redundancy-reduction objective</strong>. Without requiring target-domain data or language model updates, the method effectively enhances visual invariance. Experiments on LIBERO-plus and LIBERO-pro demonstrate consistent robustness improvements under <strong>lighting, layout, and background shifts</strong>, along with <strong class="experience-card__highlight">strong zero-shot generalization capability</strong>.</p>
            </div>
          </article>

          <article class="experience-card experience-card--meiya">
            <header class="experience-card__header">
              <div>
                <h3>Algorithm Intern</h3>
                <p>SDIC Intelligence Xiamen Information Co., Ltd (AI Institute)</p>
              </div>
              <time datetime="2025-03/2025-08">Mar 2025 – Aug 2025</time>
            </header>
            <figure class="experience-card__media experience-card__media--contain">
              <img src="/images/experience/meiya-pico.png" alt="SDIC Intelligence Xiamen Information Co., Ltd" loading="lazy">
            </figure>
            <div class="experience-card__body">
              <p>During my internship at <strong>SDIC Intelligence</strong>, I worked on open-vocabulary pedestrian attribute recognition and multimodal content understanding. For OVPAR, our team developed three open-vocabulary benchmarks—<strong>OV-MSP60K, OV-RAP2, and OV-CelebPAR</strong>—to evaluate generalization from seen to unseen attributes. We also proposed <strong>MGTSM</strong>, a meta-learning framework that simulates distribution shifts to improve adaptation to unseen classes, achieving more balanced performance across ZSL and GZSL settings.</p>
              <p>I also contributed to a <strong class="experience-card__highlight">multimodal deepfake detection system</strong> built around a multi-branch architecture that combines semantic, frequency-domain, and spatial-domain cues, using consistency constraints and contrastive learning to improve feature fusion. Evaluated on <strong>more than 100,000 samples</strong>, the model achieved <strong>0.97 AUC</strong> and <strong>over 93% accuracy</strong>.</p>
            </div>
          </article>
        </div>
  - block: experience
    content:
      username: junhao-wu
    design:
      # Hugo date format
      date_format: 'January 2026'
      # Education or Experience section first?
      is_education_first: false
  - block: portfolio
    content:
      title: Projects
      subtitle: ""
      count: 3
      filters:
        tags: []
        categories: []
        exclude_featured: false
      sort_by: Weight
      sort_ascending: true
    design:
      view: card
      columns: 3
      full_width: true

  - block: collection
    content:
      title: Events
      subtitle: ""
      # 告诉它读取哪类内容
      page_type: events
      # 显示数量
      count: 3
      # 过滤
      filters:
        tags: []
        categories: []
        featured_only: false
    design:
      view: card
      columns: 2
      full_width: true
  - block: awards
    content:
      title: Awards
      username: junhao-wu
  - block: skills
    content:
      title: Skills & Hobbies
      username: junhao-wu
---
