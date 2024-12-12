---
permalink: /
title: "👋🏼 Hello there, I'm Miquel!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

👨🏻‍💻 I'm a fifth year robotics PhD student at University of Michigan in the [MMINT Lab](https://mmintlab.com), where I work under the guidance of [Prof. Nima Fazeli](https://www.mmintlab.com/people/nima-fazeli/).

🔬 My research focuses on tactile-based manipulation, combining learning, optimization, and controls to enable robots to interact more intelligently and effectively with their environments.

🎓 As I approach graduation (March 2025), I'm excited to explore opportunities to apply my skills and advance robotics research. These days, I'm particularly interested in using tactile sensing for dexterous conctact-rich robotic manipulation.


# Highlights

Some recent highlights from our research:

<!-- <p float="left">
  <a href="/publication/2023-08-30-tactile-vad"><img src="/images/projects/tactile_cartpole_speedup_lowres.gif" width="330" /></a>
  <a href="/publication/2022-09-27-manipulation-via_membranes"><img src="/images/projects/bubble_pivoting_optimized-2.gif" width="253" /></a>
</p> -->

<!-- <p float="left">
  <a href="/publication/2023-08-30-tactile-vad"><img src="/images/projects/tactile_cartpole_speedup_lowres.gif" width="240" /></a>
  <a href="/publication/2022-09-27-manipulation-via_membranes"><img src="/images/projects/bubble_pivoting_optimized-2.gif" width="184" /></a>
  <a href="/publication/2024-02-30-tactile-nonprehensile"><img src="/images/projects/extrinsic_pivoting_cropped.gif" width="122"/></a>
</p> -->

<p float="left">
  <a href="/publication/2023-08-30-tactile-vad"><img src="/images/projects/tactile_cartpole_cropped.gif" width="280" style="border-radius:5%" /></a>
  <a href="/publication/2024-02-30-tactile-nonprehensile"><img src="/images/projects/extrinsic_pivoting_cropped.gif" width="168" style="border-radius:5%"/></a>
  <a href="/publication/2022-09-27-manipulation-via_membranes"><img src="/images/projects/bubble_pivoting_optimized-2.gif" width="252" style="border-radius:5%"/></a>
</p>


<!-- ![Tactile-Driven Non-Prehensile Object Manipulation via Extrinsic Contact Mode Control](/images/projects/tactile_cartpole_speedup_lowres.gif)
![Tactile-Driven Non-Prehensile Object Manipulation via Extrinsic Contact Mode Control](/images/projects/extrinsic_pivoting.gif)
![Tactile-Driven Non-Prehensile Object Manipulation via Extrinsic Contact Mode Control](/images/projects/bubble_pivoting_optimized-2.gif) -->

<!-- Button to toggle content -->
<!-- <button onclick="toggleContent()" style="margin-top: 1em;">Show More Research Projects</button> -->
<!-- Button to toggle content -->
<div style="text-align: center; margin-top: 1em;">
  <button 
    onclick="toggleContent()" 
    style="
      background-color: #007BFF; 
      color: white; 
      padding: 15px 30px; 
      font-size: 18px; 
      border: none; 
      border-radius: 25px; 
      cursor: pointer;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);"
  >
    Show More Research Projects
  </button>
</div>

<!-- Content to toggle -->
<div id="moreContent" style="display: none; margin-top: 1em;">
  <h1> Publications </h1>
  
  {% include base_path %}

  {% for post in site.publications reversed %}
    {% include archive-single-publication.html %}
  {% endfor %}
</div>

<script>
  function toggleContent() {
    const content = document.getElementById("moreContent");
    const button = event.target;

    if (content.style.display === "none") {
      content.style.display = "block";
      button.innerText = "Show Less";
    } else {
      content.style.display = "none";
      button.innerText = "Show More Research Projects";
    }
  }
</script>