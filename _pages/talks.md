---
layout: archive
title: ""
permalink: /talks/
author_profile: true
redirect_from:
  - /talks.html
---

{% include base_path %}

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
.talks-section-title {
  display: flex;
  align-items: center;
  gap: 1rem;
  margin: 0 0 1.8rem;
  color: #111827;
  font-size: 1.4rem;
  font-weight: 700;
  letter-spacing: -0.02em;
}

.talks-section-title::after {
  content: "";
  flex: 1;
  height: 1px;
  background: linear-gradient(to right, #e5e7eb, transparent);
}

.talk-list {
  display: flex;
  flex-direction: column;
  gap: 0.5rem;
  padding: 0;
  margin: 0;
  list-style: none;
}

.talk-item {
  display: flex;
  align-items: baseline;
  gap: 0.75rem;
  background: rgba(255,255,255,0.9);
  border: 1px solid #e5e7eb;
  border-left: 3px solid #7e22ce;
  border-radius: 10px;
  padding: 0.7rem 1rem;
  box-shadow: 0 2px 8px rgba(15,23,42,0.04);
  transition: transform 0.18s ease, box-shadow 0.18s ease;
}

.talk-item:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 18px rgba(15,23,42,0.08);
}

.talk-month {
  font-size: 0.75rem;
  font-weight: 700;
  color: #7e22ce;
  background: #faf5ff;
  padding: 0.15rem 0.5rem;
  border-radius: 999px;
  white-space: nowrap;
  flex-shrink: 0;
}

.talk-content {
  flex: 1;
}

.talk-title {
  font-size: 0.92rem;
  font-weight: 700;
  color: #111827;
  margin: 0 0 0.15rem;
  line-height: 1.3;
}

.talk-meta {
  font-size: 0.8rem;
  color: #6b7280;
  display: flex;
  flex-wrap: wrap;
  gap: 0.3rem 0.7rem;
}

.talk-meta span {
  display: inline-flex;
  align-items: center;
  gap: 0.3rem;
}

@media (max-width: 600px) {
  .talk-item {
    flex-direction: column;
    gap: 0.4rem;
  }
}
</style>

<h2 class="talks-section-title">Talks and Presentations</h2>

<ul class="talk-list">

  <li class="talk-item">
    <span class="talk-month">Mar 2026</span>
    <div class="talk-content">
      <p class="talk-title">Doctoral Seminar at LPSM</p>
      <div class="talk-meta">
        <span><i class="fa-solid fa-building-columns"></i> Sorbonne Université</span>
        <span><i class="fa-solid fa-location-dot"></i> Paris, France</span>
      </div>
    </div>
  </li>

  <li class="talk-item">
    <span class="talk-month">Dec 2025</span>
    <div class="talk-content">
      <p class="talk-title">CERMICS × SCALE AI Workshop</p>
      <div class="talk-meta">
        <span><i class="fa-solid fa-building-columns"></i> École des Ponts</span>
        <span><i class="fa-solid fa-location-dot"></i> Paris, France</span>
      </div>
    </div>
  </li>

  <li class="talk-item">
    <span class="talk-month">Nov 2025</span>
    <div class="talk-content">
      <p class="talk-title">Seminar at CIRRELT</p>
      <div class="talk-meta">
        <span><i class="fa-solid fa-building-columns"></i> École Polytechnique de Montréal</span>
        <span><i class="fa-solid fa-location-dot"></i> Montréal, Canada</span>
      </div>
    </div>
  </li>

  <li class="talk-item">
    <span class="talk-month">Jun 2025</span>
    <div class="talk-content">
      <p class="talk-title">56es Journées de Statistique</p>
      <div class="talk-meta">
        <span><i class="fa-solid fa-location-dot"></i> Marseille, France</span>
      </div>
    </div>
  </li>

  <li class="talk-item">
    <span class="talk-month">May 2025</span>
    <div class="talk-content">
      <p class="talk-title">AISTATS 2025</p>
      <div class="talk-meta">
        <span><i class="fa-solid fa-location-dot"></i> Phuket, Thailand</span>
      </div>
    </div>
  </li>

  <li class="talk-item">
    <span class="talk-month">Dec 2024</span>
    <div class="talk-content">
      <p class="talk-title">NeurIPS 2024</p>
      <div class="talk-meta">
        <span><i class="fa-solid fa-location-dot"></i> Vancouver, Canada</span>
      </div>
    </div>
  </li>

  <li class="talk-item">
    <span class="talk-month">Nov 2024</span>
    <div class="talk-content">
      <p class="talk-title">NeurIPS@Paris 2024</p>
      <div class="talk-meta">
        <span><i class="fa-solid fa-location-dot"></i> Paris, France</span>
      </div>
    </div>
  </li>

  <li class="talk-item">
    <span class="talk-month">May 2024</span>
    <div class="talk-content">
      <p class="talk-title">55es Journées de Statistique</p>
      <div class="talk-meta">
        <span><i class="fa-solid fa-location-dot"></i> Bordeaux, France</span>
      </div>
    </div>
  </li>

</ul>