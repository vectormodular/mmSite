---
layout: splash
title:  "Welcome"
permalink: /

hero_image: /assets/images/curModulesLanding.png

feature_row:
  - image_path: assets/images/baseosc.png
    alt: "baseOsc"
    title: "baseOsc"
    excerpt: "Versatile oscillator with analog waveforms, FM, PWM, wavetable synthesis, regular and digital noise, quantization, and bit reduction."
    url: /modules/baseOsc
    btn_label: "Overview"
    btn_class: "btn--inverse"
  - image_path: /assets/images/basetrig.png
    alt: "baseTrig"
    title: "baseTrig"
    excerpt: "Clock-signal generator with tempo control, reset, and rhythmic divisions."
    url: /modules/baseTrig
    btn_label: "Overview"
    btn_class: "btn--inverse"
  - image_path: assets/images/solomixer.png
    alt: "soloMixer"
    title: "soloMixer"
    excerpt: "Color-coded 3-channel mixer with solo performance control, cascading outputs, and CV offset."
    url: /modules/soloMixer
    btn_label: "Overview"
    btn_class: "btn--inverse"
feature_row2:

  - image_path: assets/images/3i9o.png
    alt: "3i/9o multiple"
    title: "3i/9o"
    excerpt: "Flexible multiple that uses normalled connections to connect outputs."
    url: /modules/3i9o
    btn_label: "Overview"
    btn_class: "btn--inverse"
---
<br> 
<div style="text-align: center;">
  <img src="{{ page.hero_image }}" alt="{{ page.title }}" style="max-width: 85%; height: auto; display: inline-block;">
  {% if page.hero_caption %}
  <div style="margin-top: 10px; color: white;">{{ page.hero_caption }}</div>
  {% endif %}
</div>
  <p>{{ page.hero_image }}</p>
<br>  
    

{% include feature_row id="intro" type="center" %}
<br>

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}
