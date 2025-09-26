---
title: "Scaling Dexterous Manipulation"
excerpt: "Real-to-Sim-to-Real for Dexterous Manipulation with Multi-fingered Hands"
collection: portfolio
image: "/images/portfolio/allegro_plate_manipulation_short.gif"
---

<p style="float: center; position: relative; margin-right: 5px; width:70%">
  <a>
    <img src="{{ page.image }}" alt="{{ page.title }}" style="border-radius: 20px; cursor: pointer; transition: transform 0.2s ease-in-out; width: 100%"/>
    <span class="image-text">Panda-Allegro setup with Xela tactile sensors</span>
  </a>
</p>

<!-- <p style="float: center; position: relative; margin-right: 5px; width:70%">
<a>
<img src="/images/portfolio/panda_finray_box_pushing_real_world.gif" width="100%" style="border-radius:5%; cursor: pointer; transition: transform 0.2s ease-in-out;"/>
<span class="image-text"> Zero-shot Real World Execution </span>
</a>
</p> -->

<div style="clear: both;"></div>


We are developing scalable real-to-sim-to-real learning pipelines that combine behavior cloning from real-world demonstrations with reinforcement learning (RL). Demonstrations collected on real robots provide an effective warm start for RL, enabling curriculum-style training that extends behavior beyond the demonstrations. Our platform focuses on dexterous manipulation with multi-fingered Allegro hands equipped with Xela tactile sensors, allowing us to investigate how tactile feedback supports sim-to-real transfer. This integration of demonstrations, RL, and tactile sensing aims to accelerate policy learning while achieving robust performance in complex manipulation tasks.


<!-- <p style="float: left; position: relative; margin-right: 5px;">
  <a>
    <img src="/images/portfolio/isaac_sim_tacsl_training.gif" width="438" style="border-radius:5%; cursor: pointer; transition: transform 0.2s ease-in-out;"/>
    <span class="image-text">Large Scale Simulation RL Training</span>
  </a>
</p>

<p style="float: left; position: relative; margin-right: 5px;">
  <a>
    <img src="/images/portfolio/tactile_insertion_rw.gif" width="200" style="border-radius:5%; cursor: pointer; transition: transform 0.2s ease-in-out;"/>
    <span class="image-text">Zero-shot Real World Execution</span>
  </a>
</p> -->


<style>
  /* Hover effect for enlarging the image */
  a img:hover {
    transform: scale(1);
  }

  /* Text appearance settings */
  .image-text {
    position: absolute;
    bottom: 10px;
    left: 50%;
    width: 80%;
    transform: translateX(-50%);
    background-color: rgba(0, 0, 0, 0.6);
    color: white;
    padding: 5px 10px;
    border-radius: 5px;
    display: none;
    font-size: 14px;
    text-align: center;
  }

  /* Show text when hovering over the image */
  a:hover .image-text {
    display: block;
  }

  /* Apply shadowing and reduce opacity only when hovered */
  a img:hover {
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.3);
    opacity: 1; /* Reset opacity to full */
  }

  /* Remove opacity and shadowing when not hovered */
  a img {
    opacity: 1; /* Ensure opacity is normal when not hovered */
    transition: opacity 0.2s ease-in-out, box-shadow 0.2s ease-in-out;
  }
 </style>

<div style="clear: both;"></div>
<p>
Our goal is to enable real-world manipulation systems to learn complex skills without requiring large-scale real-world data collection.
</p>