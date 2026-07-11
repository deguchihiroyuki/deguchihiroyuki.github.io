---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 1
---

<style>
  .publication-list {
    display: grid;
    gap: 1.75rem;
    margin-bottom: 2rem;
  }

  .publication-item {
    display: grid;
    grid-template-columns: minmax(0, 210px) minmax(0, 1fr);
    gap: 1rem;
    align-items: start;
  }

  .publication-thumb {
    width: 100%;
    border-radius: 6px;
    border: 1px solid var(--global-divider-color);
  }

  .publication-title {
    font-weight: 600;
  }

  .publication-links {
    margin-top: 0.35rem;
  }

  @media (max-width: 640px) {
    .publication-item {
      grid-template-columns: 1fr;
    }

    .publication-thumb {
      max-width: 320px;
    }
  }
</style>

## Conference Proceedings

<div class="publication-list">
  <article class="publication-item">
    <img class="publication-thumb" src="{{ '/assets/img/ICIP2026.png' | relative_url }}" alt="Map-Mono-Ego preview">
    <div>
      <div><strong>H. Deguchi</strong>, Ryosuke Hori, Kotaro Amaya, Tsubasa Maruyama, Mitsunori Tada, and Hideo Saito</div>
      <div class="publication-title">Map-Mono-Ego: Map-Grounded Global Human Pose Estimation from Monocular Egocentric Video</div>
      <div>In Proceedings of the 2026 IEEE International Conference on Image Processing (ICIP).</div>
      <div class="publication-links"><a href="https://deguchihiroyuki.github.io/Map-Mono-Ego-Project/">Website</a></div>
    </div>
  </article>

  <article class="publication-item">
    <img class="publication-thumb" src="{{ '/assets/img/ICIP2024.png' | relative_url }}" alt="E2GS preview">
    <div>
      <div><strong>H. Deguchi</strong>*, M. Masuda*, T. Nakabayashi, and H. Saito</div>
      <div class="publication-title">E2GS: Event Enhanced Gaussian Splatting</div>
      <div>In Proceedings of the 2024 IEEE International Conference on Image Processing (ICIP), pp. 1676-1682, 2024.</div>
      <div>DOI: 10.1109/ICIP51287.2024.10647607.</div>
      <div class="publication-links"><a href="https://ieeexplore.ieee.org/document/10647607">DOI</a></div>
    </div>
  </article>
</div>

## Journal Articles

<div class="publication-list">
  <article class="publication-item">
    <img class="publication-thumb" src="{{ '/assets/img/ACCESS2025.png' | relative_url }}" alt="Gait Inertial Poser preview">
    <div>
      <div>R. Hori, <strong>H. Deguchi</strong>, T. Maruyama, M. Tada, and H. Saito</div>
      <div class="publication-title">Gait Inertial Poser (GIP): Gait-Aware Human Motion Capture Using Shoe-Embedded IMUs</div>
      <div>IEEE Access, vol. 13, pp. 183262-183282, 2025.</div>
      <div>DOI: 10.1109/ACCESS.2025.3624393.</div>
      <div class="publication-links"><a href="https://ieeexplore.ieee.org/document/11214366">DOI</a></div>
    </div>
  </article>
</div>

## Workshop Papers

<div class="publication-list">
  <article class="publication-item">
    <img class="publication-thumb" src="{{ '/assets/img/CHI2025.png' | relative_url }}" alt="Realtime Smart Gait Poser preview">
    <div>
      <div><strong>H. Deguchi</strong>*, R. Hori*, T. Maruyama, M. Tada, and H. Saito</div>
      <div class="publication-title">Realtime Smart Gait Poser for Foot Augmentation</div>
      <div>CHI 2025 Workshop, 2025.</div>
    </div>
  </article>
</div>
