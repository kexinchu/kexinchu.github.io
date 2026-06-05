---
layout: default
title: "Publications | Kexin Chu"
nav: publications
permalink: /publications/
---

<section class="page-card">
  <span class="section-heading">Publications</span>
  <h1 class="page-title">Selected papers</h1>
  <p class="page-intro">
    This page highlights representative papers across LLM systems, hybrid infrastructure, security, and trustworthy AI systems. For the most complete and up-to-date list, please use my <a href="https://scholar.google.com/citations?user=ZIdS3d0AAAAJ&hl=en" target="_blank" rel="noreferrer">Google Scholar profile</a>.
  </p>
</section>

<section class="publication-grid">
  <article class="publication-card">
    <div class="tag-row">
      <span class="tag">EuroSys 2026</span>
      <span class="tag">Trustworthy LLM systems</span>
    </div>
    <h2 class="card-title">TrustWeave: Integrity Measurement and Attestation For Multi-Cloud LLMs</h2>
    <p class="publication-copy">
      A system for integrity measurement and attestation in multi-cloud LLM deployments, aimed at making model execution more trustworthy across heterogeneous cloud environments.
    </p>
    <div class="pub-links">
      <a href="https://doi.org/10.1145/3767295.3803586" target="_blank" rel="noreferrer">DOI</a>
    </div>
  </article>

  <article class="publication-card">
    <div class="tag-row">
      <span class="tag">arXiv 2026</span>
      <span class="tag">Deterministic inference</span>
    </div>
    <h2 class="card-title">MarginGate: Sparse Margin-Triggered Verification for Batch-Invariant LLM Inference</h2>
    <p class="publication-copy">
      A verification policy that targets only low-margin decode steps, aiming to restore deterministic decoding while keeping verification overhead significantly lower than always-on checking.
    </p>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2605.30218" target="_blank" rel="noreferrer">arXiv</a>
    </div>
  </article>

  <article class="publication-card">
    <div class="tag-row">
      <span class="tag">arXiv 2026</span>
      <span class="tag">Agent systems</span>
    </div>
    <h2 class="card-title">Latency-Quality Routing for Functionally Equivalent Tools in LLM Agents</h2>
    <p class="publication-copy">
      A routing system for same-function tool providers that treats latency as service capacity and answer quality as the main target under changing load and provider heterogeneity.
    </p>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2605.14241" target="_blank" rel="noreferrer">arXiv</a>
    </div>
  </article>

  <article class="publication-card">
    <div class="tag-row">
      <span class="tag">ICDCS 2025</span>
      <span class="tag">LLM serving</span>
    </div>
    <h2 class="card-title">MCaM: Efficient LLM Inference with Multi-tier KV Cache Management</h2>
    <p class="publication-copy">
      A multi-tier KV-cache management system for improving large-model inference efficiency under memory pressure.
    </p>
    <div class="pub-links">
      <a href="https://ieeexplore.ieee.org/abstract/document/11183741" target="_blank" rel="noreferrer">IEEE</a>
    </div>
  </article>

  <article class="publication-card">
    <div class="tag-row">
      <span class="tag">arXiv 2025</span>
      <span class="tag">MoE systems</span>
    </div>
    <h2 class="card-title">ExpertFlow: Adaptive Expert Scheduling and Memory Coordination for Efficient MoE Inference</h2>
    <p class="publication-copy">
      A runtime system for MoE inference that jointly optimizes expert scheduling and memory coordination instead of treating them as separate problems.
    </p>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2510.26730" target="_blank" rel="noreferrer">arXiv</a>
    </div>
  </article>

  <article class="publication-card">
    <div class="tag-row">
      <span class="tag">arXiv 2025</span>
      <span class="tag">MoE memory efficiency</span>
    </div>
    <h2 class="card-title">Dynamic Expert Quantization for Scalable Mixture-of-Experts Inference</h2>
    <p class="publication-copy">
      A runtime-aware approach to dynamic expert precision control for MoE serving, designed to adapt expert bit-widths under strict GPU memory budgets.
    </p>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2511.15015" target="_blank" rel="noreferrer">arXiv</a>
    </div>
  </article>

  <article class="publication-card">
    <div class="tag-row">
      <span class="tag">arXiv 2025</span>
      <span class="tag">LLM security</span>
    </div>
    <h2 class="card-title">Selective KV-Cache Sharing to Mitigate Timing Side-Channels in LLM Inference</h2>
    <p class="publication-copy">
      A security-focused line of work on reducing timing side-channel leakage in multi-tenant LLM serving without giving up the performance benefits of shared caching.
    </p>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2508.08438" target="_blank" rel="noreferrer">arXiv</a>
    </div>
  </article>
</section>
