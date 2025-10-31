---
layout: default
title: "Kexin Chu | Academic Homepage"
---

<style>
  .nav-menu {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    padding: 15px 0;
    margin: -20px -20px 30px -20px;
    text-align: center;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  }
  .nav-menu a {
    color: white;
    text-decoration: none;
    margin: 0 20px;
    font-weight: 600;
    font-size: 16px;
    transition: all 0.3s ease;
    padding: 8px 15px;
    border-radius: 5px;
  }
  .nav-menu a:hover {
    background: rgba(255,255,255,0.2);
    transform: translateY(-2px);
  }
  .profile-header {
    display: flex;
    align-items: center;
    gap: 30px;
    margin-bottom: 30px;
    padding: 30px;
    background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
    border-radius: 15px;
    box-shadow: 0 8px 16px rgba(0,0,0,0.1);
  }
  .profile-photo {
    width: 180px;
    height: 180px;
    border-radius: 50%;
    object-fit: cover;
    border: 5px solid white;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
  }
  .profile-info {
    flex: 1;
  }
  .section-title {
    color: #2c3e50;
    border-left: 5px solid #667eea;
    padding-left: 15px;
    margin-top: 40px;
    margin-bottom: 20px;
    font-size: 28px;
  }
  .pub-item {
    background: #f8f9fa;
    padding: 20px;
    margin-bottom: 15px;
    border-radius: 10px;
    border-left: 4px solid #667eea;
    transition: all 0.3s ease;
  }
  .pub-item:hover {
    transform: translateX(5px);
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  }
  .badge {
    display: inline-block;
    padding: 4px 12px;
    background: #667eea;
    color: white;
    border-radius: 20px;
    font-size: 13px;
    margin-right: 8px;
    margin-top: 5px;
  }
  .contact-links {
    margin-top: 15px;
  }
  .contact-links a {
    display: inline-block;
    margin-right: 15px;
    padding: 8px 16px;
    background: #667eea;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    transition: all 0.3s ease;
    font-size: 14px;
  }
  .contact-links a:hover {
    background: #764ba2;
    transform: translateY(-2px);
  }
  .stats-container {
    display: flex;
    gap: 20px;
    margin: 30px 0;
    flex-wrap: wrap;
  }
  .stat-box {
    flex: 1;
    min-width: 200px;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 25px;
    border-radius: 10px;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  }
  .stat-number {
    font-size: 36px;
    font-weight: bold;
    margin-bottom: 5px;
  }
  .stat-label {
    font-size: 14px;
    opacity: 0.9;
  }
  .skill-tag {
    display: inline-block;
    background: #e8eaf6;
    color: #5e35b1;
    padding: 8px 16px;
    margin: 5px;
    border-radius: 20px;
    font-size: 14px;
    font-weight: 500;
  }
  .timeline-item {
    position: relative;
    padding-left: 40px;
    margin-bottom: 30px;
    border-left: 2px solid #667eea;
  }
  .timeline-item::before {
    content: '';
    position: absolute;
    left: -8px;
    top: 0;
    width: 16px;
    height: 16px;
    border-radius: 50%;
    background: #667eea;
    border: 3px solid white;
    box-shadow: 0 0 0 3px #667eea;
  }
</style>

<div class="nav-menu">
  <a href="#about">About</a>
  <a href="#research">Research</a>
  <a href="#publications">Publications</a>
  <a href="#experience">Experience</a>
  <a href="#education">Education</a>
  <a href="#awards">Awards</a>
  <a href="#skills">Skills</a>
</div>

<div class="profile-header" id="about">
  <img src="pictures/2-inch_ID_photo-min.jpg" alt="Kexin Chu" class="profile-photo">
  <div class="profile-info">
    <h1 style="margin-top:0; color:#2c3e50;">👋 <span style="color:#c0392b"><b>Kexin Chu</b></span></h1>
    <h3 style="color:#555; margin: 10px 0;">Ph.D. Student in Computer Science</h3>
    <p style="font-size: 16px; line-height: 1.6; color:#555;">
      University of Connecticut | Focusing on <span style="color:#667eea"><b>Machine Learning Systems</b></span>, <span style="color:#667eea"><b>LLM Infrastructure</b></span>, <span style="color:#667eea"><b>System Security</b></span>, and <span style="color:#667eea"><b>Disaggregated Memory</b></span>
    </p>
    <p style="color:#555;">📍 Connecticut, USA</p>
    <div class="contact-links">
      <a href="https://scholar.google.com/citations?user=ZIdS3d0AAAAJ&hl=en" target="_blank">📚 Google Scholar</a>
      <a href="https://github.com/kexinchu" target="_blank">💻 GitHub</a>
      <a href="mailto:kexin.chu@uconn.edu">📧 Email</a>
    </div>
  </div>
</div>

<div style="background: #fff3cd; padding: 20px; border-radius: 10px; border-left: 5px solid #ffc107; margin-bottom: 30px;">
  <p style="color:#856404; font-size: 16px; margin: 0;">
    <b>💡 Open to Collaboration!</b> If you're interested in MLSys, Multi-Agent Systems, Disaggregated Memory, or Security, feel free to reach out — let's build something exciting together!
  </p>
</div>

<div class="stats-container">
  <div class="stat-box">
    <div class="stat-number">8+</div>
    <div class="stat-label">Publications</div>
  </div>
  <div class="stat-box">
    <div class="stat-number">4+</div>
    <div class="stat-label">Years Industry Experience</div>
  </div>
  <div class="stat-box">
    <div class="stat-number">3</div>
    <div class="stat-label">Top Conferences</div>
  </div>
</div>

---

<h2 class="section-title" id="research">🧪 Research Interests</h2>

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin-bottom: 30px;">
  <div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; padding: 25px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <h3 style="margin-top: 0; color: white;">🤖 LLM Systems</h3>
    <p style="font-size: 14px; line-height: 1.6;">Efficient inference, KV-cache optimization, and serving systems for large language models</p>
  </div>
  <div style="background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); color: white; padding: 25px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <h3 style="margin-top: 0; color: white;">🔒 System Security</h3>
    <p style="font-size: 14px; line-height: 1.6;">Security and privacy in ML systems, timing side-channel mitigation</p>
  </div>
  <div style="background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%); color: white; padding: 25px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <h3 style="margin-top: 0; color: white;">💾 Memory Systems</h3>
    <p style="font-size: 14px; line-height: 1.6;">RDMA, disaggregated memory, CXL, and memory-tiered architectures</p>
  </div>
</div>

---

<h2 class="section-title" id="publications">📄 Selected Publications</h2>

<div class="pub-item">
  <h3 style="color: #2c3e50; margin-top: 0;">MCaM: Efficient LLM Inference with Multi-tier KV Cache Management</h3>
  <span class="badge">ICDCS 2025</span>
  <span class="badge" style="background: #27ae60;">Conference Paper</span>
  <p style="margin: 10px 0; color: #555;">Multi-tier KV cache management system for efficient large language model inference.</p>
  <a href="https://ieeexplore.ieee.org/abstract/document/11183741" style="color: #667eea; text-decoration: none;">📄 Read Paper →</a>
</div>

<div class="pub-item">
  <h3 style="color: #2c3e50; margin-top: 0;">DynaMoE: An Algorithm-System Co-Design for Fast MoE Serving</h3>
  <span class="badge" style="background: #f39c12;">Under Review</span>
  <span class="badge">IPDPS 2026</span>
  <p style="margin: 10px 0; color: #555;">Novel co-design approach for efficient Mixture-of-Experts model serving.</p>
</div>

<div class="pub-item">
  <h3 style="color: #2c3e50; margin-top: 0;">Selective KV-Cache Sharing to Mitigate Timing Side-Channels in LLM Inference</h3>
  <span class="badge" style="background: #e74c3c;">Security</span>
  <span class="badge">arXiv</span>
  <p style="margin: 10px 0; color: #555;">Security-focused approach to prevent timing attacks in LLM serving systems.</p>
  <a href="https://arxiv.org/abs/2508.08438" style="color: #667eea; text-decoration: none;">📄 Read Paper →</a>
</div>

<div class="pub-item">
  <h3 style="color: #2c3e50; margin-top: 0;">eInfer: Unlocking Fine-Grained Tracing for Distributed LLM Inference with eBPF</h3>
  <span class="badge">eBPF 2025</span>
  <span class="badge" style="background: #16a085;">Workshop</span>
  <p style="margin: 10px 0; color: #555;">eBPF-based tracing framework for distributed LLM inference systems.</p>
  <a href="https://dl.acm.org/doi/abs/10.1145/3748355.3748372" style="color: #667eea; text-decoration: none;">📄 Read Paper →</a>
</div>

<div class="pub-item">
  <h3 style="color: #2c3e50; margin-top: 0;">SafeKV: Safe KV-Cache Sharing in LLM Serving</h3>
  <span class="badge">MLArchSys 2025</span>
  <span class="badge">ISCA 2025</span>
  <span class="badge" style="background: #e74c3c;">Security</span>
  <p style="margin: 10px 0; color: #555;">Privacy-preserving KV-cache sharing mechanism for multi-tenant LLM serving.</p>
  <a href="https://openreview.net/pdf?id=jhDsbd5eXL" style="color: #667eea; text-decoration: none; margin-right: 15px;">📄 Paper</a>
  <a href="https://www.youtube.com/watch?v=SJqN4HY1HKQ" style="color: #e74c3c; text-decoration: none;">🎥 Presentation</a>
</div>

---

<h2 class="section-title" id="education">🎓 Education</h2>

<div class="timeline-item">
  <h3 style="color: #2c3e50; margin-top: 0;">Ph.D. in Computer Science</h3>
  <p style="color: #667eea; font-weight: 600; margin: 5px 0;">University of Connecticut, USA | 2024 - Present</p>
  <p style="color: #555; line-height: 1.6;">
    Research Focus: ML Systems, KV-cache optimization, RDMA-backed storage, and disaggregated memory architectures.<br>
    <span style="color: #27ae60;">💰 Predoctoral Fellowship Recipient</span>
  </p>
</div>

<div class="timeline-item">
  <h3 style="color: #2c3e50; margin-top: 0;">M.S. in Integrated Circuit Engineering</h3>
  <p style="color: #667eea; font-weight: 600; margin: 5px 0;">Hefei University of Technology, China</p>
  <p style="color: #555; line-height: 1.6;">
    Co-supervised by A.P. Ying Wang and A.P. Cheng Liu<br>
    Specialized in computer architecture and AI acceleration
  </p>
</div>

<div class="timeline-item">
  <h3 style="color: #2c3e50; margin-top: 0;">B.S. in Integrated Circuit Design & Integrated System</h3>
  <p style="color: #667eea; font-weight: 600; margin: 5px 0;">Hefei University of Technology, China</p>
  <p style="color: #555; line-height: 1.6;">
    Foundation in digital circuit design, computer organization, and system integration<br>
    <span style="color: #27ae60;">🏆 National Scholarship Recipient (2018, 2019)</span>
  </p>
</div>

---

<h2 class="section-title" id="experience">💼 Industry Experience</h2>

<div style="background: #f8f9fa; padding: 25px; border-radius: 10px; border-left: 5px solid #667eea; margin-bottom: 20px;">
  <div style="display: flex; justify-content: space-between; align-items: start; flex-wrap: wrap;">
    <div>
      <h3 style="color: #2c3e50; margin: 0 0 5px 0;">Software Architect & Backend Engineer</h3>
      <p style="color: #667eea; font-weight: 600; margin: 5px 0; font-size: 18px;">Baidu Inc., Beijing, China</p>
    </div>
    <div>
      <span style="background: #667eea; color: white; padding: 6px 15px; border-radius: 20px; font-size: 14px;">2020 - 2024</span>
    </div>
  </div>
  
  <p style="color: #555; margin: 15px 0; line-height: 1.6;">
    <b>Department:</b> Search R&D Platform - Focus on large-scale backend systems
  </p>
  
  <div style="background: #e8f5e9; padding: 12px; border-radius: 5px; margin: 15px 0;">
    <p style="color: #2e7d32; margin: 0; font-weight: 600;">
      🚀 Career Progression: T3 → T4 (2021) → T5 (2023)
    </p>
  </div>
  
  <p style="color: #2c3e50; font-weight: 600; margin: 15px 0 10px 0;">Key Contributions:</p>
  <ul style="color: #555; line-height: 1.8;">
    <li><b>DeepQA Web Services:</b> Developed high-performance web services using C++/brpc for large-scale search infrastructure, handling millions of queries daily</li>
    <li><b>LLM Access Control Systems:</b> Built comprehensive access control and monitoring systems for Ernie Bot/WenXinYiYan (文心一言) using Golang, Redis, and MySQL. Ensured security and reliability for production LLM services</li>
    <li><b>Real-Time Streaming Systems:</b> Designed and implemented Kafka-based streaming pipelines for large-scale data indexing and ingestion, enabling real-time data processing</li>
    <li><b>System Architecture:</b> Led architectural design decisions for high-throughput, low-latency distributed systems serving billions of requests</li>
  </ul>
  
  <div style="margin-top: 15px;">
    <span class="skill-tag">C++</span>
    <span class="skill-tag">Golang</span>
    <span class="skill-tag">brpc</span>
    <span class="skill-tag">Kafka</span>
    <span class="skill-tag">Redis</span>
    <span class="skill-tag">MySQL</span>
    <span class="skill-tag">Distributed Systems</span>
  </div>
</div>

---

<h2 class="section-title" id="awards">🏆 Honors & Awards</h2>

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; margin-bottom: 30px;">
  <div style="background: linear-gradient(135deg, #ffd89b 0%, #19547b 100%); color: white; padding: 25px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <h3 style="margin: 0 0 10px 0; color: white;">🏅 Predoctoral Fellowship</h3>
    <p style="font-size: 16px; margin: 5px 0; opacity: 0.95;">University of Connecticut</p>
    <p style="font-size: 14px; margin: 0; opacity: 0.9;">2025</p>
  </div>
  
  <div style="background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); color: white; padding: 25px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <h3 style="margin: 0 0 10px 0; color: white;">🏅 Baidu Pride Special Award</h3>
    <p style="font-size: 16px; margin: 5px 0; opacity: 0.95;">Baidu Inc.</p>
    <p style="font-size: 14px; margin: 0; opacity: 0.9;">2022</p>
  </div>
  
  <div style="background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%); color: white; padding: 25px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <h3 style="margin: 0 0 10px 0; color: white;">🎓 National Scholarship</h3>
    <p style="font-size: 16px; margin: 5px 0; opacity: 0.95;">China Ministry of Education</p>
    <p style="font-size: 14px; margin: 0; opacity: 0.9;">2018, 2019</p>
  </div>
</div>

---

<h2 class="section-title" id="skills">🛠️ Technical Skills</h2>

<div style="margin-bottom: 30px;">
  <h3 style="color: #2c3e50; margin-bottom: 15px;">Programming Languages</h3>
  <div>
    <span class="skill-tag" style="background: #667eea; color: white;">C++</span>
    <span class="skill-tag" style="background: #667eea; color: white;">Python</span>
    <span class="skill-tag" style="background: #667eea; color: white;">Golang</span>
    <span class="skill-tag" style="background: #667eea; color: white;">C</span>
    <span class="skill-tag">Rust</span>
    <span class="skill-tag">CUDA</span>
  </div>
</div>

<div style="margin-bottom: 30px;">
  <h3 style="color: #2c3e50; margin-bottom: 15px;">ML/AI Frameworks & Tools</h3>
  <div>
    <span class="skill-tag" style="background: #667eea; color: white;">PyTorch</span>
    <span class="skill-tag" style="background: #667eea; color: white;">vLLM</span>
    <span class="skill-tag">TensorFlow</span>
    <span class="skill-tag">Triton</span>
    <span class="skill-tag">DeepSpeed</span>
    <span class="skill-tag">Ray</span>
    <span class="skill-tag">LangChain</span>
  </div>
</div>

<div style="margin-bottom: 30px;">
  <h3 style="color: #2c3e50; margin-bottom: 15px;">Systems & Infrastructure</h3>
  <div>
    <span class="skill-tag" style="background: #667eea; color: white;">RDMA</span>
    <span class="skill-tag" style="background: #667eea; color: white;">Linux Kernel</span>
    <span class="skill-tag" style="background: #667eea; color: white;">eBPF</span>
    <span class="skill-tag">Distributed Systems</span>
    <span class="skill-tag">Kubernetes</span>
    <span class="skill-tag">Docker</span>
    <span class="skill-tag">CXL</span>
  </div>
</div>

<div style="margin-bottom: 30px;">
  <h3 style="color: #2c3e50; margin-bottom: 15px;">Databases & Message Queues</h3>
  <div>
    <span class="skill-tag" style="background: #667eea; color: white;">Redis</span>
    <span class="skill-tag" style="background: #667eea; color: white;">MySQL</span>
    <span class="skill-tag" style="background: #667eea; color: white;">Kafka</span>
    <span class="skill-tag">PostgreSQL</span>
    <span class="skill-tag">MongoDB</span>
  </div>
</div>

<div style="margin-bottom: 30px;">
  <h3 style="color: #2c3e50; margin-bottom: 15px;">Research Areas</h3>
  <div>
    <span class="skill-tag" style="background: #27ae60; color: white;">LLM Serving</span>
    <span class="skill-tag" style="background: #27ae60; color: white;">KV-Cache Optimization</span>
    <span class="skill-tag" style="background: #e74c3c; color: white;">System Security</span>
    <span class="skill-tag" style="background: #3498db; color: white;">Memory Systems</span>
    <span class="skill-tag">Computer Architecture</span>
    <span class="skill-tag">Performance Optimization</span>
  </div>
</div>

---

<div style="text-align: center; padding: 30px; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); border-radius: 10px; color: white; margin-top: 40px;">
  <h3 style="margin-top: 0; color: white;">📬 Get In Touch</h3>
  <p style="font-size: 16px; margin: 15px 0;">Interested in collaboration or have questions about my research?</p>
  <a href="mailto:kexin.chu@uconn.edu" style="display: inline-block; margin-top: 15px; padding: 12px 30px; background: white; color: #667eea; text-decoration: none; border-radius: 25px; font-weight: 600; transition: all 0.3s ease;">Send me an email →</a>
</div>
