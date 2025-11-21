---
title: About
layout: page
---
![Profile Image]({% if site.external-image %}{{ site.picture }}{% else %}{{ site.url }}/{{ site.picture }}{% endif %})

<p>
  Yoonsik Jung is a Ph.D. candidate in Industrial and Management Engineering at Korea University. His research interests include mathematical optimization, operations research, smart manufacturing, and machine learning.
</p>

<h3>Research Interests</h3>
<b>Mathematical Optimization &amp; Operations Research</b>
<p>
  Leveraging mathematical modeling and meta-heuristic techniques, he has designed a scheduling algorithm aimed at minimizing the work‐in‐process ratio at battery formation facilities [C4][C7].
</p>

<b>Smart Manufacturing &amp; Machine Learning</b>
<p>
  He has applied deep learning methods along with signal decomposition techniques, such as Fourier and wavelet transforms, to predict tool wear in machining processes [C6][C8]. Additionally, he developed an interpretable machine learning model to predict churn among MMORPG users. Furthermore, he proposed an integer programming–based promotion strategy to enhance user retention for NCSOFT’s action role-playing game, <i>Blade and Soul</i> [Award 2].
</p>

<style>
  ol {
    counter-reset: item;
    margin-left: 0;
    padding-left: 0;
  }
  ol li {
    margin-bottom: 0.5em;
    margin-left: 2em;
  }
  ul li {
    margin-bottom: 0.5em;
  }
  ol.conference li {
    display: block;
    margin-bottom: 0.5em;
    margin-left: 2em;
  }
  ol.conference li::before {
    display: inline-block;
    content: "C" counter(item) ".";
    counter-increment: item;
    width: 2em;
    margin-left: -2em;
  }
  ol.papers li::before {
    display: inline-block;
    content: "P" counter(item) ".";
    counter-increment: item;
    width: 2em;
    margin-left: -2em;
  }
</style>

<h3>Papers</h3>
<ol class="papers">
  <li>
    <b>Yoonsik Jung</b>, Hyejin Jang, Sunhye Kim, "Explainable AI for Player Retention: Hyper-Personalized Promotions to Prevent Game User Churn”, IEEE Transactions on Games, Under Review
  </li>
  <li>
    Dongwoo Kang, Sunung Kim, Eunhyo Kim, Sangkyun Noh, Hong Seo Ryoo, Kanguk Lee, <b>Yoonsik Jung<b>, "Maintenance Strategy of Semiconductor Equipment under Limited Data Conditions:A Survival Analysis Approach", KOREAN MANAGEMENT SCIENCE REVIEW, (2025)
  </li>
</ol>


<h3>Conferences</h3>
<ol class="conference">
  <li>
    <b>Yoonsik Jung</b>, Hong Seo Ryoo, "An Online Framework for Logical Analysis of Data with Dynamic Cutpoint Generation and Incremental Pattern Refinement”, APIEMS & SMILE 2025, Hangzhou, China (Nov. 2025)
  </li>
	<li>
    <b>Yoonsik Jung</b>, Hong Seo Ryoo, "Overcoming Spatial Feature Limitations in Image Classification through Convolutional Logical Analysis of Data”, 2024 INFORMS Annual Meeting, Seattle, WA, USA (Oct. 2024)
  </li>
  <li>
    <b>Yoonsik Jung</b>, Hong Seo Ryoo, “Bipartite Graph for Logical Pattern Generation”, 2023 INFORMS Annual Meeting, Phoenix, AZ, USA (Oct. 2023)
  </li>
  <li>
    Dongwoo Kang, Sunung Kim, <b>Yoonsik Jung</b>, Hong Seo Ryoo, “Generating Interpretable Patterns for Biomedical Image Classification”, 2021 IEEE International Conference on Bioinformatics and Biomedicine (BIBM), Virtual (Dec. 2021)
  </li>
  <li>
    <b>Yoonsik Jung</b>, Jeongin Koo, “A Scheduling Algorithm for Reducing Long-Term Work-In-Process Inventory in Battery Formation Process”, The 26th Winter Conference of Society for Computational Design and Engineering, Jeju, Korea (2020)
  </li>
  <li>
    Sun Kim, Hanjun Kwon, <b>Yoonsik Jung</b>, Jeongin Koo, “Design and Implementation of a Machining Process Data Preprocessing System”, KSMTE Spring Conference 2020, Pyungchang, Korea (2020)
  </li>
  <li>
    <b>Yoonsik Jung</b>, Mingi Kang, Jeongin Koo, “A Study on Tool Wear Estimation Using Discrete Wavelet Transformation and LSTM Networks”, KSMPE 2020 Spring Conference, Pyungchang, Korea (2020)
  </li>
  <li>
    <b>Yoonsik Jung</b>, Jeongin Koo, “A Development of a Scheduling Algorithm for Automated Logistics in Battery Formation Production”, The 25th Winter Conference of Society for Computational Design and Engineering, Pyungchang, Korea (2020)
  </li>
  <li>
    Jeongin Koo, <b>Yoonsik Jung</b>, Chanyong Kim, Dongil Kim, “A Study on the Toolwear Estimation Model Based on Machine Learning”, KSPE 2019 Fall Conference, Changwon, Korea (2019)
  </li>
</ol>

<h3>Awards</h3>
<ol>
  <li>
    Matlab AI Student Challenge, 3rd Prize, The MathWorks Korea, Korea (Oct. 2021)
  </li>
  <li>
    “게임 유저 이탈 예측 및 XAI 기반 초개인화 프로모션 제안”, Award of Merit, Industrial Engineering Project Competition, Korean Institute of Industrial Engineers, Korea (Nov. 2019)
  </li>
  <li>
    Computer Simulation Competition, Award of Distinction, The Korea Society for Simulation, Korea (Apr. 2019)
  </li>
  <li>
    “Development of Algorithms for Reducing Touch Error in Two-Thumb Text Entry on a Soft Keyboard”, Award of Merit, Ergonomics Capstone Design Award, Ergonomic Society of Korea, Korea (Nov. 2018)
  </li>
</ol>

<h3>Skills</h3>
<ul class="skill-list">
  <li>Python</li>
  <li>C++</li>
  <li>Java</li>
  <li>SQL &amp; Database</li>
  <li>Git</li>
  <li>Gurobi</li>
  <li>Linux</li>
</ul>


<!-- bundle exec jekyll serve -->

<!-- <h2>Projects</h2>

<ul>
	<li><a href="https://github.com/">Lorem Lorem</a></li>
	<li><a href="https://github.com/">Ipsum Dolor</a></li>
	<li><a href="https://github.com/">Dolor Lorem</a></li>
</ul> -->
