---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* PREMIUM TYPOGRAPHY ENHANCEMENTS */
.intro-text { font-family: -apple-system, BlinkMacSystemFont, "Roboto", "Helvetica Neue", "Segoe UI", Arial, sans-serif; font-size: 1.15rem; margin-top: 2.5rem; margin-bottom: 2.5rem; color: #334155; line-height: 1.85; font-weight: 400; }
.intro-text p { margin-bottom: 1.25rem; }
.intro-text strong { color: #0f172a; font-weight: 600; }
.section-title { font-family: -apple-system, BlinkMacSystemFont, "Roboto", "Helvetica Neue", "Segoe UI", Arial, sans-serif; font-size: 1.7rem; font-weight: 700; letter-spacing: -0.01em; margin-top: 3.5rem; margin-bottom: 1.5rem; border-bottom: 2px solid #f1f5f9; padding-bottom: 0.5rem; color: #0f172a; display: flex; align-items: center; gap: 10px; }

/* Existing Components CSS with updated colors and spacing */
.news-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 15px; margin-bottom: 2rem; font-family: -apple-system, sans-serif; }
.news-card { background: #fff; border: 1px solid #e2e8f0; border-radius: 10px; padding: 18px; box-shadow: 0 4px 6px -1px rgba(0,0,0,0.02); transition: transform 0.2s, box-shadow 0.2s; }
.news-card:hover { transform: translateY(-3px); box-shadow: 0 10px 15px -3px rgba(0,0,0,0.05); }
.news-date { font-weight: 700; color: #0284c7; margin-bottom: 8px; font-size: 0.85em; display: inline-block; background: #e0f2fe; padding: 4px 10px; border-radius: 20px; }
.news-desc { font-size: 1rem; color: #334155; line-height: 1.6; }

.exp-list { list-style-type: none; padding-left: 0; font-family: -apple-system, sans-serif; }
.exp-item { margin-bottom: 1.8rem; padding-left: 20px; border-left: 3px solid #e2e8f0; position: relative; }
.exp-item::before { content: ""; position: absolute; left: -8px; top: 6px; width: 13px; height: 13px; border-radius: 50%; background: #0284c7; box-shadow: 0 0 0 3px #fff; }
.exp-date { font-size: 0.95rem; color: #64748b; font-weight: 600; margin-bottom: 0.3rem; display: inline-block; }
.exp-title { font-size: 1.15rem; font-weight: 700; margin-bottom: 0.3rem; color: #0f172a; }
.exp-desc { font-size: 1rem; color: #475569; line-height: 1.6; }
.exp-desc a { color: #0284c7; text-decoration: none; font-weight: 500; }
.exp-desc a:hover { text-decoration: underline; }

.pub-list { list-style-type: none; padding-left: 0; font-family: -apple-system, sans-serif; }
.pub-item { display: flex; gap: 20px; align-items: flex-start; margin-bottom: 1.5rem; padding: 20px; border: 1px solid #e2e8f0; border-radius: 12px; background-color: #fff; transition: box-shadow 0.2s ease, transform 0.2s ease; }
.pub-item:hover { box-shadow: 0 10px 25px -5px rgba(0,0,0,0.05); transform: translateY(-3px); }
.pub-image { width: 220px; flex-shrink: 0; border-radius: 8px; overflow: hidden; border: 1px solid #f1f5f9; background: #f8fafc; display: flex; align-items: center; justify-content: center; min-height: 120px; }
.pub-image img { width: 100%; height: auto; display: block; object-fit: cover; }
.pub-content { flex-grow: 1; display: flex; flex-direction: column; justify-content: center; }
.pub-title { font-weight: 700; font-size: 1.15rem; margin-bottom: 0.5rem; color: #0f172a; line-height: 1.5; }
.pub-authors { font-size: 1rem; color: #475569; margin-bottom: 0.4rem; }
.pub-venue { font-size: 0.95rem; color: #64748b; font-style: italic; margin-bottom: 0.8rem; font-weight: 500; }
.pub-links a { display: inline-block; font-size: 0.9rem; color: #334155; border: 1px solid #cbd5e1; border-radius: 6px; padding: 5px 12px; text-decoration: none; margin-right: 8px; transition: all 0.2s ease; background: #f8fafc; font-weight: 600; }
.pub-links a:hover { background-color: #f1f5f9; border-color: #94a3b8; }
.pub-badge { display: inline-block; background-color: #10b981; color: #fff; font-size: 0.75rem; font-weight: bold; padding: 2px 8px; border-radius: 12px; margin-left: 8px; vertical-align: middle; }

.project-gallery { display: grid; grid-template-columns: repeat(auto-fill, minmax(320px, 1fr)); gap: 20px; margin-bottom: 2rem; font-family: -apple-system, sans-serif; }
.gallery-card { border: 1px solid #e2e8f0; border-radius: 12px; overflow: hidden; background: #fff; transition: transform 0.2s, box-shadow 0.2s; box-shadow: 0 4px 6px -1px rgba(0,0,0,0.02); display: flex; flex-direction: column; }
.gallery-card:hover { transform: translateY(-5px); box-shadow: 0 10px 25px -5px rgba(0,0,0,0.08); }
.gallery-img { width: 100%; height: 180px; object-fit: cover; background: #f8fafc; border-bottom: 1px solid #e2e8f0; }
.gallery-info { padding: 22px; display: flex; flex-direction: column; flex-grow: 1; }
.gallery-title { font-weight: 700; font-size: 1.25em; margin-bottom: 8px; color: #0f172a; }
.gallery-desc { font-size: 1em; color: #475569; margin-bottom: 18px; line-height: 1.6; flex-grow: 1; }
.gallery-links a { display: inline-block; color: #fff; background: #0f172a; font-size: 0.9em; font-weight: 600; text-decoration: none; padding: 6px 14px; border-radius: 6px; transition: background 0.2s; text-align: center; }
.gallery-links a:hover { background: #1e293b; text-decoration: none;}
.gallery-tag { display: inline-flex; align-items: center; padding: 4px 12px; border-radius: 20px; font-size: 0.72rem; font-weight: 700; margin-bottom: 12px; letter-spacing: 0.4px; text-transform: uppercase; box-shadow: 0 1px 2px rgba(0,0,0,0.03); }
.gallery-tag::before { content: ""; display: inline-block; width: 6px; height: 6px; border-radius: 50%; margin-right: 8px; }
.tag-comprehensive { background: #eef2ff; color: #4f46e5; border: 1px solid #e0e7ff; }
.tag-comprehensive::before { background: #4f46e5; }
.tag-research { background: #f0fdf4; color: #16a34a; border: 1px solid #dcfce7; }
.tag-research::before { background: #16a34a; }
.tag-engineering { background: #fffbeb; color: #d97706; border: 1px solid #fef3c7; }
.tag-engineering::before { background: #d97706; }

.bullet-list { padding-left: 20px; font-family: -apple-system, sans-serif; }
.bullet-list li { margin-bottom: 0.6rem; font-size: 1rem; color: #334155; line-height: 1.6; }

.view-more-container { text-align: center; margin-top: 1.5rem; margin-bottom: 3.5rem; }
.view-more-btn { display: inline-block; padding: 12px 28px; background: #f8fafc; border: 1px solid #cbd5e1; border-radius: 8px; color: #0f172a; text-decoration: none; font-weight: 600; font-size: 1rem; font-family: -apple-system, BlinkMacSystemFont, "Roboto", sans-serif; transition: all 0.2s; }
.view-more-btn:hover { background: #f1f5f9; border-color: #94a3b8; transform: translateY(-2px); box-shadow: 0 4px 6px -1px rgba(0,0,0,0.05); }

@media (max-width: 768px) { .pub-item { flex-direction: column; } .pub-image { width: 100%; max-height: 200px; } }

/* Smooth inner scroll */
html { scroll-behavior: smooth; }

/* GITHUB PROJECTS STYLES (Matt Deitke Style) */
.github-projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
  gap: 20px;
  margin-bottom: 3rem;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
}
.github-project-card {
  border: 1px solid #d0d7de;
  border-radius: 8px;
  padding: 20px;
  background-color: #ffffff;
  text-decoration: none !important;
  display: flex;
  flex-direction: column;
  transition: all 0.2s ease;
  box-shadow: 0 1px 3px rgba(0,0,0,0.05);
}
.github-project-card:hover {
  border-color: #0969da;
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.08);
}
.github-project-header {
  display: flex;
  align-items: center;
  gap: 8px;
  margin-bottom: 12px;
}
.github-icon {
  fill: #636c76;
}
.github-project-name {
  font-weight: 600;
  font-size: 1.1rem;
  color: #0969da;
}
.github-project-description {
  font-size: 0.95rem;
  color: #57606a;
  line-height: 1.5;
  margin-bottom: 20px;
  flex-grow: 1;
}
.github-project-footer {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.github-project-stats {
  display: flex;
  align-items: center;
  gap: 16px;
  font-size: 0.85rem;
  color: #57606a;
}
.github-project-stat {
  display: flex;
  align-items: center;
  gap: 4px;
}
.language-color {
  width: 12px;
  height: 12px;
  border-radius: 50%;
  display: inline-block;
}
.stat-icon {
  fill: #57606a;
}
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "<https://cdn.jsdelivr.net/gh/>" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "<https://raw.githubusercontent.com/>" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<div class="intro-text">
  <p>I am a researcher in the School of Mechanical Engineering at <strong>Tongji University</strong>, specializing in Heating, Ventilation and Air Conditioning (HVAC). I am currently a visiting scholar at the <strong>Center for the Built Environment (CBE), UC Berkeley</strong>.</p>
  
  <p>My research focuses on energy forecasting, optimal operation and control for HVAC systems in commercial buildings using data science technologies. Specifically, I leverage <strong>causal science</strong> and <strong>causal machine learning</strong> to enhance the physical principles underlying these models in the context of building energy data. I am also interested in automating energy management and optimization tasks with <strong>large language models (LLM)</strong>, primarily focusing on automating energy efficiency diagnosis using multi-source building data.</p>
</div>

<h2 class="section-title" id="news">📰 News</h2>
<div class="news-grid">
  <div class="news-card">
    <div class="news-date">Dec 2024</div>
    <div class="news-desc">Started as a Visiting PhD student at the Center for the Built Environment (CBE), UC Berkeley.</div>
  </div>
  <div class="news-card">
    <div class="news-date">Aug 2024</div>
    <div class="news-desc">Our paper "Exploring automated energy optimization with unstructured building data..." was accepted by <em>Energy and Buildings</em>.</div>
  </div>
  <div class="news-card">
    <div class="news-date">Jul 2023</div>
    <div class="news-desc">Started Applied Energy Trainee Program as a Research Intern at Shenzhen Institute of Building Research Co., Ltd.</div>
  </div>
</div>

<h2 class="section-title" id="education">🎓 Education</h2>
<ul class="exp-list">
  <li class="exp-item">
    <div class="exp-date">2024.12 - 2025.12</div>
    <div class="exp-title">Visiting PhD Student</div>
    <div class="exp-desc"><a href="https://cbe.berkeley.edu/">Center for the Built Environment (CBE), UC Berkeley</a>. Working with Dr. Carlos Duarte and Dr. Paul Raftery, supervised by Prof. Stefano Schiavon.</div>
  </li>
  <li class="exp-item">
    <div class="exp-date">2019.09 - 2025.12</div>
    <div class="exp-title">Ph.D in Mechanical Engineering</div>
    <div class="exp-desc">School of Mechanical Engineering, Tongji University. Supervised by Prof. <a href="https://a434.tongji.edu.cn/english/GROUP/Team_leader.htm">Peng Xu</a>. GPA 4.93/5.0.</div>
  </li>
  <li class="exp-item">
    <div class="exp-date">2015.09 - 2019.06</div>
    <div class="exp-title">B.E. in Built Environment and Energy Application Engineering</div>
    <div class="exp-desc">School of Mechanical Engineering, Tongji University. GPA 4.61/5.0.</div>
  </li>
</ul>

<h2 class="section-title" id="experience">💼 Work Experience</h2>
<ul class="exp-list">
  <li class="exp-item">
    <div class="exp-date">2023.07 - 2023.08</div>
    <div class="exp-title">Research Intern</div>
    <div class="exp-desc">DC Building Lab, <a href="https://szibr.com/en/">Shenzhen Institute of Building Research Co., Ltd.</a> Supervised by Dr. Yemao Li, Zhihui Deng, and Dr. Bin Hao. Focus on Demand-side Energy Flexibility Management Optimization Considering Occupant Behavior.</div>
  </li>
</ul>

<h2 class="section-title" id="selected-publications">📝 Selected Publications</h2>
<ul class="pub-list">
  <li class="pub-item">
    <div class="pub-image">
      <img src="images/paper/Xiao-2024-multiagent.jpg" alt="LLM Framework Abstract Image">
    </div>
    <div class="pub-content">
      <div class="pub-title">Exploring automated energy optimization with unstructured building data: A multi-agent based framework leveraging large language models <span class="pub-badge">Q1, IF=6.6</span></div>
      <div class="pub-authors"><b>T. Xiao</b>, P. Xu</div>
      <div class="pub-venue">Energy and Buildings, 2024</div>
      <div class="pub-links">
        <a href="https://doi.org/10.1016/j.enbuild.2024.114691" target="_blank">📄 Paper</a>
      </div>
    </div>
  </li>
  <li class="pub-item">
    <div class="pub-image">
      <img src="images/paper/Xiao-2022-mislabel.jpg" alt="Paper Image">
    </div>
    <div class="pub-content">
      <div class="pub-title">An interpretable method for identifying mislabeled commercial building based on temporal feature extraction and ensemble classifier <span class="pub-badge">Q1, IF=11.7</span></div>
      <div class="pub-authors"><b>T. Xiao</b>, P. Xu, R. Ding, Z. Chen</div>
      <div class="pub-venue">Sustainable Cities and Society, 2022</div>
      <div class="pub-links">
        <a href="https://doi.org/10.1016/j.scs.2021.103635" target="_blank">📄 Paper</a>
      </div>
    </div>
  </li>
  <li class="pub-item">
    <div class="pub-image">
      <img src="images/paper/Xiao-2022-crossbuilding.jpg" alt="Paper Image">
    </div>
    <div class="pub-content">
      <div class="pub-title">Status quo and opportunities for building energy prediction in limited data Context—Overview from a competition <span class="pub-badge">Q1, IF=11.2</span></div>
      <div class="pub-authors"><b>T. Xiao</b>, P. Xu, R. He, H. Sha</div>
      <div class="pub-venue">Applied Energy, 2022</div>
      <div class="pub-links">
        <a href="https://doi.org/10.1016/j.apenergy.2021.117829" target="_blank">📄 Paper</a>
      </div>
    </div>
  </li>
</ul>

<div class="view-more-container">
  <a href="/publications/" class="view-more-btn">View All Publications & Patents ➔</a>
</div>

<h2 class="section-title" id="projects">🚀 Project Gallery</h2>
<div class="project-gallery">
  <div class="gallery-card">
    <img src="images/projects/overview.png" class="gallery-img" alt="Energy Detective Competition">
    <div class="gallery-info">
      <div class="gallery-tag tag-comprehensive">Comprehensive Project</div>
      <div class="gallery-title">Energy Detective Competition</div>
      <div class="gallery-desc">Student lead for the inaugural building energy forecasting competition. Orchestrated full-cycle operations for 195 global participants: from data curation to first-author SCI publication.</div>
      <div class="gallery-links">
        <a href="/projects/energyPredictionCompetition/">Project Details →</a>
      </div>
    </div>
  </div>
  <!--<div class="gallery-card">
    <img src="https://via.placeholder.com/600x350/e1f0fe/1a1a1a?text=Awesome+List+Project" class="gallery-img" alt="Awesome Project">
    <div class="gallery-info">
      <div class="gallery-tag tag-research">Research Project</div>
      <div class="gallery-title">Awesome Building Energy Optimization</div>
      <div class="gallery-desc">A curated collection of resources, papers, and algorithms focusing on modern building energy control and data-driven methods.</div>
      <div class="gallery-links">
        <a href="https://github.com/SheltonXiao" target="_blank">View on GitHub →</a>
      </div>
    </div>
  </div>-->
</div>

<h2 class="section-title" id="github-projects">💻 GitHub Projects</h2>
{% include github_projects.html %}

<h2 class="section-title" id="awards">🏆 Selected Honors & Awards</h2>
<ul class="bullet-list">
  <li><strong>2022</strong> - Outstanding Doctoral Scholarship, Tongji University.</li>
  <li><strong>2022</strong> - Outstanding Student, Tongji University.</li>
  <li><strong>2022</strong> - <a href="https://github.com/datawhalechina">Datawhale</a> Contributor.</li>
  <li><strong>2019</strong> - Outstanding Graduate, Shanghai.</li>
  <li><strong>2017</strong> - Second Prize of National Mathematical Contest in Modeling, China Society of Industrial and Applied Mathematics.</li>
</ul>

<h2 class="section-title" id="talks">💬 Selected Presentations</h2>
<ul class="exp-list">
  <li class="exp-item">
    <div class="exp-date">2025</div>
    <div class="exp-title">Toward Automated Building Performance Analysis with LLM-Based Agents</div>
    <div class="exp-desc"><em>BuildNext: A Global Seminar for Young Researchers.</em> @Syracuse, NY, USA.</div>
  </li>
  <li class="exp-item">
    <div class="exp-date">2025</div>
    <div class="exp-title">Causal analysis of distribution shift in building energy models</div>
    <div class="exp-desc"><em>WeLL Seminar Spring Student Spotlight Talk.</em> @Berkeley, CA, USA. <a href="https://sheltonxiao.github.io/images/files/WeLL2024.jpg">[Picture]</a></div>
  </li>
</ul>
<div class="view-more-container">
  <a href="/talks/" class="view-more-btn">View All Presentations & Talks ➔</a>
</div>
