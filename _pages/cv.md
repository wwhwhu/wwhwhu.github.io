---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
/* ① 调整条目间距 */
.archive__item {
  margin-bottom: -20px !important; /* 原来约2rem，这里减半 */
}
  
/* ② 设置链接颜色 */
.archive__item a {
  color: #2b6cb0;
  text-decoration: none;
  font-weight: 500;
}

.archive__item a:hover {
  color: #1a4a8e;
  text-decoration: underline;
}

.cv-section {
  display: flex;
  flex-direction: column;
  gap: 1.8rem;
  margin-top: 2rem;
}

.cv-content p {
  text-align: justify;
}

/* 每个条目整体容器 */
.cv-item {
  display: flex;
  align-items: flex-start;
  gap: 20px;
}

/* 左侧 Logo 样式 */
.cv-logo {
  flex: 0 0 70px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.cv-logo img {
  width: 70px;
  height: 70px;
  object-fit: contain;
  border-radius: 10px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}

/* 右侧文字区域 */
.cv-content {
  flex: 1;
}
.cv-content h3 {
  margin: 0;
  font-size: 1.1rem;
  font-weight: 600;
}
.cv-content p {
  margin: 0.2em 0;
  color: #444;
  line-height: 1.5;
}
.cv-date {
  font-size: 0.9rem;
  color: #666;
}
.cv-role {
  font-weight: 500;
  color: #2b6cb0;
}
.cv-content a {
  color: #2b6cb0;
  text-decoration: none; /* 去掉下划线 */
  font-weight: 500;
}

.cv-content a:hover {
  color: #1a4a8e; /* 鼠标悬停时稍深一点 */
  text-decoration: underline;
}

.language-card {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  flex-wrap: wrap;
  background: #fff;
  border-radius: 10px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.08);
  padding: 20px 25px;
  margin-top: 10px;
  margin-bottom: 30px;
}

.language-block {
  flex: 1;
  min-width: 180px;
  text-align: center;
}

.language-name {
  color: #2b6cb0;
  font-weight: 600;
  font-size: 1.05rem;
}

.language-level {
  margin-top: 5px;
  font-size: 0.95rem;
  color: #222;
}

.skill-card {
  display: grid;
  grid-template-columns: repeat(2, 1fr); /* ✅ 固定两列 */
  grid-template-rows: repeat(2, auto);   /* ✅ 固定两行 */
  gap: 30px 60px;                        /* 控制间距 */
  background: #fff;
  border-radius: 10px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.08);
  padding: 30px 40px;
  margin-top: 40px;                      /* 与上一节的距离 */
}

.skill-block {
  text-align: left;
}

.skill-name {
  color: #2b6cb0;                        /* 与 Languages 颜色一致 */
  font-weight: 600;
  font-size: 1.05rem;
  margin-bottom: 8px;
}

.skill-list {
  list-style-type: disc;
  padding-left: 20px;
  margin: 0;
}

.skill-list li {
  font-size: 0.95rem;
  color: #222;
  line-height: 1.5;
}
</style>

🎓 Education
======

<div class="cv-section">

  <div class="cv-item">
    <div class="cv-logo">
      <img src="/images/logos/whu_logo.png" alt="Wuhan University">
    </div>
    <div class="cv-content">
      <h3>Wuhan University</h3>
      <p>
      <span class="cv-role">M.Sc. in Computer Science and Technology</span> — 
  Advisors: <a href="https://scholar.google.com/citations?user=rRsraIwAAAAJ&hl=en" target="_blank">Prof. Dazhao Cheng</a> 
  and <a href="https://scholar.google.com/citations?user=cl9QFQ8AAAAJ&hl=zh-CN" target="_blank">Prof. Chuang Hu</a>.
    </p>
      <p>GPA: <strong>94.45 / 100.00</strong> (ranking <strong>1st</strong> among 187 students)</p>
      <p class="cv-date">Sep 2023 – Jun 2026 (expected)</p>
    </div>
  </div>

  <div class="cv-item">
    <div class="cv-logo">
      <img src="/images/logos/whu_logo.png" alt="Wuhan University">
    </div>
    <div class="cv-content">
      <h3>Wuhan University</h3>
      <p>
        <span class="cv-role">B.Eng. in Computer Science and Technology</span> —
        Advisor: <a href="https://yiligong-whu.github.io/yiligong_homepage" target="_blank">Prof. Yili Gong</a>.
      </p>
      <p>GPA: <strong>91.26 / 100.00</strong></p>
      <p class="cv-date">Sep 2019 – Jun 2023</p>
    </div>
  </div>

</div>

---

🧪 Academic Internship
======

<div class="cv-section">

  <div class="cv-item">
    <div class="cv-logo">
      <img src="/images/logos/NU_logo.png" alt="Northwestern University">
    </div>
    <div class="cv-content">
      <h3>Northwestern University</h3>
      <p>
      <span class="cv-role">Research Intern</span> — Advised by 
        <a href="https://kaize0409.github.io/" target="_blank">Prof. Kaize Ding</a>, 
        <a href="https://franciscoliu.github.io/" target="_blank">Dr. Zheyuan Liu</a>, and <a href="https://gcyzsl.github.io/" target="_blank">Dr. Chongyang Gao</a>.
      </p>
      <p class="cv-date">May 2025 – Sep 2025</p>
      <p>
        Conducted research on <strong>Robust Unlearning for Large Language Models against Relearning Attacks</strong>. Employed <strong>bi-level feedback-guided optimization</strong> and adversarial parameter perturbation to enhance model resilience. The project’s findings have been submitted to <em>ICLR 2026</em>.
      </p>
    </div>
  </div>
</div>

---

💼 Industrial and Opensource Experiences
======

<div class="cv-section">

  <div class="cv-item">
    <div class="cv-logo">
      <img src="/images/logos/OPPO-logo.png" alt="OPPO Inc.">
    </div>
    <div class="cv-content">
      <h3>OPPO Inc.</h3>
      <p><span class="cv-role">Research Intern — Mobile System Performance Optimization Group</span></p>
      <p class="cv-date">Nov 2024 – Sep 2025</p>
      <p>
        Led the project <strong>Reinforcement Learning-Based Frequency Adjustment and Its Generalization in Mobile Devices</strong>.  
        Developed a <strong>DQN-based reinforcement learning</strong> framework for dynamic CPU frequency scaling to balance performance and power consumption. Also introduced a <strong>transfer learning</strong> scheme for fast adaptation across heterogeneous mobile workloads.
      </p>
    </div>
  </div>

  <div class="cv-item">
    <div class="cv-logo">
      <img src="/images/logos/OPPO-logo.png" alt="OPPO Inc.">
    </div>
    <div class="cv-content">
      <h3>OPPO Inc.</h3>
      <p><span class="cv-role">Research Intern — Mobile System Performance Optimization Group</span></p>
      <p class="cv-date">Nov 2022 – Sep 2023</p>
      <p>
        Worked on <strong>Performance Anomaly Detection and Bottleneck Diagnosis in Android Systems</strong>.  
        Proposed a <strong>decision tree–based anomaly detection</strong> framework and bottleneck hyperplane diagnosis to handle memory/CPU/GPU performance issues. The project concluded successfully, and a related <strong>invention patent (202310756598.6)</strong> was filed.
      </p>
    </div>
  </div>

  <div class="cv-item">
  <div class="cv-logo">
    <img src="/images/logos/Huawei_logo.png" alt="Huawei Technologies">
  </div>
  <div class="cv-content">
    <h3>Huawei Technologies Co., Ltd.</h3>
    <p><span class="cv-role">Open-source Contributor (OSPP 2025)</span></p>
    <p class="cv-date">Jul 2025 – Sep 2025</p>
    <p style="text-align: justify;">
      Federated fine-tuning for large language models in Huawei’s distributed synergy AI project <a href="https://github.com/kubeedge" target="_blank">KubeEdge</a> project, 
      focusing on distributed optimization and efficient edge deployment. Providing best practices for developers and end users with presentation tools including leaderboards and test reports.
    </p>
  </div>
</div>

</div>

---

📰 Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
<div style="margin-top:80px;"></div>
---
  
🤝 Service
======
  <ul>{% for post in site.service reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
<div style="margin-top:80px;"></div>
---

🧰 Skills
======
<div class="skill-card">
  <div class="skill-block">
    <div class="skill-name">Programming Languages (Familiar)</div>
    <ul class="skill-list">
      <li>Python</li>
      <li>C / C++ / C#</li>
      <li>Java</li>
      <li>SQL</li>
      <li>HTML</li>
    </ul>
  </div>

  <div class="skill-block">
    <div class="skill-name">Tools (Familiar)</div>
    <ul class="skill-list">
      <li>PyTorch</li>
      <li>TensorFlow</li>
      <li>Git</li>
      <li>Linux Command Line</li>
      <li>ADB Tools</li>
    </ul>
  </div>

  <div class="skill-block">
    <div class="skill-name">Programming  Languages (Used)</div>
    <ul class="skill-list">
      <li>Matlab</li>
      <li>Verilog</li>
      <li>X86 Assembly</li>
      <li>Kotlin</li>
      <li>Docker</li>
    </ul>
  </div>

  <div class="skill-block">
    <div class="skill-name">Tools (Used)</div>
    <ul class="skill-list">
      <li>Kubernetes</li>
      <li>HADOOP</li>
      <li>LLVM</li>
      <li>QT</li>
      <li>SSM</li>
    </ul>
  </div>
</div>
<div style="margin-top:70px;"></div>
---

🌐 Languages
======
<div class="language-card">
  <div class="language-block">
    <div class="language-name">Chinese</div>
    <div class="language-level">Native speaker</div>
  </div>
  <div class="language-block">
    <div class="language-name">English</div>
    <div class="language-level">Professional working proficiency</div>
  </div>
</div>
<div style="margin-top:70px;"></div>
---

🏆 Awards
======
{% include award_list.html %}
---