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
  - image_path: /assets/images/placeholder.png
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/placeholder.png
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/placeholder.png
    alt: "placeholder image 4"
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
---

<h1 class="page-title">Introduction + Demo Reel</h1>

<div class="mock-layout">

  <!-- LEFT IMAGE -->
  <div class="side">
    <img src="/assets/images/gameCatalogue.png" alt="Left panel">
  </div>

  <!-- CENTER VIDEO -->
  <div class="center">
    <h2>Demo Video</h2>
    <hr>

    <div class="video-wrapper">
      {% include video id="dQw4w9WgXcQ" provider="youtube" %}
    </div>
  </div>

  <!-- RIGHT IMAGE -->
  <div class="side">
    <img src="/assets/images/gameCatalogue2.png" alt="Right panel">
  </div>

</div>

{% include feature_row %}
