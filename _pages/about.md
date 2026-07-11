---
layout: about
title: about
permalink: /
subtitle:

profile:
  align: right
  image: face.jpeg
  image_circular: false # crops the image to make it circular
  more_info:

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
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

Hi, I am Hiroyuki Deguchi (出口 裕之).

I am pursuing my first year as a PhD candidate at [Keio University](https://www.keio.ac.jp/en/st/) under the guidance of [Prof. Hideo Saito](http://www.hvrl.ics.keio.ac.jp/), and also a research
assistant at the [Digital Human Research Team](https://dhrt.notion.site/Digital-Human-Research-Team-AIRC-AIST-8d53e3c09734402092effc93f52eee6a), part of the [Artificial Intelligence Research Center](https://www.airc.aist.go.jp/en/) at the [National Institute of Advanced
Industrial Science and Technology (AIST)](https://www.aist.go.jp/index_en.html).

My research focuses on computer vision, especially egocentric vision, human motion capture, and 3D human reconstruction using multimodal
sensors. More broadly, I am interested in human-centered visual understanding and in building robust vision systems that connect
perception in the real world with digital human modeling, with a long-term interest in humanoid applications.

## News

**May 11, 2026.** One paper accepted to IEEE International Conference on Image Processing.

**June 7, 2024.** One paper accepted to IEEE International Conference on Image Processing.

**Jul 28, 2023.** Received the "Demo Presentation Award" and the "Student Encouragement Award" at MIRU 2023.

## Publications

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
    <img class="publication-thumb" src="{{ '/assets/img/ACCESS2025.png' | relative_url }}" alt="Gait Inertial Poser preview">
    <div>
      <div>R. Hori, <strong>H. Deguchi</strong>, T. Maruyama, M. Tada, and H. Saito</div>
      <div class="publication-title">Gait Inertial Poser (GIP): Gait-Aware Human Motion Capture Using Shoe-Embedded IMUs</div>
      <div>IEEE Access, vol. 13, pp. 183262-183282, 2025.</div>
      <div class="publication-links"><a href="https://ieeexplore.ieee.org/document/11214366">DOI</a></div>
    </div>
  </article>

  <article class="publication-item">
    <img class="publication-thumb" src="{{ '/assets/img/CHI2025.png' | relative_url }}" alt="Realtime Smart Gait Poser preview">
    <div>
      <div><strong>H. Deguchi</strong>*, R. Hori*, T. Maruyama, M. Tada, and H. Saito</div>
      <div class="publication-title">Realtime Smart Gait Poser for Foot Augmentation</div>
      <div>CHI 2025 Workshop, 2025.</div>
    </div>
  </article>

  <article class="publication-item">
    <img class="publication-thumb" src="{{ '/assets/img/ICIP2024.png' | relative_url }}" alt="E2GS preview">
    <div>
      <div><strong>H. Deguchi</strong>*, M. Masuda*, T. Nakabayashi, and H. Saito</div>
      <div class="publication-title">E2GS: Event Enhanced Gaussian Splatting</div>
      <div>In Proceedings of the 2024 IEEE International Conference on Image Processing (ICIP), pp. 1676-1682, 2024.</div>
      <div class="publication-links"><a href="https://ieeexplore.ieee.org/document/10647607">DOI</a></div>
    </div>
  </article>
</div>
