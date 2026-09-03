---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
.about-bio {
  font-size: 0.97rem;
  color: #374151;
  line-height: 1.8;
  margin: 0 0 2rem;
}

.about-bio a {
  color: #2563eb;
  text-decoration: none;
  font-weight: 500;
}

.about-bio a:hover {
  text-decoration: underline;
}

.about-section-title {
  display: flex;
  align-items: center;
  gap: 1rem;
  margin: 0 0 1.2rem;
  color: #111827;
  font-size: 1.2rem;
  font-weight: 700;
  letter-spacing: -0.02em;
}

.about-section-title::after {
  content: "";
  flex: 1;
  height: 1px;
  background: linear-gradient(to right, #e5e7eb, transparent);
}

.interests-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 0.6rem;
  padding: 0;
  margin: 0;
  list-style: none;
}

.interest-badge {
  display: inline-flex;
  align-items: center;
  gap: 0.4rem;
  padding: 0.4rem 0.9rem;
  border-radius: 999px;
  border: 1px solid #e5e7eb;
  background: rgba(255,255,255,0.9);
  font-size: 0.86rem;
  font-weight: 600;
  color: #374151;
  box-shadow: 0 2px 8px rgba(15,23,42,0.05);
  transition: transform 0.18s ease, box-shadow 0.18s ease;
}

.interest-badge:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 16px rgba(15,23,42,0.09);
}

.interest-badge i {
  color: #2563eb;
  font-size: 0.85rem;
}
</style>

<p class="about-bio">
I am currently a final-year PhD student in Machine Learning and Optimization at Sorbonne Université. I work within the Department of Statistics (LPSM) under the supervision of <a href="https://godichon.perso.math.cnrs.fr/">Antoine Godichon-Baggioni</a> (Sorbonne Université), <a href="https://sylvainlc.github.io/">Sylvain Le Corff</a> (Sorbonne Université), and <a href="https://afermanian.github.io/">Adeline Fermanian</a> (Califrais). I was also a visiting PhD student at CIRRELT, École Polytechnique de Montréal, under the supervision of <a href="https://w1.cirrelt.ca/~vidalt/en/home-thibaut-vidal.html">Thibaut Vidal</a>. My research focuses on the theoretical aspects of stochastic optimization and generative models, with applications of generative models to vehicle routing problems. I am also interested in probabilistic time-series forecasting using generative models, particularly foundation models for time series.
</p>

<h2 class="about-section-title">Research Interests</h2>

<ul class="interests-grid">
  <li class="interest-badge">Stochastic Optimization</li>
  <li class="interest-badge">Diffusion Models</li>
  <li class="interest-badge">Variational Inference</li>
  <li class="interest-badge">Neural Combinatorial Optimization</li>
  <li class="interest-badge">Vehicle Routing Problems</li>
  <li class="interest-badge">Probabilistic Time Series Forecasting</li>
</ul>