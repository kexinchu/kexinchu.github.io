---
layout: default
title: "Kexin Chu | Systems Researcher"
---

<style>
  @import url("https://fonts.googleapis.com/css2?family=Manrope:wght@400;500;600;700;800&family=Fraunces:opsz,wght@9..144,600;9..144,700&display=swap");

  :root {
    --paper: #f4efe6;
    --paper-strong: #fbf7f1;
    --ink: #102033;
    --muted: #5b6877;
    --line: rgba(16, 32, 51, 0.12);
    --accent: #c75a38;
    --accent-deep: #8f3b20;
    --teal: #205d61;
    --gold: #d2a64a;
    --shadow: 0 24px 60px rgba(16, 32, 51, 0.14);
    --radius-xl: 28px;
    --radius-lg: 20px;
    --radius-md: 14px;
  }

  .brand-home,
  .brand-home * {
    box-sizing: border-box;
  }

  .brand-home {
    margin: -32px -24px 0;
    padding: 24px 24px 56px;
    color: var(--ink);
    font-family: "Manrope", sans-serif;
    background:
      radial-gradient(circle at top left, rgba(210, 166, 74, 0.18), transparent 30%),
      radial-gradient(circle at top right, rgba(32, 93, 97, 0.12), transparent 26%),
      linear-gradient(180deg, #efe7db 0%, #f8f4ed 22%, #f5f0e8 100%);
  }

  .brand-shell {
    max-width: 1120px;
    margin: 0 auto;
  }

  .topbar {
    position: sticky;
    top: 12px;
    z-index: 20;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 20px;
    padding: 14px 18px;
    margin-bottom: 28px;
    border: 1px solid rgba(255, 255, 255, 0.45);
    border-radius: 999px;
    background: rgba(251, 247, 241, 0.84);
    backdrop-filter: blur(14px);
    box-shadow: 0 12px 30px rgba(16, 32, 51, 0.08);
  }

  .topbar-brand {
    font-size: 13px;
    font-weight: 800;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    color: var(--muted);
  }

  .topbar nav {
    display: flex;
    flex-wrap: wrap;
    gap: 14px;
  }

  .topbar a {
    color: var(--ink);
    text-decoration: none;
    font-size: 14px;
    font-weight: 600;
  }

  .hero {
    display: grid;
    grid-template-columns: minmax(0, 1.45fr) minmax(300px, 0.95fr);
    gap: 28px;
    align-items: stretch;
    margin-bottom: 26px;
  }

  .hero-copy,
  .hero-side,
  .panel,
  .feature-card,
  .publication-card,
  .background-card,
  .cta-card {
    border-radius: var(--radius-xl);
    box-shadow: var(--shadow);
  }

  .hero-copy {
    position: relative;
    overflow: hidden;
    padding: 42px;
    background:
      linear-gradient(140deg, rgba(16, 32, 51, 0.96), rgba(20, 50, 65, 0.92)),
      linear-gradient(160deg, rgba(199, 90, 56, 0.12), transparent 45%);
    color: #f7f3eb;
  }

  .hero-copy::after {
    content: "";
    position: absolute;
    inset: auto -60px -70px auto;
    width: 240px;
    height: 240px;
    border-radius: 50%;
    background: radial-gradient(circle, rgba(210, 166, 74, 0.25), transparent 70%);
  }

  .eyebrow {
    margin: 0 0 18px;
    font-size: 12px;
    font-weight: 800;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    color: rgba(247, 243, 235, 0.74);
  }

  .hero-copy h1 {
    margin: 0;
    font-family: "Fraunces", serif;
    font-size: clamp(2.6rem, 4vw, 4.6rem);
    line-height: 1.02;
    letter-spacing: -0.04em;
    max-width: 10.5ch;
  }

  .hero-copy .lede {
    max-width: 660px;
    margin: 22px 0 0;
    font-size: 18px;
    line-height: 1.8;
    color: rgba(247, 243, 235, 0.86);
  }

  .hero-copy .sublede {
    max-width: 620px;
    margin: 18px 0 0;
    font-size: 15px;
    line-height: 1.8;
    color: rgba(247, 243, 235, 0.7);
  }

  .hero-actions,
  .social-links,
  .badge-row,
  .toolkit,
  .pub-links {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
  }

  .hero-actions {
    margin-top: 28px;
  }

  .hero-actions a,
  .cta-link,
  .pub-links a {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    gap: 8px;
    padding: 12px 18px;
    border-radius: 999px;
    font-size: 14px;
    font-weight: 700;
    text-decoration: none;
    transition: transform 0.2s ease, box-shadow 0.2s ease, background 0.2s ease;
  }

  .hero-actions a:hover,
  .cta-link:hover,
  .pub-links a:hover {
    transform: translateY(-1px);
  }

  .hero-primary {
    background: var(--paper-strong);
    color: var(--ink);
  }

  .hero-secondary {
    border: 1px solid rgba(247, 243, 235, 0.2);
    color: #f7f3eb;
    background: rgba(255, 255, 255, 0.04);
  }

  .signal-strip {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 12px;
    margin-top: 34px;
  }

  .signal {
    padding: 16px;
    border: 1px solid rgba(247, 243, 235, 0.12);
    border-radius: 18px;
    background: rgba(255, 255, 255, 0.04);
  }

  .signal strong {
    display: block;
    font-size: 1.45rem;
    color: #fff7ea;
  }

  .signal span {
    display: block;
    margin-top: 6px;
    font-size: 13px;
    line-height: 1.5;
    color: rgba(247, 243, 235, 0.74);
  }

  .hero-side {
    display: grid;
    gap: 18px;
  }

  .profile-card,
  .focus-card {
    overflow: hidden;
    background: var(--paper-strong);
  }

  .profile-card {
    padding: 22px;
  }

  .profile-photo {
    width: 100%;
    aspect-ratio: 1 / 1.05;
    object-fit: cover;
    border-radius: 22px;
    display: block;
  }

  .profile-card h2 {
    margin: 18px 0 6px;
    font-size: 1.6rem;
    font-family: "Fraunces", serif;
    letter-spacing: -0.03em;
  }

  .profile-card p {
    margin: 0;
    color: var(--muted);
    line-height: 1.7;
  }

  .social-links {
    margin-top: 16px;
  }

  .social-links a {
    color: var(--ink);
    text-decoration: none;
    font-size: 14px;
    font-weight: 700;
  }

  .focus-card {
    padding: 24px;
    background:
      linear-gradient(180deg, rgba(199, 90, 56, 0.08), rgba(255, 255, 255, 0)),
      var(--paper-strong);
  }

  .section-kicker {
    display: inline-block;
    margin-bottom: 12px;
    padding: 6px 10px;
    border-radius: 999px;
    background: rgba(199, 90, 56, 0.1);
    color: var(--accent-deep);
    font-size: 12px;
    font-weight: 800;
    letter-spacing: 0.14em;
    text-transform: uppercase;
  }

  .focus-card h3,
  .panel h2,
  .publication-card h3,
  .background-card h3,
  .cta-card h2 {
    margin: 0;
    letter-spacing: -0.03em;
  }

  .focus-card h3 {
    font-size: 1.3rem;
  }

  .focus-list {
    display: grid;
    gap: 14px;
    margin: 18px 0 0;
  }

  .focus-item {
    padding-top: 14px;
    border-top: 1px solid var(--line);
  }

  .focus-item strong {
    display: block;
    font-size: 15px;
  }

  .focus-item span {
    display: block;
    margin-top: 6px;
    color: var(--muted);
    line-height: 1.65;
    font-size: 14px;
  }

  .panel {
    margin-top: 28px;
    padding: 34px;
    background: rgba(251, 247, 241, 0.82);
    border: 1px solid rgba(255, 255, 255, 0.55);
  }

  .panel h2 {
    font-family: "Fraunces", serif;
    font-size: clamp(1.9rem, 2vw, 2.7rem);
    line-height: 1.08;
  }

  .section-intro {
    max-width: 780px;
    margin-top: 14px;
    color: var(--muted);
    font-size: 16px;
    line-height: 1.8;
  }

  .feature-grid,
  .latest-grid,
  .publication-grid,
  .background-grid {
    display: grid;
    gap: 18px;
    margin-top: 24px;
  }

  .feature-grid {
    grid-template-columns: repeat(3, minmax(0, 1fr));
  }

  .latest-grid {
    grid-template-columns: repeat(3, minmax(0, 1fr));
  }

  .publication-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }

  .background-grid {
    grid-template-columns: 1.1fr 0.9fr;
  }

  .feature-card,
  .publication-card,
  .background-card,
  .cta-card {
    padding: 24px;
    background: var(--paper-strong);
    border: 1px solid rgba(16, 32, 51, 0.06);
  }

  .feature-card h3,
  .publication-card h3,
  .background-card h3 {
    font-size: 1.18rem;
  }

  .feature-card p,
  .publication-card p,
  .background-card p,
  .background-card li,
  .cta-card p {
    margin: 12px 0 0;
    color: var(--muted);
    line-height: 1.8;
    font-size: 15px;
  }

  .feature-card strong,
  .publication-card strong,
  .background-card strong {
    color: var(--ink);
  }

  .feature-number {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 36px;
    height: 36px;
    margin-bottom: 14px;
    border-radius: 50%;
    background: rgba(32, 93, 97, 0.1);
    color: var(--teal);
    font-size: 14px;
    font-weight: 800;
  }

  .badge-row {
    margin-top: 14px;
  }

  .badge {
    display: inline-flex;
    align-items: center;
    padding: 6px 10px;
    border-radius: 999px;
    background: rgba(16, 32, 51, 0.06);
    color: var(--ink);
    font-size: 12px;
    font-weight: 700;
    letter-spacing: 0.02em;
  }

  .publication-card .badge {
    background: rgba(199, 90, 56, 0.1);
    color: var(--accent-deep);
  }

  .pub-links {
    margin-top: 18px;
  }

  .pub-links a {
    background: rgba(16, 32, 51, 0.05);
    color: var(--ink);
  }

  .background-card ul {
    margin: 16px 0 0;
    padding-left: 18px;
  }

  .toolkit {
    margin-top: 18px;
  }

  .toolkit span {
    display: inline-flex;
    align-items: center;
    padding: 8px 12px;
    border-radius: 999px;
    background: rgba(16, 32, 51, 0.06);
    color: var(--ink);
    font-size: 13px;
    font-weight: 700;
  }

  .cta-card {
    margin-top: 28px;
    padding: 32px;
    background:
      linear-gradient(135deg, rgba(199, 90, 56, 0.95), rgba(143, 59, 32, 0.95)),
      linear-gradient(135deg, rgba(255, 255, 255, 0.08), transparent);
    color: #fffaf2;
  }

  .cta-card h2 {
    font-family: "Fraunces", serif;
    font-size: clamp(1.8rem, 2vw, 2.6rem);
  }

  .cta-card p {
    max-width: 720px;
    color: rgba(255, 250, 242, 0.84);
  }

  .cta-link {
    margin-top: 18px;
    background: #fffaf2;
    color: var(--accent-deep);
  }

  @media (max-width: 980px) {
    .hero,
    .feature-grid,
    .latest-grid,
    .publication-grid,
    .background-grid,
    .signal-strip {
      grid-template-columns: 1fr;
    }

    .topbar {
      border-radius: 26px;
      align-items: flex-start;
      flex-direction: column;
    }

    .hero-copy,
    .panel,
    .cta-card {
      padding: 28px;
    }
  }

  @media (max-width: 640px) {
    .brand-home {
      margin: -24px -16px 0;
      padding: 16px 16px 48px;
    }

    .hero-copy h1 {
      max-width: none;
    }

    .hero-actions a,
    .cta-link,
    .pub-links a {
      width: 100%;
    }
  }
</style>

<div class="brand-home">
  <div class="brand-shell">
    <div class="topbar">
      <div class="topbar-brand">Kexin Chu</div>
      <nav>
        <a href="#focus">Focus</a>
        <a href="#latest">Latest</a>
        <a href="#publications">Publications</a>
        <a href="#background">Background</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>

    <section class="hero" id="top">
      <div class="hero-copy">
        <p class="eyebrow">Ph.D. student, University of Connecticut</p>
        <h1>Building systems that make AI workloads faster, fairer, and more dependable.</h1>
        <p class="lede">
          I work on ML systems with a systems-builder mindset: long-context LLM serving, hybrid retrieval, secure inference, and memory-centric infrastructure for modern AI.
        </p>
        <p class="sublede">
          My perspective is shaped by both research and production. Before starting my Ph.D., I spent four years at Baidu designing large-scale backend and AI service infrastructure, which still influences how I frame problems, evaluate tradeoffs, and build systems that survive real workloads.
        </p>
        <div class="hero-actions">
          <a class="hero-primary" href="mailto:kexin.chu@uconn.edu">Email me</a>
          <a class="hero-secondary" href="CV_Kexin_Chu_Academic_RA.pdf" target="_blank">View CV</a>
          <a class="hero-secondary" href="https://scholar.google.com/citations?user=ZIdS3d0AAAAJ&hl=en" target="_blank">Google Scholar</a>
        </div>
        <div class="signal-strip">
          <div class="signal">
            <strong>8+</strong>
            <span>publications across ML systems, security, and AI infrastructure</span>
          </div>
          <div class="signal">
            <strong>4 years</strong>
            <span>building production-scale backend and AI platform systems at Baidu</span>
          </div>
          <div class="signal">
            <strong>Now</strong>
            <span>pushing on dLLM serving, hybrid retrieval, and reliable stateful agents</span>
          </div>
        </div>
      </div>

      <div class="hero-side">
        <div class="profile-card">
          <img src="pictures/2-inch_ID_photo-min.jpg" alt="Kexin Chu" class="profile-photo">
          <h2>Kexin Chu</h2>
          <p>
            Systems researcher focused on efficient and reliable AI infrastructure, with interests spanning LLM serving, memory systems, retrieval systems, and security.
          </p>
          <div class="social-links">
            <a href="https://github.com/kexinchu" target="_blank">GitHub</a>
            <a href="https://scholar.google.com/citations?user=ZIdS3d0AAAAJ&hl=en" target="_blank">Scholar</a>
            <a href="mailto:kexin.chu@uconn.edu">Email</a>
          </div>
        </div>

        <div class="focus-card">
          <span class="section-kicker">Working style</span>
          <h3>How I approach systems research</h3>
          <div class="focus-list">
            <div class="focus-item">
              <strong>Mechanism first</strong>
              <span>I like problems where the system behavior can be explained, measured, and improved through concrete mechanisms.</span>
            </div>
            <div class="focus-item">
              <strong>Real workloads over toy wins</strong>
              <span>I care about whether an idea still holds under heterogeneous traffic, long tails, and realistic deployment constraints.</span>
            </div>
            <div class="focus-item">
              <strong>Research with builder instincts</strong>
              <span>I bring a production systems perspective to research questions, which helps me focus on bottlenecks that matter in practice.</span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="panel" id="focus">
      <span class="section-kicker">Research identity</span>
      <h2>I care about the systems layer that decides whether ambitious AI ideas actually work in practice.</h2>
      <p class="section-intro">
        The common thread across my work is coordination under real constraints: coordinating memory across tiers, coordinating heterogeneous retrieval pipelines, coordinating latency and fairness in serving, and increasingly coordinating recoverability when agents interact with stateful tools.
      </p>

      <div class="feature-grid">
        <div class="feature-card">
          <div class="feature-number">01</div>
          <h3>Efficient AI infrastructure</h3>
          <p>
            I design systems that improve <strong>throughput, latency, fairness, and memory efficiency</strong> for large-model inference, especially when naive batching or caching choices break under heterogeneous workloads.
          </p>
        </div>
        <div class="feature-card">
          <div class="feature-number">02</div>
          <h3>Workload-aware data systems</h3>
          <p>
            My retrieval work studies how <strong>SQL, vector search, filtering, and execution policy</strong> interact, with an emphasis on bottlenecks, crossover regimes, and practical hybrid-query coordination.
          </p>
        </div>
        <div class="feature-card">
          <div class="feature-number">03</div>
          <h3>Reliable stateful agents</h3>
          <p>
            I am exploring how agent systems can become more dependable by making <strong>recoverability, repair cost, and tool-side effects</strong> first-class concerns in planning, not afterthoughts.
          </p>
        </div>
      </div>
    </section>

    <section class="panel" id="latest">
      <span class="section-kicker">Latest work</span>
      <h2>What I am actively pushing right now</h2>
      <p class="section-intro">
        These are the workstreams I would want a collaborator, recruiter, or faculty reviewer to notice first because they show where my thinking is heading today.
      </p>

      <div class="latest-grid">
        <div class="feature-card">
          <div class="badge-row">
            <span class="badge">Serving systems</span>
            <span class="badge">Current</span>
          </div>
          <h3>Shape-aware serving for long-context diffusion LLMs</h3>
          <p>
            I am refining a systems story around shape-aware continuous batching, fairness controls, and same-model online baselines for long-context dLLM serving. The emphasis is not only speed, but also honest evaluation under realistic workload mixes and boundary cases.
          </p>
        </div>

        <div class="feature-card">
          <div class="badge-row">
            <span class="badge">Hybrid retrieval</span>
            <span class="badge">Current</span>
          </div>
          <h3>Workload-aware coordination for SQL plus vector search</h3>
          <p>
            My recent retrieval work frames hybrid search as a coordinator problem: when should a system lean SQL-first, vector-first, cooperative execution, or exact fallback, and how do selectivity, filter cost, and interference change the answer?
          </p>
        </div>

        <div class="feature-card">
          <div class="badge-row">
            <span class="badge">Agent systems</span>
            <span class="badge">Emerging</span>
          </div>
          <h3>Recoverability-aware planning for stateful tool agents</h3>
          <p>
            I am also shaping an agent-systems direction around Recoverability-Aware Planner (RAP), where tool contracts, reversible actions, checkpoint value, and repair policies guide planning before failures happen.
          </p>
        </div>
      </div>
    </section>

    <section class="panel" id="publications">
      <span class="section-kicker">Selected publications</span>
      <h2>Research themes with tangible outputs</h2>
      <p class="section-intro">
        My papers sit at the intersection of systems, performance, and reliability. I care about papers that lead to stronger mechanisms, clearer measurements, and more actionable systems insight.
      </p>

      <div class="publication-grid">
        <div class="publication-card">
          <div class="badge-row">
            <span class="badge">ICDCS 2025</span>
            <span class="badge">LLM systems</span>
          </div>
          <h3>MCaM: Efficient LLM Inference with Multi-tier KV Cache Management</h3>
          <p>
            A multi-tier KV-cache management system for improving inference efficiency under memory pressure, grounded in the practical realities of serving large models.
          </p>
          <div class="pub-links">
            <a href="https://ieeexplore.ieee.org/abstract/document/11183741" target="_blank">Read paper</a>
          </div>
        </div>

        <div class="publication-card">
          <div class="badge-row">
            <span class="badge">arXiv</span>
            <span class="badge">MoE systems</span>
          </div>
          <h3>ExpertFlow: Adaptive Expert Scheduling and Memory Coordination for Efficient MoE Inference</h3>
          <p>
            A runtime system for MoE inference that couples expert scheduling with memory coordination instead of optimizing one in isolation.
          </p>
          <div class="pub-links">
            <a href="https://arxiv.org/abs/2510.26730" target="_blank">Read paper</a>
          </div>
        </div>

        <div class="publication-card">
          <div class="badge-row">
            <span class="badge">arXiv</span>
            <span class="badge">Security</span>
          </div>
          <h3>Selective KV-Cache Sharing to Mitigate Timing Side-Channels in LLM Inference</h3>
          <p>
            A security-focused line of work that studies how inference performance techniques can leak information and how systems design can reduce that risk.
          </p>
          <div class="pub-links">
            <a href="https://arxiv.org/abs/2508.08438" target="_blank">Read paper</a>
          </div>
        </div>

        <div class="publication-card">
          <div class="badge-row">
            <span class="badge">eBPF 2025</span>
            <span class="badge">Observability</span>
          </div>
          <h3>eInfer: Unlocking Fine-Grained Tracing for Distributed LLM Inference with eBPF</h3>
          <p>
            A tracing framework that improves visibility into distributed LLM inference stacks, making performance debugging and systems analysis more practical.
          </p>
          <div class="pub-links">
            <a href="https://dl.acm.org/doi/abs/10.1145/3748355.3748372" target="_blank">Read paper</a>
          </div>
        </div>

        <div class="publication-card">
          <div class="badge-row">
            <span class="badge">MLArchSys 2025</span>
            <span class="badge">ISCA 2025</span>
            <span class="badge">Security</span>
          </div>
          <h3>SafeKV: Safe KV-Cache Sharing in LLM Serving</h3>
          <p>
            Privacy-preserving KV-cache sharing for multi-tenant LLM serving, connecting systems optimization with concrete safety concerns.
          </p>
          <div class="pub-links">
            <a href="https://openreview.net/pdf?id=jhDsbd5eXL" target="_blank">Paper</a>
            <a href="https://www.youtube.com/watch?v=SJqN4HY1HKQ" target="_blank">Talk</a>
          </div>
        </div>
      </div>
    </section>

    <section class="panel" id="background">
      <span class="section-kicker">Background</span>
      <h2>Research depth, backed by production instincts</h2>
      <div class="background-grid">
        <div class="background-card">
          <h3>Baidu, 2020 to 2024</h3>
          <p>
            Before my Ph.D., I worked as a software architect and backend engineer at Baidu, where I helped build large-scale backend and AI service infrastructure. That experience taught me to care about throughput, tail behavior, observability, failure modes, and how design choices age under real traffic.
          </p>
          <ul>
            <li>Built large-scale web services and backend systems for search infrastructure.</li>
            <li>Designed access control and monitoring systems for production LLM services.</li>
            <li>Worked on streaming pipelines, distributed services, and performance-sensitive architecture.</li>
            <li>Progressed from T3 to T5, with a strong bias toward end-to-end ownership.</li>
          </ul>
          <div class="toolkit">
            <span>C++</span>
            <span>Python</span>
            <span>Golang</span>
            <span>Kafka</span>
            <span>Redis</span>
            <span>MySQL</span>
            <span>Distributed systems</span>
          </div>
        </div>

        <div class="background-card">
          <h3>Education and recognition</h3>
          <p>
            I am currently a Ph.D. student in Computer Science at the University of Connecticut. My academic path started in integrated circuit design and computer architecture, which still shapes how I think about memory, scheduling, hardware-software boundaries, and performance.
          </p>
          <ul>
            <li>Ph.D. in Computer Science, University of Connecticut, 2024 to present.</li>
            <li>M.S. in Integrated Circuit Engineering, Hefei University of Technology.</li>
            <li>B.S. in Integrated Circuit Design and Integrated System, Hefei University of Technology.</li>
            <li>Predoctoral Fellowship recipient, University of Connecticut.</li>
            <li>Baidu Pride Special Award and National Scholarship recipient.</li>
          </ul>
          <div class="toolkit">
            <span>LLM serving</span>
            <span>KV cache</span>
            <span>eBPF</span>
            <span>RDMA</span>
            <span>CXL</span>
            <span>System security</span>
          </div>
        </div>
      </div>
    </section>

    <section class="cta-card" id="contact">
      <span class="section-kicker" style="background: rgba(255, 250, 242, 0.14); color: #fffaf2;">Let's connect</span>
      <h2>I am always interested in thoughtful collaborations on systems for real AI workloads.</h2>
      <p>
        If you are working on ML systems, retrieval infrastructure, serving efficiency, memory-centric design, or dependable agent systems, I would be happy to talk. The best collaborations usually start with a concrete bottleneck, an honest question, or an interesting workload.
      </p>
      <a class="cta-link" href="mailto:kexin.chu@uconn.edu">Start a conversation</a>
    </section>
  </div>
</div>
