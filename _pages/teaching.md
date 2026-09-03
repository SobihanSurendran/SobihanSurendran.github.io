---
layout: archive
title: ""
permalink: /teaching/
author_profile: true
---

{% include base_path %}

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
.teaching-section-title {
  display: flex;
  align-items: center;
  gap: 1rem;
  margin: 0 0 1.8rem;
  color: #111827;
  font-size: 1.4rem;
  font-weight: 700;
  letter-spacing: -0.02em;
}

.teaching-section-title::after {
  content: "";
  flex: 1;
  height: 1px;
  background: linear-gradient(to right, #e5e7eb, transparent);
}

.timeline {
  position: relative;
  padding-left: 2.8rem;
}

.timeline::before {
  content: "";
  position: absolute;
  left: 0.65rem;
  top: 0.3rem;
  bottom: 0.3rem;
  width: 3px;
  border-radius: 999px;
  background: linear-gradient(to bottom, #b45309, #fde68a);
}

.timeline-item {
  position: relative;
  margin-bottom: 1.35rem;
}

.timeline-item:last-child {
  margin-bottom: 0;
}

.timeline-dot {
  position: absolute;
  left: -2.55rem;
  top: 1.45rem;
  width: 1.05rem;
  height: 1.05rem;
  border-radius: 999px;
  background: #b45309;
  border: 3px solid #f9fafb;
  box-shadow: 0 0 0 3px rgba(180, 83, 9, 0.2);
}

.timeline-card {
  position: relative;
  overflow: hidden;
  background: rgba(255, 255, 255, 0.9);
  border: 1px solid #e5e7eb;
  border-left: 4px solid #b45309;
  border-radius: 14px;
  padding: 1.2rem 1.4rem;
  box-shadow: 0 4px 16px rgba(15, 23, 42, 0.05);
  transition: transform 0.22s ease, box-shadow 0.22s ease;
}

.timeline-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 10px 28px rgba(15, 23, 42, 0.09);
}

.timeline-card-title {
  font-size: 1rem;
  font-weight: 700;
  color: #111827;
  margin: 0 0 0.15rem;
  line-height: 1.4;
}

.timeline-card-meta {
  display: flex;
  flex-wrap: wrap;
  gap: 0.35rem 0.8rem;
  color: #6b7280;
  font-size: 0.84rem;
  margin: 0 0 0.7rem;
}

.timeline-card-meta span {
  display: inline-flex;
  align-items: center;
  gap: 0.35rem;
}

.timeline-card-desc {
  font-size: 0.91rem;
  color: #4b5563;
  margin: 0;
  line-height: 1.6;
}

.badge-current {
  display: inline-flex;
  align-items: center;
  margin-left: 0.45rem;
  padding: 0.18rem 0.55rem;
  border-radius: 999px;
  background: #b45309;
  color: white;
  font-size: 0.66rem;
  font-weight: 700;
  letter-spacing: 0.045em;
  text-transform: uppercase;
  vertical-align: middle;
  white-space: nowrap;
}

@media (max-width: 600px) {
  .timeline {
    padding-left: 2.05rem;
  }
  .timeline::before {
    left: 0.45rem;
  }
  .timeline-dot {
    left: -2.02rem;
  }
  .timeline-card {
    padding: 1rem;
    border-radius: 12px;
  }
}
</style>

<h2 class="teaching-section-title">Teaching</h2>

<div class="timeline">

  <div class="timeline-item">
    <div class="timeline-dot" aria-hidden="true"></div>
    <div class="timeline-card">
      <p class="timeline-card-title">Statistical Learning</p>
      <div class="timeline-card-meta">
        <span><i class="fa-solid fa-building-columns"></i> Sorbonne Université</span>
        <span><i class="fa-regular fa-calendar"></i> 2023 – 2026</span>
      </div>
      <p class="timeline-card-desc">Python computer labs introducing fundamental concepts in statistical learning and machine learning (regression, classification, clustering, optimization, and neural networks) for Master's students in Applied Mathematics.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-dot" aria-hidden="true"></div>
    <div class="timeline-card">
      <p class="timeline-card-title">Nonparametric Statistics and High-Dimensional Data</p>
      <div class="timeline-card-meta">
        <span><i class="fa-solid fa-building-columns"></i> Sorbonne Université</span>
        <span><i class="fa-regular fa-calendar"></i> 2023 – 2026</span>
      </div>
      <p class="timeline-card-desc">Exercise classes on advanced topics in statistics (nonparametric testing, nonparametric regression, supervised classification, and high-dimensional estimation and shrinkage) for Master's students in Applied Mathematics.</p>
    </div>
  </div>

</div>