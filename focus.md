---
layout: default
title: "Focus | Kexin Chu"
nav: focus
permalink: /focus/
---

<section class="page-card">
  <span class="section-heading">Focus</span>
  <h1 class="page-title">Research themes that I keep returning to</h1>
  <p class="page-intro">
    I am most interested in the systems layer beneath modern AI: how memory, scheduling, retrieval, verification, and runtime policy interact when workloads become large, heterogeneous, and failure-prone.
  </p>
</section>

<section class="card-grid">
  <article class="mini-card">
    <h2 class="card-title">LLM serving and inference systems</h2>
    <p class="card-copy">
      I work on efficient large-model inference with an emphasis on throughput, tail behavior, fairness, and memory pressure. That includes KV-cache management, batching strategy, runtime observability, and deterministic or verification-aware decoding.
    </p>
  </article>

  <article class="mini-card">
    <h2 class="card-title">Hybrid retrieval systems</h2>
    <p class="card-copy">
      I am interested in hybrid SQL plus vector retrieval as a coordination problem. The important question is not only which index to build, but how a system decides among SQL-first, vector-first, cooperative execution, and exact fallback under different regimes.
    </p>
  </article>

  <article class="mini-card">
    <h2 class="card-title">Trust, security, and recoverability</h2>
    <p class="card-copy">
      Another recurring theme in my work is making AI infrastructure more dependable. That includes secure multi-tenant serving, integrity or attestation for model execution, and recoverability-aware planning when agents interact with stateful tools.
    </p>
  </article>
</section>

<section class="page-card">
  <span class="section-heading">How I work</span>
  <h2 class="section-title">Systems research with builder instincts</h2>
  <ul class="detail-list">
    <li>I prefer mechanism-level explanations over vague stories.</li>
    <li>I care about real workloads more than toy wins.</li>
    <li>I like evaluating how an idea changes tail behavior, not only averages.</li>
    <li>I bring production systems instincts from Baidu into academic problem selection and evaluation.</li>
  </ul>
</section>
