---
layout: yifan-homepage
permalink: /
title: "About Me"
---

<link rel="stylesheet" href="{{ base_path }}/assets/css/yifan-style.css">

<div class="wrapper">
  <header>
    <div class="image avatar">
      <img src="{{ base_path }}/images/jifengsong.JPG" alt="Jifeng Song">
    </div>
    <h1>Jifeng Song</h1>
    <p class="position">Ph.D. Student</p>
    <email>JIS219[at]pitt.edu</email>
    
    <div class="social-icons">
      <a href="https://scholar.google.com/citations?user=U_c8QM0AAAAJ&hl=en" title="Google Scholar">🔍</a>
      <a href="https://github.com/Muhusystem" title="GitHub">💻</a>
      <a href="https://www.linkedin.com/in/jifeng-song-51b2971a3" title="LinkedIn">💼</a>
      <a href="mailto:JIS219@pitt.edu" title="Email">✉️</a>
    </div>
    
    <div class="research-interests">
      <p>Research Interests:</p>
      <ul>
        <li>Multimodal Learning</li>
        <li>Vision-Language Models</li>
        <li>AI for Biomedicine</li>
        <li>Computational Biology</li>
      </ul>
    </div>
  </header>

  <section>
    <div class="about-section">
      <h2>About Me</h2>
      <p>
        Hi, I am Jifeng Song, a third-year Ph.D. student in Electrical and Computer Engineering at the 
        <a href="https://www.pitt.edu/">University of Pittsburgh</a> and also a research assistant in the Cancer Virology Program at 
        <a href="https://hillman.upmc.com/">UPMC Hillman Cancer Center</a>, co-advised by 
        <a href="https://www.sci.pitt.edu/people/yufei-huang">Prof. Yufei Huang</a> and 
        <a href="https://sites.pitt.edu/~zhm4/">Prof. Zhi-Hong Mao</a>. 
        My current research focuses on <strong>Multimodal Learning</strong> and <strong>AI for Biomedicine</strong>, with broader interests in AI for scientific discovery, computational biology, explainable AI, and efficient large language models. 
        I received my B.E. in Electrical Engineering and Automation from 
        <a href="https://www.hust.edu.cn/">Huazhong University of Science and Technology</a>, where I worked on transfer learning for renewable energy forecasting.
      </p>
      <p>
        Here is my <a href="{{ base_path }}/files/CV_JifengSong.pdf">CV</a>. My current work focuses on <strong>vision-language models for biomedical applications</strong>. 
        I am training biomedical multimodal large models for cancer research, particularly in spatial transcriptomics and single-cell, including multimodal retrieval, image captioning, question answering, and hypothesis generation.
      </p>
    </div>

    <div class="news-section">
      <h2>News</h2>
      <ul class="news-list">
        <li>
          <strong>[01/2026]</strong>
          <span class="news-content">Our paper <strong>FigEx2</strong> is released on arXiv. <a href="https://arxiv.org/abs/2601.08026">Check it out!</a></span>
        </li>
        <li>
          <strong>[01/2026]</strong>
          <span class="news-content">Our paper <strong>Aligning Findings with Diagnosis</strong> is released on arXiv.</span>
        </li>
        <li>
          <strong>[11/2025]</strong>
          <span class="news-content">Our paper <strong>FigEx</strong> is accepted by EMNLP 2025 Findings. Congrats to the team!</span>
        </li>
        <li>
          <strong>[12/2025]</strong>
          <span class="news-content">Our survey paper <strong>A Process-Centric Survey of AI for Scientific Discovery</strong> is released on Research Square.</span>
        </li>
        <li>
          <strong>[06/2025]</strong>
          <span class="news-content">Our paper <strong>Achieving Sparse Activation in Small Language Models</strong> is released on arXiv.</span>
        </li>
      </ul>
    </div>

    <div class="publications-section">
      <h2>Selected Publications | <a href="{{ base_path }}/publications/">Full list</a></h2>
      <p>(*equal contribution)</p>

      <div class="project-container">
        <table class="pub-table">
          <tr>
            <td class="media-col">
              <div class="project-media">
                <span class="conference-badge">EMNLP 2025 Findings</span>
                <img src="{{ base_path }}/images/figex.png" alt="FigEx">
              </div>
            </td>
            <td class="content-col">
              <div class="pub-title">
                <a href="https://aclanthology.org/2025.findings-emnlp.899/">FigEx: Aligned Extraction of Scientific Figures and Captions</a>
              </div>
              <div class="pub-authors">
                <strong>Jifeng Song</strong>, Arun Das, <strong>Ge Cui</strong>, <strong>Yufei Huang</strong>
              </div>
              <div class="pub-venue">Findings of the Association for Computational Linguistics: EMNLP 2025</div>
              <div class="text-links">
                <a href="https://aclanthology.org/2025.findings-emnlp.899/" class="text-btn">Paper</a>
                <a href="https://github.com/Huang-AI4Medicine-Lab/FigEx" class="text-btn">Code</a>
              </div>
              <div class="pub-description">A framework for aligned extraction of scientific figures and their captions from research papers.</div>
            </td>
          </tr>
        </table>
      </div>

      <div class="project-container">
        <table class="pub-table">
          <tr>
            <td class="media-col">
              <div class="project-media">
                <span class="conference-badge">arXiv</span>
                <img src="{{ base_path }}/images/500x300.png" alt="FigEx2">
              </div>
            </td>
            <td class="content-col">
              <div class="pub-title">
                <a href="https://arxiv.org/abs/2601.08026">FigEx2: Visual-Conditioned Panel Detection and Captioning for Scientific Compound Figures</a>
              </div>
              <div class="pub-authors">
                <strong>Jifeng Song</strong>, Arun Das, Pan Wang, Hui Ji, Kun Zhao, <strong>Yufei Huang</strong>
              </div>
              <div class="pub-venue">arXiv preprint 2025</div>
              <div class="text-links">
                <a href="https://arxiv.org/abs/2601.08026" class="text-btn">Paper</a>
              </div>
              <div class="pub-description">A visual-conditioned approach for detecting and captioning panels in scientific compound figures.</div>
            </td>
          </tr>
        </table>
      </div>

      <div class="project-container">
        <table class="pub-table">
          <tr>
            <td class="media-col">
              <div class="project-media">
                <span class="conference-badge">arXiv</span>
                <img src="{{ base_path }}/images/500x300.png" alt="Radiology Reporting">
              </div>
            </td>
            <td class="content-col">
              <div class="pub-title">
                <a href="https://arxiv.org/abs/2601.03321">Aligning Findings with Diagnosis: A Self-Consistent Reinforcement Learning Framework for Trustworthy Radiology Reporting</a>
              </div>
              <div class="pub-authors">
                Kun Zhao, Siyuan Dai, Pan Wang, <strong>Jifeng Song</strong>, Hui Ji, Chenghua Lin, Liang Zhan, Haoteng Tang
              </div>
              <div class="pub-venue">arXiv preprint 2025</div>
              <div class="text-links">
                <a href="https://arxiv.org/abs/2601.03321" class="text-btn">Paper</a>
              </div>
              <div class="pub-description">A self-consistent reinforcement learning framework for generating trustworthy radiology reports that align findings with diagnosis.</div>
            </td>
          </tr>
        </table>
      </div>

      <div class="project-container">
        <table class="pub-table">
          <tr>
            <td class="media-col">
              <div class="project-media">
                <span class="conference-badge">Res Sq</span>
                <img src="{{ base_path }}/images/500x300.png" alt="EXHYTE Framework">
              </div>
            </td>
            <td class="content-col">
              <div class="pub-title">
                <a href="https://doi.org/10.21203/rs.3.rs-8370059/v1">A Process-Centric Survey of AI for Scientific Discovery Through the EXHYTE Framework</a>
              </div>
              <div class="pub-authors">
                Md Musaddaqul Hasib, Sumin Jo, Harsh Sinha, <strong>Jifeng Song</strong>, Arun Das, Zhentao Liu, Hugh Galloway, Huey Huang, Kexun Zhang, Shou-Jiang Gao, Yu-Chiao Chiu, Lei Li, <strong>Yufei Huang</strong>
              </div>
              <div class="pub-venue">Research Square preprint 2024</div>
              <div class="text-links">
                <a href="https://doi.org/10.21203/rs.3.rs-8370059/v1" class="text-btn">Paper</a>
              </div>
              <div class="pub-description">A comprehensive survey of AI applications in scientific discovery organized through the EXHYTE framework.</div>
            </td>
          </tr>
        </table>
      </div>

      <div class="project-container">
        <table class="pub-table">
          <tr>
            <td class="media-col">
              <div class="project-media">
                <span class="conference-badge">arXiv</span>
                <img src="{{ base_path }}/images/500x300.png" alt="Sparse Activation">
              </div>
            </td>
            <td class="content-col">
              <div class="pub-title">
                <a href="https://arxiv.org/abs/2406.06562">Achieving Sparse Activation in Small Language Models</a>
              </div>
              <div class="pub-authors">
                <strong>Jifeng Song</strong>, Kai Huang, Xiangyu Yin, Boyuan Yang, Wei Gao
              </div>
              <div class="pub-venue">arXiv preprint 2024</div>
              <div class="text-links">
                <a href="https://arxiv.org/abs/2406.06562" class="text-btn">Paper</a>
                <a href="https://github.com/pittisl/Sparse-Activation" class="text-btn">Code</a>
              </div>
              <div class="pub-description">A method for achieving sparse activation patterns in small language models to improve efficiency and interpretability.</div>
            </td>
          </tr>
        </table>
      </div>
    </div>
  </section>
</div>
