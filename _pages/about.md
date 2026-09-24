---
layout: yifan-homepage
permalink: /
title: "About Me"
---

<div class="wrapper">
  {% include homepage-nav.html %}

  {% include homepage-profile.html %}

  <main id="main-content">
    <div class="about-section" id="about">
      <p class="research-kicker">AI for biomedicine &amp; scientific discovery</p>
      <h2>About Me</h2>
      <p>
        Hi, I am Jifeng Song, a fourth-year Ph.D. student in Electrical and Computer Engineering at the
        <a href="https://www.pitt.edu/">University of Pittsburgh</a> and also a research assistant in the Cancer Virology Program at 
        <a href="https://hillman.upmc.com/">UPMC Hillman Cancer Center</a>, co-advised by 
        <a href="https://www.sci.pitt.edu/people/yufei-huang">Prof. Yufei Huang</a> and 
        <a href="https://sites.pitt.edu/~zhm4/">Prof. Zhi-Hong Mao</a>. 
        I received my B.E. in Electrical Engineering and Automation from 
        <a href="https://www.hust.edu.cn/">Huazhong University of Science and Technology</a>.
      </p>
      <p>
        My current research focuses on <strong>post-training and efficient inference for multimodal large language models (MLLMs)</strong>, with applications in <strong>scientific discovery and cancer research</strong>.
        I am particularly interested in scientific document understanding and multimodal knowledge discovery.
      </p>
      <p class="opportunity-line">
        <strong>I am actively seeking internship opportunities starting in 2027.</strong> You can find my CV <a href="{{ base_path }}/files/CV_JifengSong.pdf">here</a>.
      </p>
    </div>

    <div class="news-section" id="news">
      <h2>News</h2>
      <ul class="news-list">
        <li>
          <strong>[08/2026]</strong>
          <span class="news-content">🎉 Paper accepted to <strong>EMNLP Main</strong>: <a href="https://arxiv.org/abs/2601.08026">FigEx2: Visual-Conditioned Panel Detection and Captioning for Scientific Compound Figures</a>.</span>
        </li>
        <li>
          <strong>[05/2026]</strong>
          <span class="news-content">🎉 Paper accepted to <strong>MLSys</strong>: <a href="https://proceedings.mlsys.org/paper_files/paper/2026/hash/29591f355702c3f4436991335784b503-Abstract-Conference.html">Attribution-based Sparse Activation in Large Language Models</a>.</span>
        </li>
        <li>
          <strong>[04/2026]</strong>
          <span class="news-content">New preprint: <a href="https://www.biorxiv.org/content/10.64898/2026.04.29.721735v1">spatiAlytica</a>.</span>
        </li>
        <li>
          <strong>[01/2026]</strong>
          <span class="news-content">New preprint: <a href="https://arxiv.org/abs/2601.03321">Aligning Findings with Diagnosis</a>.</span>
        </li>
        <li>
          <strong>[12/2025]</strong>
          <span class="news-content">New preprint: <a href="https://doi.org/10.21203/rs.3.rs-8370059/v1">A Process-Centric Survey of AI for Scientific Discovery</a>.</span>
        </li>
        <li>
          <strong>[08/2025]</strong>
          <span class="news-content">🎉 Paper accepted to <strong>EMNLP Findings</strong>: <a href="https://aclanthology.org/2025.findings-emnlp.899/">FigEx: Aligned Extraction of Scientific Figures and Captions</a>.</span>
        </li>
        <li>
          <strong>[06/2024]</strong>
          <span class="news-content">New preprint: <a href="https://arxiv.org/abs/2406.06562">Achieving Sparse Activation in Small Language Models</a>.</span>
        </li>
      </ul>
    </div>

    <div class="publications-section" id="publications">
      <div class="section-heading"><h2>Selected Publications</h2><a class="section-link" href="{{ base_path }}/publications/">Full list <span aria-hidden="true">↗</span></a></div>
      <p class="publication-note"><span><sup>&dagger;</sup> Equal contribution.</span></p>

      <div class="project-container">
        <table class="pub-table">
          <tr>
            <td class="media-col">
              <span class="conference-badge venue-emnlp">EMNLP 2026</span>
              <div class="project-media">
                <img src="{{ base_path }}/images/figex2.png" alt="FigEx2">
              </div>
            </td>
            <td class="content-col">
              <div class="pub-title">
                <a href="https://arxiv.org/abs/2601.08026">FigEx2: Visual-Conditioned Panel Detection and Captioning for Scientific Compound Figures</a>
              </div>
              <div class="pub-authors">
                <strong class="author-self">Jifeng Song</strong>, Arun Das, Pan Wang, Hui Ji, Kun Zhao, Yufei Huang
              </div>
              <div class="pub-venue">Proceedings of the 2026 Conference on Empirical Methods in Natural Language Processing</div>
              <div class="text-links">
                <a href="https://arxiv.org/abs/2601.08026" class="text-btn">Paper</a>
                <a href="https://github.com/Huang-AI4Medicine-Lab/FigEx2" class="text-btn">Code</a>
              </div>
            </td>
          </tr>
        </table>
      </div>

      <div class="project-container">
        <table class="pub-table">
          <tr>
            <td class="media-col">
              <span class="conference-badge venue-mlsys">MLSys 2026</span>
              <div class="project-media">
                <img src="{{ base_path }}/images/sparse-activation.png" alt="Attribution-based Sparse Activation">
              </div>
            </td>
            <td class="content-col">
              <div class="pub-title">
                <a href="https://proceedings.mlsys.org/paper_files/paper/2026/hash/29591f355702c3f4436991335784b503-Abstract-Conference.html">Attribution-based Sparse Activation in Large Language Models</a>
              </div>
              <div class="pub-authors">
                <strong class="author-self">Jifeng Song</strong><sup>&dagger;</sup>, Xiangyu Yin<sup>&dagger;</sup>, Boyuan Yang, Kai Huang, Weichen Liu, Wei Gao
              </div>
              <div class="pub-venue">Proceedings of Machine Learning and Systems (MLSys) 2026</div>
              <div class="text-links">
                <a href="https://proceedings.mlsys.org/paper_files/paper/2026/hash/29591f355702c3f4436991335784b503-Abstract-Conference.html" class="text-btn">Paper</a>
                <a href="https://github.com/pittisl/Sparse-Activation" class="text-btn">Code</a>
              </div>
            </td>
          </tr>
        </table>
      </div>

      <div class="project-container">
        <table class="pub-table">
          <tr>
            <td class="media-col">
              <span class="conference-badge venue-emnlp">EMNLP 2025</span>
              <div class="project-media">
                <img src="{{ base_path }}/images/figex.png" alt="FigEx">
              </div>
            </td>
            <td class="content-col">
              <div class="pub-title">
                <a href="https://aclanthology.org/2025.findings-emnlp.899/">FigEx: Aligned Extraction of Scientific Figures and Captions</a>
              </div>
              <div class="pub-authors">
                <strong class="author-self">Jifeng Song</strong>, Arun Das, Ge Cui, Yufei Huang
              </div>
              <div class="pub-venue">Findings of the Association for Computational Linguistics: EMNLP 2025</div>
              <div class="text-links">
                <a href="https://aclanthology.org/2025.findings-emnlp.899/" class="text-btn">Paper</a>
                <a href="https://github.com/Huang-AI4Medicine-Lab/FigEx" class="text-btn">Code</a>
                <a href="https://huggingface.co/datasets/Huang-AI4Medicine-Lab/BioSci-Fig" class="text-btn">Dataset</a>
              </div>
            </td>
          </tr>
        </table>
      </div>

      <div class="project-container">
        <table class="pub-table">
          <tr>
            <td class="media-col">
              <span class="conference-badge venue-biorxiv">bioRxiv</span>
              <div class="project-media">
                <img src="{{ base_path }}/images/spatialytica.png" alt="spatiAlytica">
              </div>
            </td>
            <td class="content-col">
              <div class="pub-title">
                <a href="https://www.biorxiv.org/content/10.64898/2026.04.29.721735v1">spatiAlytica: Viewer-Grounded Multimodal Agentic System for Interactive Spatial Omics Analysis</a>
              </div>
              <div class="pub-authors">
                Arun Das, Kexun Zhang, <strong class="author-self">Jifeng Song</strong>, Meiru Han, Angela Chen, Wen Meng, Hugh Galloway, Po-Yuan Chen, Sumin Jo, Zhentao Liu, Md Musaddaqul Hasib, Adam Officer, Harsh Sinha, Yu-Chiao Chiu, Shou-Jiang Gao, Lei Li, Yufei Huang
              </div>
              <div class="pub-venue">bioRxiv preprint 2026</div>
              <div class="text-links">
                <a href="https://www.biorxiv.org/content/10.64898/2026.04.29.721735v1" class="text-btn">Paper</a>
              </div>
            </td>
          </tr>
        </table>
      </div>

      <div class="project-container">
        <table class="pub-table">
          <tr>
            <td class="media-col">
              <span class="conference-badge venue-arxiv">arXiv</span>
              <div class="project-media">
                <img src="{{ base_path }}/images/aligning-findings.png" alt="Radiology Reporting">
              </div>
            </td>
            <td class="content-col">
              <div class="pub-title">
                <a href="https://arxiv.org/abs/2601.03321">Aligning Findings with Diagnosis: A Self-Consistent Reinforcement Learning Framework for Trustworthy Radiology Reporting</a>
              </div>
              <div class="pub-authors">
                Kun Zhao, Siyuan Dai, Pan Wang, <strong class="author-self">Jifeng Song</strong>, Hui Ji, Chenghua Lin, Liang Zhan, Haoteng Tang
              </div>
              <div class="pub-venue">arXiv preprint 2026</div>
              <div class="text-links">
                <a href="https://arxiv.org/abs/2601.03321" class="text-btn">Paper</a>
              </div>
            </td>
          </tr>
        </table>
      </div>
    </div>

  </main>
</div>
