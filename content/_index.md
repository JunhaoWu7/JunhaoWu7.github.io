---
title: 'Home'
date: 2023-10-24
type: landing

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
              <p>Serving as a Research Intern at <strong>OV3Lab</strong>, under the supervision of <strong>Professor Jiahuan Zhou</strong>. We systematically analyzed the performance degradation of OpenVLA under <strong>visual distribution shifts</strong> and attributed it to environmental perturbations in visual representations. Based on this insight, we developed a <strong>self-supervised training framework</strong> for the vision encoder, introducing a <strong>small number of learnable prompt tokens</strong> optimized with a <strong>redundancy-reduction objective</strong>. Without requiring target-domain data or language model updates, the method effectively enhances visual invariance. Experiments on LIBERO-plus and LIBERO-pro demonstrate consistent robustness improvements under <strong>lighting, layout, and background shifts</strong>, along with <strong>strong zero-shot generalization capability</strong>.</p>
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
              <p>Contributed to a <strong>multimodal deepfake detection system</strong> that fuses semantic, frequency-domain, and spatial-domain features for social platform content moderation and evidence extraction. Worked with <strong class="experience-card__metric">100K+ data samples</strong> across multiple modalities; incorporated CLIP-based semantic features, a frequency-branch module (Freq-Net), and a spatial-branch module (CameraPrint), and applied mutual-consistency constraints and contrastive learning to improve fusion. Achieved <strong class="experience-card__metric">0.97 AUC</strong> on the validation set and <strong class="experience-card__metric">93%+</strong> accuracy, delivering a <strong class="experience-card__metric">~8-percentage-point</strong> improvement over a baseline model.</p>
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
