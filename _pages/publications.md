---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

{% include base_path %}

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
.pub-section-title {
  display: flex;
  align-items: center;
  gap: 1rem;
  margin: 2.5rem 0 1.5rem;
  color: #111827;
  font-size: 1.4rem;
  font-weight: 700;
  letter-spacing: -0.02em;
}

.pub-section-title::after {
  content: "";
  flex: 1;
  height: 1px;
  background: linear-gradient(to right, #e5e7eb, transparent);
}

.pub-section-title:first-child {
  margin-top: 0;
}

.pub-list {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.pub-item {
  background: rgba(255,255,255,0.9);
  border: 1px solid #e5e7eb;
  border-left: 4px solid #2563eb;
  border-radius: 14px;
  padding: 1.2rem 1.4rem;
  box-shadow: 0 4px 16px rgba(15,23,42,0.05);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.pub-item:hover {
  transform: translateY(-2px);
  box-shadow: 0 10px 28px rgba(15,23,42,0.09);
}

.pub-item.preprint {
  border-left-color: #d97706;
}

.pub-title {
  font-size: 1rem;
  font-weight: 700;
  color: #111827;
  margin: 0 0 0.35rem;
  line-height: 1.4;
}

.pub-authors {
  font-size: 0.88rem;
  color: #6b7280;
  margin: 0 0 0.5rem;
}

.pub-authors strong {
  color: #374151;
  font-weight: 600;
}

.pub-venue-row {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 0.5rem;
  margin-bottom: 0.75rem;
}

.badge {
  display: inline-flex;
  align-items: center;
  gap: 0.3rem;
  padding: 0.2rem 0.6rem;
  border-radius: 999px;
  font-size: 0.72rem;
  font-weight: 700;
  letter-spacing: 0.03em;
  white-space: nowrap;
}

.badge-conference {
  background: #eff6ff;
  color: #1d4ed8;
}

.badge-journal {
  background: #f0fdf4;
  color: #15803d;
}

.badge-workshop {
  background: #faf5ff;
  color: #7e22ce;
}

.badge-preprint {
  background: #fffbeb;
  color: #b45309;
}

.badge-year {
  background: #f3f4f6;
  color: #6b7280;
}

.pub-links {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
}

.pub-link {
  display: inline-flex;
  align-items: center;
  gap: 0.3rem;
  padding: 0.25rem 0.7rem;
  border-radius: 8px;
  border: 1px solid #e5e7eb;
  font-size: 0.8rem;
  font-weight: 600;
  color: #374151;
  text-decoration: none;
  background: #f9fafb;
  transition: background 0.15s ease, border-color 0.15s ease;
}

.pub-link:hover {
  background: #eff6ff;
  border-color: #bfdbfe;
  color: #1d4ed8;
  text-decoration: none;
}

@media (max-width: 600px) {
  .pub-item {
    padding: 1rem;
    border-radius: 12px;
  }
}
</style>

<h2 class="pub-section-title">Accepted Papers</h2>

<ul class="pub-list">

  <li class="pub-item">
    <p class="pub-title">Latent Stochastic Interpolants for Probabilistic Time Series Forecasting</p>
    <p class="pub-authors">Bourgeat, M. &amp; <strong>Surendran, S.</strong></p>
    <div class="pub-venue-row">
      <span class="badge badge-workshop">ICML 2026 Workshop</span>
      <span class="badge badge-year">2026</span>
    </div>
    <div class="pub-links">
      <a class="pub-link" href="https://openreview.net/pdf?id=oBvLAlzGq3" target="_blank">
        <i class="fa-regular fa-file-pdf"></i> Paper
      </a>
    </div>
  </li>

  <li class="pub-item">
    <p class="pub-title">Latent Guided Sampling for Combinatorial Optimization</p>
    <p class="pub-authors"><strong>Surendran, S.</strong>, Fermanian, A., &amp; Le Corff, S.</p>
    <div class="pub-venue-row">
      <span class="badge badge-conference">ICML 2026</span>
      <span class="badge badge-year">2026</span>
    </div>
    <div class="pub-links">
      <a class="pub-link" href="https://arxiv.org/pdf/2506.03672" target="_blank"><i class="fa-regular fa-file-pdf"></i> Paper</a>
      <a class="pub-link" href="https://github.com/SobihanSurendran/LGS" target="_blank"><i class="fa-brands fa-github"></i> Code</a>
      <a class="pub-link" href="/files/Poster_ICML_2026_LGS.pdf" target="_blank"><i class="fa-solid fa-image"></i> Poster</a>
    </div>
  </li>

  <li class="pub-item">
    <p class="pub-title">Diffusion-Driven Latent Guided Sampling for Neural Combinatorial Optimization</p>
    <p class="pub-authors"><strong>Surendran, S.</strong>, Fermanian, A., &amp; Le Corff, S.</p>
    <div class="pub-venue-row">
      <span class="badge badge-workshop">ICLR 2026 Workshop</span>
      <span class="badge badge-year">2026</span>
    </div>
    <div class="pub-links">
      <a class="pub-link" href="https://openreview.net/pdf?id=0ljRxP9y5W" target="_blank"><i class="fa-regular fa-file-pdf"></i> Paper</a>
      <a class="pub-link" href="https://github.com/SobihanSurendran/LGS" target="_blank"><i class="fa-brands fa-github"></i> Code</a>
    </div>
  </li>

  <li class="pub-item">
    <p class="pub-title">Wasserstein Convergence of Critically Damped Langevin Diffusions</p>
    <p class="pub-authors">Strasman, S., <strong>Surendran, S.</strong>, Boyer, C., Le Corff, S., Lemaire, V., &amp; Ocello, A.</p>
    <div class="pub-venue-row">
      <span class="badge badge-conference">NeurIPS 2025</span>
      <span class="badge badge-year">2025</span>
    </div>
    <div class="pub-links">
      <a class="pub-link" href="https://openreview.net/pdf?id=a7bisLzORM" target="_blank"><i class="fa-regular fa-file-pdf"></i> Paper</a>
      <a class="pub-link" href="https://github.com/SobihanSurendran/CLD" target="_blank"><i class="fa-brands fa-github"></i> Code</a>
      <a class="pub-link" href="/files/Poster_NeurIPS_2025_CLD.pdf" target="_blank"><i class="fa-solid fa-image"></i> Poster</a>
    </div>
  </li>

  <li class="pub-item">
    <p class="pub-title">Theoretical Convergence Guarantees for Variational Autoencoders</p>
    <p class="pub-authors"><strong>Surendran, S.</strong>, Godichon-Baggioni, A., &amp; Le Corff, S.</p>
    <div class="pub-venue-row">
      <span class="badge badge-conference">AISTATS 2025</span>
      <span class="badge badge-year">2025</span>
    </div>
    <div class="pub-links">
      <a class="pub-link" href="https://arxiv.org/pdf/2410.16750" target="_blank"><i class="fa-regular fa-file-pdf"></i> Paper</a>
      <a class="pub-link" href="https://github.com/SobihanSurendran/VAE-Convergence-Guarantees" target="_blank"><i class="fa-brands fa-github"></i> Code</a>
      <a class="pub-link" href="/files/Poster_AISTATS_2025_VAE.pdf" target="_blank"><i class="fa-solid fa-image"></i> Poster</a>
    </div>
  </li>

  <li class="pub-item">
    <p class="pub-title">Non-asymptotic Analysis of Biased Adaptive Stochastic Approximation</p>
    <p class="pub-authors"><strong>Surendran, S.</strong>, Godichon-Baggioni, A., Fermanian, A., &amp; Le Corff, S.</p>
    <div class="pub-venue-row">
      <span class="badge badge-conference">NeurIPS 2024</span>
      <span class="badge badge-year">2024</span>
    </div>
    <div class="pub-links">
      <a class="pub-link" href="https://arxiv.org/pdf/2402.02857" target="_blank"><i class="fa-regular fa-file-pdf"></i> Paper</a>
      <a class="pub-link" href="https://github.com/SobihanSurendran/Adaptive-SA" target="_blank"><i class="fa-brands fa-github"></i> Code</a>
      <a class="pub-link" href="/files/Poster_NeurIPS_2024_SA.pdf" target="_blank"><i class="fa-solid fa-image"></i> Poster</a>
    </div>
  </li>

  <li class="pub-item">
    <p class="pub-title">A Penalized Criterion for Selecting the Number of Clusters for K-medians</p>
    <p class="pub-authors">Godichon-Baggioni, A. &amp; <strong>Surendran, S.</strong></p>
    <div class="pub-venue-row">
      <span class="badge badge-journal">JCGS 2024</span>
      <span class="badge badge-year">2024</span>
    </div>
    <div class="pub-links">
      <a class="pub-link" href="https://arxiv.org/pdf/2209.03597" target="_blank"><i class="fa-regular fa-file-pdf"></i> Paper</a>
      <a class="pub-link" href="https://cran.r-project.org/web/packages/Kmedians/index.html" target="_blank"><i class="fa-solid fa-code"></i> Code</a>
    </div>
  </li>

</ul>

<h2 class="pub-section-title">Preprints</h2>

<ul class="pub-list">

  <li class="pub-item preprint">
    <p class="pub-title">Non-asymptotic Convergence of Stochastic Gradient Descent in Score-based Generative Models</p>
    <p class="pub-authors">Strasman, S., <strong>Surendran, S.</strong>, &amp; Le Corff, S.</p>
    <div class="pub-venue-row">
      <span class="badge badge-preprint">Preprint</span>
      <span class="badge badge-year">2026</span>
    </div>
    <div class="pub-links">
      <a class="pub-link" href="https://arxiv.org/pdf/2607.04775" target="_blank">
        <i class="fa-regular fa-file-pdf"></i> Paper
      </a>
    </div>
  </li>

  <li class="pub-item preprint">
    <p class="pub-title">Convergence of Multi-Level Markov Chain Monte Carlo Adaptive Stochastic Gradient Algorithms</p>
    <p class="pub-authors">Godichon-Baggioni, A., Lang, G., Le Corff, S., Stoehr, J. &amp; <strong>Surendran, S.</strong></p>
    <div class="pub-venue-row">
      <span class="badge badge-preprint">Preprint</span>
      <span class="badge badge-year">2026</span>
    </div>
    <div class="pub-links">
      <a class="pub-link" href="https://arxiv.org/pdf/2601.22799" target="_blank"><i class="fa-regular fa-file-pdf"></i> Paper</a>
    </div>
  </li>

</ul>