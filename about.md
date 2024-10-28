---
title: About
layout: page
---
![Profile Image]({% if site.external-image %}{{ site.picture }}{% else %}{{ site.url }}/{{ site.picture }}{% endif %})

<p>Yoonsik Jung is a Direct Ph.D Student in Industrial and Management Engineering, Korea University. His research interests are Mathematical Optimization, Operations Research, Smart Manufacturig, and Machine Learning.</p>

<h3> Research Interests </h3>
<b> Mathematical Optimization & Operations Research</b>
<p> Using mathematical modeling and (meta-)heuristics, he designed a scheduling algorithm to minimize the ratio of work in process on the battery formation facility[C3][C6]. </p>

<b> Smart Manufacturing & Machine Learning </b>  
<p> He predicted a wearing of machining tools, especially applying deep learning methods and signal decomposition processes such as Fourier transform and wavelet transform[C4][C6]. He also developed the interpretable machine learning model to predict churn of MMORPG(Massively Multiplayer Online Role-Playing Game) users. Furthermore, he proposed the integer programming based promotion strategy to improve retention of action role playing game 'Blade and Soul' from NCSOFT[Award 2].</p>

<style>
ol {
  counter-reset: item;
  margin-left: 0;
  padding-left: 0;
}

ol li{
	margin-bottom: .5em;
	margin-left: 2em;
}

ul li{
	margin-bottom: .5em;
}

ol.conference li {
  display: block;
  margin-bottom: .5em;
  margin-left: 2em;
}
ol.conference li::before {
  display: inline-block;
  content: "C"counter(item) ".";
  counter-increment: item;
  width: 2em;
  margin-left: -2em;
}
</style>

<h3>Conferences </h3>
<ol class="conference">
	<li><b>Yoonsik Jung</b>, Hong Seo Ryoo, "Bipartite Graph for Logical Pattern Generation", 2023 Informs Annual Meeting, Pheonix, AZ, USA (Oct. 2023)</li>
	<li>Dongwoo Kang, Sunung Kim, <b>Yoonsik Jung</b>, Hong Seo Ryoo, "Generating Interpretable Patterns
	for Biomedical Image Classification", 2021 IEEE International Conference on Bioinformatics and
	Biomedicine (BIBM), Virtual (Dec. 2021)</li>
	<!-- <li>박찬석, 정윤식, 구정인.(2020).생산 효율 향상을 위한 컨베이어 물류설비 지연예측모델.대한산업공학회 추계학술대회 논문집,(),3988-3998.</li>
	<li>화성 공정 생산성 향상을 위한 컨베이어 물류설비 지연예측모델 박찬석, 정윤식, 구정인 (한국생산기술연구원)</li> -->
	<li><b>Yoonsik Jung</b>, Jeongin Koo, "A Scheduling Algorithm for Reducing Long-Term Work-In-Process
	Inventory in Battery Formation Process", The 26th Winter Conference of Society for
	Computational Design and Engineering, Jeju, Korea(2020)</li>
	<li>Sun Kim, Hanjun Kwon, <b>Yoonsik Jung</b>, Jeongin Koo, "Design and Implementation of Machining
	Process Data preprocessing System", KSMTE Spring Conference 2020, Pyungchang, Korea(2020)</li>
	<li><b>Yoonsik Jung</b>, Mingi Kang, Jeongin Koo, "A Study on the Tool Wear Estimation Using Discrete
	Wavelet Transformation and LSTM Networks", KSMPE 2020 Spring Conference, Pyungchang,
	Korea(2020)</li>
	<li><b>Yoonsik Jung</b>, Jeongin Koo, "A Development on the Scheduling Algorithm for Automated
	Logistics in Battery Formation Production", The 25th Winter Conference of Society for
	Computational Design and Engineering, Pyungchang, Korea(2020)</li>
	<li>Jeongin Koo, <b>Yoonsik Jung</b>, Chanyong Kim, Dongil Kim, "A Study on the Toolwear Estimation
	Model based on the Machine Learning", KSPE 2019 Fall Conference , Changwon, Korea(2019)</li>

</ol>

<h3> Awards </h3>
<ol>
<li>Matlab AI Student Challenge, 3rd Prize, The MahtWorks Korea, Korea (Oct. 2021)</li>
<li>"게임 유저 이탈 예측 및 XAI 기반 초개인화 프로모션 제안", Award of Merit, Industrial Engineering Project Competition, Korean Institute of Industrial
Engineers, Korea (Nov. 2019)</li>
<li>Computer Simulation Competition, Award of Distinction, The Korea Society for Simulation,
Korea (Apr. 2019)</li>
<li>"Development of Algorithms for Reducing Touch Error in Two-Thumb Text Entry on a Soft Keyboard", Award of Merit, Ergonomics Capstone Design Award, Ergonomic Society of Korea, Korea (Nov.
2018)</li>
</ol>

<h3>Skills</h3>

<ul class="skill-list">
	<li>Python</li>
	<li>C++</li>
	<li>Java</li>
	<li>SQL & Database</li>
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
