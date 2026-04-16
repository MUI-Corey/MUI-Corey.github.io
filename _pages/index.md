---
title: "Welcome to Coraero!"
layout: default
permalink: /
header:
  overlay_color: "#eae480"
  overlay_filter: "0.3"
  overlay_image: /assets/images/vsTrainer6.png
  actions:
    - label: "Download CV"
      url: "https://drive.google.com/file/d/1FydacrDlFFgt4JTXGL831cb4WU37lcg1/view?usp=sharing"
      target: "_blank"


excerpt: "You experience a sudden urge of intrigue..."
intro: 
  - excerpt: 'You can also add text like this....'
feature_row:
  - image_path: /assets/images/2d-game-3.png
    alt: "2D Game"
    title: "2D Game"
    excerpt: "This was the first **2D** game I created. It features a parralax background, a hunger mechanic and quick movement."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/3d-game-3.png
    alt: "3D game"
    title: "3D Game"
    excerpt: "This was the first **3D** game I created. It feaures a coin collecting mechanic, strafe running and jumping for platforming and a dim-lit foggy environment."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/placeholder.png
    alt: "placeholder image 4"
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

<h1 class="page-title">Introduction + Demo Reel</h1>

<div class="mock-layout">

  <!-- LEFT PANEL -->
  <div class="panel">
    <img src="/assets/images/gameCatalogue.png" alt="Left panel">
    <p class="panel-text">Games I've been inspired by.</p>
  </div>

  <!-- CENTER VIDEO -->
  <div class="center">
    <h2>Demo Video</h2>
    <hr>

    <div class="video-wrapper">
      {% include video id="dQw4w9WgXcQ" provider="youtube" %}
    </div>

    <p class="panel-text">A showcase of my recent work and projects.</p>
  </div>

  <!-- RIGHT PANEL -->
  <div class="panel">
    <img src="/assets/images/gameCatalogue2.png" alt="Right panel">
    <p class="panel-text">Games I've been inspired by.</p>
  </div>

</div>

{% include feature_row %}
