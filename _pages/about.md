---
layout: yifan-homepage
permalink: /
title: "About Me"
---

<nav class="site-nav">
  <div class="nav-inner">
    <a class="nav-brand" href="{{ base_path }}/">Homepage</a>
    <ul class="nav-links">
      <li><a href="#about">About Me</a></li>
      <li><a href="#news">News</a></li>
      <li><a href="#publications">Selected Publications</a></li>
      <li><a href="{{ base_path }}/talks/">Talks & Posters</a></li>
      <li><a href="#teaching">Teaching</a></li>
      <li><a href="#experiences">Experiences</a></li>
    </ul>
  </div>
</nav>

<main class="page-wrap">
  <aside class="profile">
    <img class="profile-photo" src="{{ base_path }}/images/jifengsong.JPG" alt="Jifeng Song">
    <h1>Jifeng Song</h1>
    <p class="profile-title">Ph.D. Student</p>

    <ul class="profile-list">
      <li>University of Pittsburgh</li>
      <li>Pittsburgh, PA, USA</li>
      <li>JIS219 [at] pitt.edu</li>
    </ul>

    <ul class="social-list">
      <li><a href="https://github.com/Muhusystem"><i class="fab fa-github" aria-hidden="true"></i>Github</a></li>
      <li><a href="https://scholar.google.com/citations?user=U_c8QM0AAAAJ&hl=en"><i class="ai ai-google-scholar" aria-hidden="true"></i>Google Scholar</a></li>
      <li><a href="https://www.linkedin.com/in/jifeng-song-51b2971a3"><i class="fab fa-linkedin" aria-hidden="true"></i>LinkedIn</a></li>
      <li><a href="mailto:JIS219@pitt.edu"><i class="fas fa-envelope" aria-hidden="true"></i>Email</a></li>
    </ul>

    <div class="research-list">
      <p>Research Interests</p>
      <ul>
        <li>Multimodal Learning</li>
        <li>Vision-Language Models</li>
        <li>AI for Biomedicine</li>
        <li>Computational Biology</li>
      </ul>
    </div>
  </aside>

  <div class="content">
    <section class="content-section" id="about">
      <h2>About Me</h2>
      <p>
        Hi, I am Jifeng Song, a third-year Ph.D. student in Electrical and Computer Engineering at the
        <a href="https://www.pitt.edu/">University of Pittsburgh</a> and a research assistant in the Cancer Virology Program at
        <a href="https://hillman.upmc.com/">UPMC Hillman Cancer Center</a>. I am co-advised by
        <a href="https://www.sci.pitt.edu/people/yufei-huang">Prof. Yufei Huang</a> and
        <a href="https://sites.pitt.edu/~zhm4/">Prof. Zhi-Hong Mao</a>.
      </p>
      <p>
        My current research focuses on <strong>Multimodal Learning</strong> and <strong>AI for Biomedicine</strong>, with broader interests in AI for scientific discovery, <strong>computational biology (single-cell and spatial transcriptomics)</strong>, explainable AI, and efficient large language models. I received my B.E. in Electrical Engineering and Automation from
        <a href="https://www.hust.edu.cn/">Huazhong University of Science and Technology</a>, where I worked on transfer learning for renewable energy forecasting.
      </p>
      <p>
        Here is my <a href="{{ base_path }}/files/CV_JifengSong.pdf">CV</a>. My current work focuses on <strong>vision-language models for biomedical applications</strong>, particularly biomedical multimodal large models for cancer research, spatial transcriptomics and single-cell analysis, multimodal retrieval, image captioning, question answering, and hypothesis generation.
      </p>
    </section>

    <section class="content-section" id="news">
      <h2>News</h2>
      <ul class="news-list">
        <li>2026.01: Our paper <strong>FigEx2</strong> is released on arXiv.</li>
        <li>2026.01: Our paper <strong>Aligning Findings with Diagnosis</strong> is released on arXiv.</li>
        <li>2025.12: Our survey paper <strong>A Process-Centric Survey of AI for Scientific Discovery</strong> is released on Research Square.</li>
        <li>2025.11: Our paper <strong>FigEx</strong> is accepted by EMNLP 2025 Findings.</li>
        <li>2024.06: Our paper <strong>Achieving Sparse Activation in Small Language Models</strong> is released on arXiv.</li>
      </ul>
    </section>

    <section class="content-section" id="publications">
      <h2>Selected Publications</h2>

      <h3>Multimodal Scientific Document Understanding</h3>

      <article class="publication">
        <div class="pub-media">
          <span class="venue-badge">arXiv 2026</span>
          <img src="{{ base_path }}/images/figex2.png" alt="FigEx2">
        </div>
        <div>
          <p class="pub-title"><a href="https://arxiv.org/abs/2601.08026">FigEx2: Visual-Conditioned Panel Detection and Captioning for Scientific Compound Figures</a></p>
          <p class="pub-authors"><strong>Jifeng Song</strong>, Arun Das, Pan Wang, Hui Ji, Kun Zhao, Yufei Huang</p>
          <p class="pub-note">Visual-conditioned panel detection and captioning for scientific compound figures.</p>
          <p class="pub-links"><a href="https://arxiv.org/abs/2601.08026">Paper</a></p>
        </div>
      </article>

      <article class="publication">
        <div class="pub-media">
          <span class="venue-badge">EMNLP 2025 Findings</span>
          <img src="{{ base_path }}/images/figex.png" alt="FigEx">
        </div>
        <div>
          <p class="pub-title"><a href="https://aclanthology.org/2025.findings-emnlp.899/">FigEx: Aligned Extraction of Scientific Figures and Captions</a></p>
          <p class="pub-authors"><strong>Jifeng Song</strong>, Arun Das, Ge Cui, Yufei Huang</p>
          <p class="pub-note">Aligned extraction of scientific figures and captions.</p>
          <p class="pub-links"><a href="https://aclanthology.org/2025.findings-emnlp.899/">Paper</a><a href="https://github.com/Huang-AI4Medicine-Lab/FigEx">Code</a></p>
        </div>
      </article>

      <h3>Biomedical AI</h3>

      <article class="publication">
        <div class="pub-media">
          <span class="venue-badge">arXiv 2026</span>
          <img src="{{ base_path }}/images/aligning-findings.png" alt="Radiology Reporting">
        </div>
        <div>
          <p class="pub-title"><a href="https://arxiv.org/abs/2601.03321">Aligning Findings with Diagnosis: A Self-Consistent Reinforcement Learning Framework for Trustworthy Radiology Reporting</a></p>
          <p class="pub-authors">Kun Zhao, Siyuan Dai, Pan Wang, <strong>Jifeng Song</strong>, Hui Ji, Chenghua Lin, Liang Zhan, Haoteng Tang</p>
          <p class="pub-note">Self-consistent reinforcement learning for trustworthy radiology reporting.</p>
          <p class="pub-links"><a href="https://arxiv.org/abs/2601.03321">Paper</a></p>
        </div>
      </article>

      <article class="publication">
        <div class="pub-media">
          <span class="venue-badge">Research Square 2025</span>
          <img src="{{ base_path }}/images/exhyte-framework.png" alt="EXHYTE Framework">
        </div>
        <div>
          <p class="pub-title"><a href="https://doi.org/10.21203/rs.3.rs-8370059/v1">A Process-Centric Survey of AI for Scientific Discovery Through the EXHYTE Framework</a></p>
          <p class="pub-authors">Md Musaddaqul Hasib, Sumin Jo, Harsh Sinha, <strong>Jifeng Song</strong>, Arun Das, Zhentao Liu, Hugh Galloway, Huey Huang, Kexun Zhang, Shou-Jiang Gao, Yu-Chiao Chiu, Lei Li, Yufei Huang</p>
          <p class="pub-note">A process-centric survey of AI for scientific discovery.</p>
          <p class="pub-links"><a href="https://doi.org/10.21203/rs.3.rs-8370059/v1">Paper</a></p>
        </div>
      </article>

      <h3>Efficient Language Models</h3>

      <article class="publication">
        <div class="pub-media">
          <span class="venue-badge">arXiv 2024</span>
          <img src="{{ base_path }}/images/sparse-activation.png" alt="Sparse Activation">
        </div>
        <div>
          <p class="pub-title"><a href="https://arxiv.org/abs/2406.06562">Achieving Sparse Activation in Small Language Models</a></p>
          <p class="pub-authors"><strong>Jifeng Song</strong>, Kai Huang, Xiangyu Yin, Boyuan Yang, Wei Gao</p>
          <p class="pub-note">Sparse activation methods for small language models.</p>
          <p class="pub-links"><a href="https://arxiv.org/abs/2406.06562">Paper</a><a href="https://github.com/pittisl/Sparse-Activation">Code</a></p>
        </div>
      </article>

      <p><a href="{{ base_path }}/publications/">Full List of Publications</a></p>
    </section>

    <section class="content-section" id="teaching">
      <h2>Teaching</h2>
      <ul class="plain-list">
        <li>Teaching materials and course activities are listed on the <a href="{{ base_path }}/teaching/">Teaching</a> page.</li>
      </ul>
    </section>

    <section class="content-section" id="experiences">
      <h2>Experiences</h2>
      <ul class="plain-list">
        <li>2023.09 - Now, Ph.D. Student, Electrical and Computer Engineering, University of Pittsburgh</li>
        <li>Research Assistant, Cancer Virology Program, UPMC Hillman Cancer Center</li>
        <li>B.E., Electrical Engineering and Automation, Huazhong University of Science and Technology</li>
      </ul>
    </section>
  </div>
</main>
