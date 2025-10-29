---
layout: about
title: Geng Yihao
permalink: /
subtitle: Undergraduate Research Assistant, <a href='https://www.zoeticrobotics.com/'>Zoetic Robotics Lab</a> · <a href='https://umich.edu/'>University of Michigan</a>  
Email: <a href="mailto:yhgeng@umich.edu">yhgeng@umich.edu</a>

profile:
  align: right
  image: pic_psed.png
  image_circular: false
  more_info: >
selected_papers: false
social: true

announcements:
  enabled: false
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

### **Biography**

I recently graduated with a **B.S.E in Computer Science** from the **University of Michigan**, where I now work as an **Undergraduate Research Assistant** at the **Zoetic Robotics Lab**, supervised by **Dr. Cameron Aubin**. 

My research focuses on **bio-inspired, micro-scale and soft robotics**. 

At Michigan, I have worked on several projects, including the development of [**amphibious screw-propelled micro-robots**](./#amphibious-robot) and **suction cups with active delamination and energy-harvesting mechanisms**. Our work on suction cup control, [***“Release Chamber Enables Suction Cup to Delaminate and Harvest Fluid,”***](./#release-chamber) was recognized as a **Best Student Paper Finalist** and received the **Best Paper Award in Benchmarking and Reproducibility** at the **2025 IEEE International Conference on Soft Robotics (RoboSoft)**.

I am also a **co-first author** on the upcoming paper [***“Field-Effect Elastocapillary Actuators,”***](./#liquid_mdetal_actuator) which explores novel muscle-like actuators based on field-effect elastocapillary mechanisms.

<p class="bio-note">
  <strong>
    <a href="https://bulletin.engin.umich.edu/courses/eecs/" target="_blank">
      Relevant Courses:
    </a>
  </strong>
  Intro to Machine Learning, Computer Vision, Information Retrieval & Web Search, Intro to Computer Security, Intro to Cryptography, Extended Reality for Social Impact, Sensors & Signals
</p>

<hr style="height:3px; background-color:#000; border:none; margin:2rem 0;">

<div align="center" markdown="1">

<h3 style="font-weight:700; font-size:1.75rem; text-align:center; margin-bottom:25px;">Projects</h3>


####  <a id="release-chamber"></a>[**Release Chamber Enables Suction Cup to Delaminate and Harvest Fluid**](https://ieeexplore.ieee.org/document/11020908)

##### **X. Bu, Y. Geng, S. Yin, L. Luo, C. A. Aubin and T. Y. Moore**
###### **RoboSoft 2025** 
###### **Best Student Paper Finalist** 
###### **Best Paper Award for Benchmarking and Reproducibility**

<img src="/assets/img/figure1.webp"
     alt="Suction Cup Project"
     style="width:100%; display:block; margin:0 auto; border:2px solid #000; border-radius:8px;">

<img src="/assets/img/fluid_in.gif"
     alt="Suction Cup Demonstration"
     style="width:100%; display:block; margin:0 auto; border:2px solid #000; border-radius:8px;">

<p style="text-align:right; margin-top:10px;">
  <a href="https://www.embirlab.com/suctionrelease"><strong>Learn More</strong></a>
</p>




<hr style="height:3px; background-color:#000; border:none; margin:2rem 0;">

####  <a id="liquid_mdetal_actuator"></a>**Field-Effect Elastocapillary Actuators**

##### **Publication in Preparation**


<video autoplay loop muted playsinline
       style="width:100%; display:block; margin:0 auto; border:2px solid #000; border-radius:8px;">
  <source src="/assets/video/dragonfly.mp4" type="video/mp4">
</video>


<hr style="height:3px; background-color:#000; border:none; margin:2rem 0;">

#### <a id="amphibious-robot"></a>**Amphibious Screw-Propelled Micro Robot**

##### **Publication in Preparation**


<img src="/assets/img/amphibious.gif"
     alt="Amphibious Robot Demonstration"
     style="width:100%; display:block; margin:0 auto; border:2px solid #000; border-radius:8px;">



<hr style="height:3px; background-color:#000; border:none; margin:2rem 0;">

#### Capstone Project: **Ecology Education Enhanced**

##### **Educational Virtual Reality Program**


<div style="
  position:relative;
  width:100%;
  max-width:100%;
  margin:20px auto;">
  
  <video
    id="eeeVideo"
    muted
    loop
    playsinline
    controls
    poster="/assets/img/cover.png"
    style="
      width:100%;
      height:auto;
      display:block;
      margin:0 auto;
      border:2px solid #000;
      border-radius:8px;
      background-color:#000;">
    <source src="https://d3qrnjr4uo2u6l.cloudfront.net/videos/market.mp4" type="video/mp4">
  </video>

  <!-- Unmute button -->
  <button
    id="unmuteBtn"
    style="
      position:absolute;
      bottom:20px;
      right:25px;
      background-color:rgba(0,0,0,0.65);
      color:white;
      border:none;
      border-radius:6px;
      padding:8px 14px;
      cursor:pointer;
      font-weight:600;
      font-size:0.9rem;
      transition:all 0.3s ease;">
    🔈 Unmute
  </button>
</div>

<script>
  const video = document.getElementById('eeeVideo');
  const btn = document.getElementById('unmuteBtn');

  btn.addEventListener('click', () => {
    if (video.muted) {
      video.muted = false;
      btn.textContent = '🔇 Mute';
    } else {
      video.muted = true;
      btn.textContent = '🔈 Unmute';
    }
  });
</script>

<p style="text-align:right; margin-top:10px;">
  <a href="https://d3qrnjr4uo2u6l.cloudfront.net/"><strong>Learn More</strong></a>
</p>


</div>
