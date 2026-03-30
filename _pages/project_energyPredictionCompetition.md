---
permalink: /projects/energyPredictionCompetition/
title: "\"Energy Detective\" Building Energy Forecasting Competition"
author_profile: true
---

<style>
/* ===== PROJECT PAGE STYLES ===== */
.proj-container {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  margin-top: 1.5rem;
  color: #1e293b;
}

/* --- HERO --- */
.proj-hero {
  background: linear-gradient(135deg, #0f172a 0%, #1a3a5c 100%);
  border-radius: 16px;
  padding: 48px 36px;
  text-align: center;
  color: #fff;
  margin-bottom: 2.5rem;
  box-shadow: 0 20px 40px rgba(0,0,0,0.15);
}
.proj-hero-eyebrow {
  font-size: 0.85rem;
  font-weight: 600;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: #93c5fd;
  margin-bottom: 1rem;
}
.proj-hero h1 {
  margin: 0 0 8px 0;
  font-size: 2.2rem;
  font-weight: 800;
  color: #fff;
  letter-spacing: -0.02em;
  line-height: 1.2;
}
.proj-hero .hero-subtitle {
  font-size: 1rem;
  color: #94a3b8;
  margin: 0 auto 24px auto;
  max-width: 600px;
  line-height: 1.65;
}
.hero-tags { display: flex; flex-wrap: wrap; gap: 8px; justify-content: center; margin-bottom: 28px; }
.hero-tag { background: rgba(255,255,255,0.12); border: 1px solid rgba(255,255,255,0.2); border-radius: 20px; padding: 5px 14px; font-size: 0.8rem; color: #e2e8f0; }
.hero-meta { display: flex; flex-wrap: wrap; gap: 16px; justify-content: center; font-size: 0.88rem; color: #94a3b8; }
.hero-meta span { display: flex; align-items: center; gap: 5px; }
.hero-links { display: flex; flex-wrap: wrap; gap: 10px; justify-content: center; margin-top: 24px; }
.btn-hero {
  display: inline-flex; align-items: center; gap: 6px;
  padding: 10px 20px;
  background: rgba(255,255,255,0.15);
  border: 1px solid rgba(255,255,255,0.3);
  border-radius: 8px;
  color: #fff;
  text-decoration: none;
  font-weight: 600;
  font-size: 0.9rem;
  transition: all 0.2s;
}
.btn-hero:hover { background: rgba(255,255,255,0.25); text-decoration: none; color: #fff; }
.btn-hero.btn-primary { background: #fff; color: #0f172a; border-color: #fff; }
.btn-hero.btn-primary:hover { background: #e2e8f0; color: #0f172a; }

/* --- STATS ROW --- */
.stats-row {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(130px, 1fr));
  gap: 14px;
  margin-bottom: 2.5rem;
}
.stat-card {
  background: #fff;
  border: 1px solid #e2e8f0;
  border-radius: 12px;
  padding: 20px 12px;
  text-align: center;
  box-shadow: 0 2px 8px rgba(0,0,0,0.04);
}
.stat-number { font-size: 2rem; font-weight: 800; color: #0369a1; line-height: 1; margin-bottom: 4px; }
.stat-label { font-size: 0.78rem; color: #64748b; font-weight: 500; line-height: 1.4; }

/* --- SECTIONS --- */
.proj-section { margin-bottom: 3rem; }
.proj-section h2 {
  font-size: 1.5rem;
  font-weight: 700;
  color: #0f172a;
  border-bottom: 2px solid #f1f5f9;
  padding-bottom: 0.5rem;
  margin-top: 0;
  margin-bottom: 1.4rem;
  display: flex;
  align-items: center;
  gap: 8px;
}
.proj-section p { font-size: 1rem; line-height: 1.8; color: #334155; margin-bottom: 1.2rem; }
.proj-section ul { font-size: 1rem; line-height: 1.8; color: #334155; padding-left: 22px; }
.proj-section li { margin-bottom: 0.6rem; }

/* --- ROLE SECTION --- */
.role-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
  margin-top: 1.5rem;
}
.role-card {
  background: #fff;
  border: 1px solid #e2e8f0;
  border-radius: 14px;
  padding: 24px;
  position: relative;
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
  box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);
}
.role-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
  border-color: #3b82f6;
}
.role-icon {
  font-size: 1.8rem;
  margin-bottom: 12px;
  display: block;
}
.role-card h3 {
  font-size: 1.1rem;
  font-weight: 700;
  color: #0f172a;
  margin: 0 0 12px 0;
  display: flex;
  align-items: center;
  gap: 10px;
}
.role-card ul {
  font-size: 0.95rem;
  color: #475569;
  padding-left: 18px;
  margin: 0 0 16px 0;
  line-height: 1.6;
}
.role-card li { margin-bottom: 8px; }
.role-badge {
  display: inline-flex;
  align-items: center;
  padding: 4px 10px;
  background: #eff6ff;
  color: #1d4ed8;
  font-size: 0.75rem;
  font-weight: 600;
  border-radius: 6px;
  border: 1px solid #dbeafe;
}

/* --- INSIGHT CARDS --- */
.insight-list { display: flex; flex-direction: column; gap: 14px; margin-top: 1.2rem; }
.insight-card { border-left: 4px solid #0369a1; padding: 14px 18px; background: #f0f9ff; border-radius: 0 8px 8px 0; }
.insight-card strong { font-size: 1rem; color: #0f172a; display: block; margin-bottom: 4px; }
.insight-card p { margin: 0; font-size: 0.95rem; color: #334155; line-height: 1.6; }

/* --- IMAGE PLACEHOLDER --- */
.img-placeholder {
  background: #f1f5f9;
  border: 2px dashed #cbd5e1;
  border-radius: 12px;
  padding: 40px 20px;
  text-align: center;
  color: #94a3b8;
  font-style: italic;
  font-size: 0.9rem;
  margin-bottom: 1.5rem;
}

/* --- RESOURCES --- */
.resource-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 12px; margin-top: 1.2rem; }
.resource-card {
  border: 1px solid #e2e8f0;
  border-radius: 10px;
  padding: 16px 18px;
  background: #fff;
  text-decoration: none;
  transition: all 0.2s;
}
.resource-card:hover { border-color: #0369a1; box-shadow: 0 4px 12px rgba(0,0,0,0.06); transform: translateY(-2px); }
.resource-card-label { font-size: 0.75rem; font-weight: 700; text-transform: uppercase; letter-spacing: 0.08em; color: #0369a1; margin-bottom: 4px; }
.resource-card-title { font-size: 0.92rem; font-weight: 600; color: #1e293b; }
.resource-placeholder { color: #94a3b8; font-style: italic; font-size: 0.9rem; }

/* --- PERSONAL NOTE --- */
.personal-note {
  background: linear-gradient(135deg, #f0fdf4, #ecfdf5);
  border: 1px solid #bbf7d0;
  border-radius: 12px;
  padding: 24px 28px;
  margin-top: 3rem;
}
.personal-note p { font-size: 1.05rem; line-height: 1.8; color: #166534; margin: 0; font-style: italic; }
</style>

<div class="proj-container">

<!-- ===== HERO ===== -->
<div class="proj-hero">
  <div class="proj-hero-eyebrow">Competition Project · 2020</div>
  <h1>Energy Detective Building Energy Forecasting Competition<br><span style="font-size:1.1rem;font-weight:400;color:#93c5fd;letter-spacing:0;">第一届"能耗侦探"建筑能耗预测竞赛</span></h1>
  <p class="hero-subtitle">
    Student lead for competition operations, dataset curation, scoring infrastructure, and post-competition research analysis.
  </p>
  <div class="hero-tags">
    <span class="hero-tag">Building Energy Forecasting</span>
    <span class="hero-tag">Competition Organization</span>
    <span class="hero-tag">Data Infrastructure</span>
    <span class="hero-tag">Limited-Data Setting</span>
    <span class="hero-tag">Research Translation</span>
  </div>
  <div class="hero-meta">
    <span>📅 Feb 2020 – Dec 2020</span>
    <span>👤 Student Lead</span>
    <span>🏆 195 Participants · 7 Countries</span>
  </div>
  <div class="hero-links">
    <a href="#resources" class="btn-hero btn-primary">📄 Resources & Links</a>
    <a href="#task-design" class="btn-hero">🔍 Task Design</a>
  </div>
</div>

<!-- ===== STATS ===== -->
<div class="stats-row">
  <div class="stat-card"><div class="stat-number">195</div><div class="stat-label">Participants</div></div>
  <div class="stat-card"><div class="stat-number">7</div><div class="stat-label">Countries & Regions</div></div>
  <div class="stat-card"><div class="stat-number">89</div><div class="stat-label">Registered Teams</div></div>
  <div class="stat-card"><div class="stat-number">65</div><div class="stat-label">Institutions</div></div>
  <div class="stat-card"><div class="stat-number">56</div><div class="stat-label">Competing Teams</div></div>
  <div class="stat-card"><div class="stat-number">140</div><div class="stat-label">Valid Submissions</div></div>
  <div class="stat-card"><div class="stat-number">10</div><div class="stat-label">Leaderboard Updates</div></div>
  <div class="stat-card"><div class="stat-number">31</div><div class="stat-label">Technical Reports</div></div>
</div>

<!-- ===== OVERVIEW ===== -->
<div class="proj-section">
  <h2>📖 Project Overview</h2>
  <p>
    In 2020, I served as the <strong>student lead</strong> for organizing the first "Energy Detective" building energy forecasting competition. The competition was centered on a research-driven challenge: predicting the energy consumption of a <em>new building with no historical energy data</em>, using only limited physical description and data from 20 reference buildings.
  </p>
  <p>
    Beyond organizing the logistics, my role was end-to-end. I built the scoring infrastructure, curated the dataset, managed communications with 195 participants across 7 countries, led the award ceremony, and contributed to the post-competition result analysis that became a conference presentation and an SCI journal paper.
  </p>
  <div style="text-align:center; margin-top:1.2rem;">
    <img src="/images/projects/dynamic_leaderboard.gif?v=2"
         alt="Dynamic leaderboard showing submission progression throughout the competition"
         style="max-width:78%; border-radius:10px; box-shadow:0 4px 14px rgba(0,0,0,0.08);">
    <p style="font-size:0.8rem; color:#94a3b8; margin-top:0.4rem;">Dynamic leaderboard — submission progression during the competition</p>
  </div>
  <!--<div class="img-placeholder" style="margin-top:1rem;">
    [📷 封面图 / 颁奖典礼照片 — 请替换此占位符]<br>
    <small>Cover photo or award ceremony screenshot</small>
  </div>-->
</div>

<!-- ===== PARTICIPANTS SECTION ===== -->
<div class="proj-section">
  <h2>🌏 Who Participated</h2>
  <p>The competition attracted 195 participants from universities, research institutes, and industry companies across 7 countries and regions, including mainland China, Singapore, Germany, the United Kingdom, the United States, Australia, and Hong Kong.</p>

  <!-- Word Cloud + Map side by side (optimized alignment) -->
  <div style="display:flex; gap:24px; align-items:center; flex-wrap:wrap; justify-content:center; margin-top:1.5rem;">
    <!-- Column 1 -->
    <div style="flex:1; min-width:300px; max-width:45%; text-align:center;">
      <img src="/images/projects/wordcloud_en.png" alt="Participating institutions word cloud"
           style="width:100%; height:auto; border-radius:10px; box-shadow: 0 4px 14px rgba(0,0,0,0.06);">
      <p style="font-size:0.8rem; color:#64748b; margin-top:0.8rem; line-height:1.4;">
        <strong>Participating Institutions</strong><br>Word cloud (registration data)
      </p>
    </div>
    <!-- Column 2 -->
    <div style="flex:1; min-width:300px; max-width:45%; text-align:center;">
      <img src="/images/projects/participant_map.png" alt="Geographic distribution of participants"
           style="width:100%; height:auto; border-radius:10px; box-shadow: 0 4px 14px rgba(0,0,0,0.06);">
      <p style="font-size:0.8rem; color:#64748b; margin-top:0.8rem; line-height:1.4;">
        <strong>World Distribution</strong><br>(195 participants · 7 regions)
      </p>
    </div>
  </div>
</div>

<!-- ===== WHY IT MATTERS ===== -->
<div class="proj-section">
  <h2>💡 Why It Matters</h2>
  <div class="insight-list">
    <div class="insight-card">
      <strong>Connecting research problems to community practice</strong>
      <p>Rather than working on a model in isolation, we translated a meaningful research problem, limited-data building energy prediction, into a structured, reproducible competition task that dozens of teams could engage with simultaneously.</p>
    </div>
    <div class="insight-card">
      <strong>A realistic, not a benchmark, challenge</strong>
      <p>The task was fully blind: no historical energy data for the target building, only limited physical specs. This is much closer to real engineering practice than leaderboard-style benchmark datasets.</p>
    </div>
    <div class="insight-card">
      <strong>Producing methodological insight, not just rankings</strong>
      <p>The post-competition analysis revealed actionable findings: summer HVAC load is more predictable than winter; feature engineering remains the key bottleneck; and white-box/black-box hybrid methods are a promising direction.</p>
    </div>
  </div>
</div>

<!-- ===== TASK DESIGN ===== -->
<div class="proj-section" id="task-design">
  <h2>🎯 Competition Task Design</h2>
  <p>
    The competition focused on a <strong>limited-data forecasting setting</strong>: participants were asked to predict the 2017 annual energy consumption of a target office building. The target building had <em>no historical energy records</em>, only limited physical information (drawings, envelope specs, HVAC configuration). Participants could leverage:
  </p>
  <ul>
    <li>Measured energy data (2015–2017) from <strong>20 reference office buildings</strong></li>
    <li>Basic physical characteristics of all buildings</li>
    <li>Measured weather data for the same period</li>
  </ul>
  <p>Evaluation metric: <strong>CV-RMSE</strong>. This design required methods capable of cross-building knowledge transfer, physics-informed feature engineering, and generalization under data scarcity.</p>
  <div style="text-align:center; margin-top:1.5rem;">
    <img src="/images/projects/competition_problem.png"
         alt="Competition task design: Predicting 2017 energy from 20 reference buildings"
         style="max-width:85%; border-radius:12px; box-shadow:0 10px 30px rgba(0,0,0,0.1);">
    <p style="font-size:0.85rem; color:#64748b; margin-top:0.8rem; font-style:italic;">
      Competition Task Illustration: Leveraging reference building data to predict a target building's performance under data scarcity.
    </p>
  </div>
</div>

<!-- ===== MY ROLE ===== -->
<div class="proj-section">
  <h2>⚙️ My Role & Leadership</h2>
  <div class="role-grid">
    <!-- Category 1 -->
    <div class="role-card">
      <span class="role-icon">📦</span>
      <h3>Dataset & Task Design</h3>
      <ul>
        <li>Processed raw meter data and physical model specs into a publishable competition dataset</li>
        <li>Architected the "limited-data" task structure and documentation</li>
      </ul>
      <div class="role-badge">Key Highlight: Cross-building transfer dataset</div>
    </div>

    <!-- Category 2 -->
    <div class="role-card">
      <span class="role-icon">📊</span>
      <h3>Infrastructure & Operations</h3>
      <ul>
        <li>Built automated scoring pipeline for CV-RMSE evaluation</li>
        <li>Managed 140+ valid submissions and real-time leaderboard updates</li>
        <li>Implemented data deduplication and validation protocols</li>
      </ul>
      <div class="role-badge">Key Highlight: Automated evaluation pipeline</div>
    </div>

    <!-- Category 3 -->
    <div class="role-card">
      <span class="role-icon">📢</span>
      <h3>Communications & Scaling</h3>
      <ul>
        <li>Managed public outreach: 5+ WeChat technical articles published</li>
        <li>Direct communication with 195 participants from 7 countries</li>
        <li>Designed all competition visual identities and awards</li>
      </ul>
      <div class="role-badge">Key Highlight: Global community engagement</div>
    </div>

    <!-- Category 4 -->
    <div class="role-card">
      <span class="role-icon">🤝</span>
      <h3>Coordination & Leadership</h3>
      <ul>
        <li>Liaised between university, sponsors, and international experts</li>
        <li>Hosted and moderated the virtual Award Ceremony</li>
        <li>Supervised the shortlisted team report evaluation process</li>
      </ul>
      <div class="role-badge">Key Highlight: End-to-end event management</div>
    </div>

    <!-- Category 5 -->
    <div class="role-card" style="grid-column: span 1; border-color: #bfdbfe; background: #f0f9ff;">
      <span class="role-icon">📝</span>
      <h3>Research Translation</h3>
      <ul>
        <li>Led the post-competition result analysis and methodological summary</li>
        <li>Presented findings at the National HVAC Simulation Annual Meeting</li>
        <li><strong>First-authored</strong> SCI journal paper in Applied Energy (2022)</li>
      </ul>
      <div class="role-badge" style="background: #3b82f6; color: #fff; border: none;">Impact: Top-tier Journal Publication</div>
    </div>
  </div>
</div>

<!-- ===== KEY FINDINGS ===== -->
<div class="proj-section">
  <h2>🔬 Key Findings from Result Analysis</h2>
  <div class="insight-list">
    <div class="insight-card">
      <strong>Best CV-RMSE achieved: 0.67</strong>
      <p>Under fully blind conditions (no historical target data), the best submission reached a CV-RMSE of 0.67, establishing a concrete baseline for cross-building transfer in limited-data settings. (MAPE analysis pending.)</p>
    </div>
    <div class="insight-card">
      <strong>Summer is easier than winter</strong>
      <p>Summer AC energy prediction outperformed winter heating predictions consistently across methods, suggesting this is the more tractable sub-problem.</p>
    </div>
    <div class="insight-card">
      <strong>Feature engineering remains the bottleneck</strong>
      <p>Latent features, particularly building characteristics not directly available in specs, were consistently underutilized, pointing to a major open research opportunity.</p>
    </div>
    <div class="insight-card">
      <strong>White-box + black-box hybrid methods are promising</strong>
      <p>Despite their complexity, physics-informed approaches combined with data-driven models showed the most potential in this limited-data regime.</p>
    </div>
  </div>
</div>

<!-- ===== RESOURCES ===== -->
<div class="proj-section" id="resources">
  <h2>📎 Resources & Outputs</h2>
  <div class="resource-grid">
    <div class="resource-card">
      <div class="resource-card-label">Paper</div>
      <div class="resource-card-title">
        <a href="https://doi.org/10.1016/j.apenergy.2021.117829" target="_blank">Status quo and opportunities for building energy prediction in limited data context (Applied Energy, 2022)</a>
      </div>
    </div>
    <div class="resource-card">
      <div class="resource-card-label">Dataset</div>
      <div class="resource-card-title">
        <a href="https://zenodo.org/records/6590976" target="_blank">Energy Detective Building Energy Forecasting Competition Dataset</a>
        <a href="https://www.researchgate.net/publication/360928691_XuPengResearchGroupEnergyDetective2020_dataset" target="_blank">(Alternative Link)</a>
      </div>
    </div>
   <!-- *<div class="resource-card">
      <div class="resource-card-label">Result Analysis Slides</div>
      <div class="resource-card-title resource-placeholder">[PPT/报告链接 — 请补充]</div>
    </div>
    <div class="resource-card">
      <div class="resource-card-label">Competition Brief</div>
      <div class="resource-card-title resource-placeholder">[赛题说明 PDF / 网页 — 请补充]</div>
    </div>
    <div class="resource-card">
      <div class="resource-card-label">WeChat Posts (×5)</div>
      <div class="resource-card-title resource-placeholder">[推文链接 1–5 — 请补充]</div>
    </div>-->
    <div class="resource-card">
      <div class="resource-card-label">Award Announcement</div>
      <div class="resource-card-title">
        <a href="https://github.com/XuPengResearchGroup/EnergyDetective2020">Final leaderboard and winner solutions</a>
      </div>
    </div>
  </div>
</div>

<!-- ===== PERSONAL NOTE ===== -->
<div class="personal-note">
  <p>
    What I valued most about this project was not just that we ran a competition to completion — it was that we turned a scattered set of practical tasks (data cleaning, scoring algorithms, logistics, and reporting) into a coherent, research-facing workflow. For me, it was the first time I experienced how <strong>task definition, data organization, evaluation protocol, and community engagement</strong> are just as important to a research contribution as the model itself.
  </p>
</div>

</div>
