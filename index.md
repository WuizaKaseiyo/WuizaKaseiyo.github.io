---
layout: default
title: Yuxuan Huang
---

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&family=Playfair+Display:ital,wght@0,600;0,700;1,600&display=swap" rel="stylesheet">

<style>
  /* ------------------- 核心布局与重置 ------------------- */
  header, footer { display: none !important; }

  body {
    font-family: 'Inter', -apple-system, sans-serif; /* 正文：现代无衬线 */
    line-height: 1.8; /* 增加行距，更易读 */
    color: #2c3e50;
    background-color: #fcfcfc; /* 极淡的暖灰背景，比纯白护眼 */
    margin: 0;
  }

  section {
    width: 100% !important;
    max-width: 880px !important; /*稍微收窄一点，阅读体验更好 */
    margin: 0 auto !important;
    padding: 60px 24px !important;
  }

  /* ------------------- 标题设计 ------------------- */
  h1 {
    font-family: 'Playfair Display', serif; /* 名字用衬线体，优雅 */
    font-size: 3em;
    font-weight: 700;
    color: #000;
    margin-bottom: 10px;
    letter-spacing: -0.5px;
  }

  h2 {
    font-family: 'Inter', sans-serif;
    font-size: 0.9em;
    text-transform: uppercase; /* 小标题全大写 */
    letter-spacing: 1.5px; /* 增加字间距 */
    color: #888;
    margin-top: 60px;
    margin-bottom: 25px;
    border-bottom: none; /* 去掉死板的下划线 */
    display: flex;
    align-items: center;
  }
  
  /* 给标题后面加一条细细的装饰线 */
  h2::after {
    content: "";
    flex: 1;
    height: 1px;
    background: #eee;
    margin-left: 15px;
  }

  /* ------------------- 链接与按钮风格 ------------------- */
  a {
    color: #0056b3;
    text-decoration: none;
    transition: all 0.2s ease;
  }
  a:hover {
    color: #003d82;
    background-color: rgba(0, 86, 179, 0.05); /* 鼠标悬停时淡淡的背景 */
    border-radius: 2px;
  }

  /* 把 [PDF] 变成小按钮 */
  .link-btn {
    font-family: 'Inter', sans-serif;
    font-size: 0.8em;
    display: inline-block;
    padding: 1px 8px;
    border: 1px solid #d1d5db;
    border-radius: 4px;
    color: #555 !important;
    margin-right: 5px;
    background: white;
  }
  .link-btn:hover {
    border-color: #0056b3;
    color: #0056b3 !important;
    background: #fff;
    text-decoration: none;
  }

  /* ------------------- 列表与排版优化 ------------------- */
  ul {
    padding-left: 0;
    list-style: none; /* 去掉默认的小黑点 */
  }
  
  /* 新闻列表样式 */
  .news-item {
    display: flex;
    margin-bottom: 12px;
    align-items: baseline;
  }
  .news-date {
    flex: 0 0 100px; /* 固定日期宽度 */
    font-family: 'Inter', sans-serif;
    font-weight: 600;
    font-size: 0.9em;
    color: #666;
  }
  .news-content {
    flex: 1;
  }

  /* 论文列表样式 */
  .pub-item {
    margin-bottom: 25px;
  }
  .pub-title {
    font-weight: 600;
    color: #000;
    font-size: 1.05em;
  }
  .pub-authors {
    color: #555;
    margin: 4px 0;
  }
  .pub-venue {
    font-style: italic;
    color: #666;
    margin-bottom: 6px;
  }

  /* 个人信息区域 */
  .intro-text {
    font-size: 1.1em;
    color: #444;
    max-width: 700px;
  }
  
  /* 移动端适配 */
  @media (max-width: 600px) {
    h1 { font-size: 2.2em; }
    .news-item { flex-direction: column; }
    .news-date { margin-bottom: 4px; color: #888; font-size: 0.85em; }
  }
</style>

<div style="margin-bottom: 50px;">
  <h1>Yuxuan Huang</h1>
  <div class="intro-text">
    <p>
      Ph.D. Student at <strong>University of Liverpool</strong> <br>
      <span style="font-size: 0.9em; color: #666;">
        📍 London, UK &nbsp;|&nbsp; 
        <a href="mailto:Kaseiyo@liverpool.ac.uk">Email</a> &nbsp;|&nbsp; 
        <a href="https://github.com/WuizaKaseiyo">Github</a>
      </span>
    </p>
  </div>
</div>

<div style="margin-bottom: 40px; font-size: 1.05em; color: #333;">
  <p>
    I am a Ph.D. student in Computer Science at the <strong>University of Liverpool</strong>, supervised by <strong>Prof. Meng Fang</strong>. I am also very fortunate to work closely with <strong>Prof. Jun Wang</strong>.
  </p>
  <p>
    My research interests focus on <strong>LLM based Agents</strong> and the application of <strong>Large Language Models (LLMs)</strong> in agent-based systems. I am particularly interested in building language-capable agents that can collaborate, plan, and adapt in real-world environments to support effective human-AI interaction.
  </p>
</div>

<h2>News</h2>
<div class="news-item">
  <div class="news-date">2026.Jan</div>
  <div class="news-content">One paper under review by <strong>ACL ARR 2026 Jan</strong>.</div>
</div>
<div class="news-item">
  <div class="news-date">2026.Jan</div>
  <div class="news-content">One paper under review by <strong>CVPR 2026</strong>.</div>
</div>
<div class="news-item">
  <div class="news-date">2025.Nov</div>
  <div class="news-content">One paper accepted by <strong>EMNLP 2025</strong>.</div>
</div>
<div class="news-item">
  <div class="news-date">2025.Jul</div>
  <div class="news-content">One paper accepted by <strong>ACL 2025</strong>.</div>
</div>
<div class="news-item">
  <div class="news-date">2024.Mar</div>
  <div class="news-content">One paper accepted by <strong>ICLR 2024 Workshop</strong>.</div>
</div>

<h2>Publications & Preprints</h2>
<div style="font-size: 0.85em; color: #888; margin-bottom: 25px; margin-top: -15px;">
  * denotes equal contribution
</div>

<div class="pub-item">
  <div class="pub-title">Adapting Like Humans: A Metacognitive Agent with Test-time Reasoning</div>
  <div class="pub-authors">Yang Li, Zhiyuan He, <strong>Yuxuan Huang</strong>*, Zhuhanling Xiao, Chao Yu, Meng Fang, Kun Shao, Jun Wang</div>
  <div class="pub-venue">arXiv preprint arXiv:2511.23262, 2025</div>
  <div>
    <a href="https://arxiv.org/abs/2511.23262" class="link-btn">arXiv</a>
  </div>
</div>

<div class="pub-item">
  <div class="pub-title">Spiral of Silence in Large Language Model Agents</div>
  <div class="pub-authors">Mingze Zhong, Meng Fang, Zijing Shi, <strong>Yuxuan Huang</strong>, Shunfeng Zheng, Yali Du, Ling Chen, Jun Wang</div>
  <div class="pub-venue">Findings of EMNLP 2025</div>
  <div>
    <a href="https://aclanthology.org/anthology-files/anthology-files/pdf/findings/2025.findings-emnlp.1262.pdf" class="link-btn">PDF</a>
  </div>
</div>

<div class="pub-item">
  <div class="pub-title">Agentic Web: Weaving the Next Web with AI Agents</div>
  <div class="pub-authors">Yingxuan Yang, Mulei Ma, <strong>Yuxuan Huang</strong>*, et al.</div>
  <div class="pub-venue">arXiv preprint arXiv:2507.21206, 2025</div>
  <div>
    <a href="https://arxiv.org/abs/2507.21206" class="link-btn">arXiv</a>
  </div>
</div>

<div class="pub-item">
  <div class="pub-title">Deep Research Agents: A Systematic Examination and Roadmap</div>
  <div class="pub-authors"><strong>Yuxuan Huang</strong>*, Yihang Chen, Haozheng Zhang, Kang Li, Meng Fang, et al.</div>
  <div class="pub-venue">arXiv preprint arXiv:2506.18096, 2025</div>
  <div>
    <a href="https://arxiv.org/abs/2506.18096" class="link-btn">arXiv</a>
  </div>
</div>

<div class="pub-item">
  <div class="pub-title">ATLaS: Agent Tuning via Learning Critical Steps</div>
  <div class="pub-authors">Zhixun Chen, Ming Li, <strong>Yuxuan Huang</strong>*, Yali Du, Meng Fang, Tianyi Zhou</div>
  <div class="pub-venue">Findings of ACL 2025</div>
  <div>
    <a href="https://aclanthology.org/2025.findings-acl.1299.pdf" class="link-btn">PDF</a>
  </div>
</div>

<div class="pub-item">
  <div class="pub-title">CausalPrompt: Enhancing LLMs with Weakly Supervised Causal Reasoning...</div>
  <div class="pub-authors">Tung-Wei Lin, Vanshaj Khattar, <strong>Yuxuan Huang</strong>*, et al.</div>
  <div class="pub-venue">ICLR 2024 Workshop</div>
  <div>
    <a href="https://www.climatechange.ai/papers/iclr2024/51" class="link-btn">Paper</a>
  </div>
</div>

<h2>Internships</h2>

<div class="news-item">
  <div class="news-date">2025.Mar - </div>
  <div class="news-content">
    <strong>Research Intern</strong>, Huawei Noah's Ark Lab. (London)
  </div>
</div>

<div class="news-item">
  <div class="news-date">2023.Apr - Jul</div>
  <div class="news-content">
    <strong>Data Analysis Intern</strong>, ByteDance Ltd. (Shanghai)
  </div>
</div>

<div class="news-item">
  <div class="news-date">2022.Aug - Feb</div>
  <div class="news-content">
    <strong>Algorithm Intern</strong>, Nio Inc. (Shanghai)
  </div>
</div>

<h2>Service</h2>
<ul>
  <li><strong>Reviewer:</strong> ACL 2025</li>
  <li><strong>Teaching Assistant:</strong> COMP532 BioInspired Learning (2024/2025)</li>
</ul>
