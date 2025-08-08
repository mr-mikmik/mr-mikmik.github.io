---
title: "Sim-to-Real RL for Manipulation"
excerpt: "Sim-to-Real Policy Transfer for Contact-Rich Manipulation via Simulation-Trained RL"
collection: portfolio
image: "/images/portfolio/planar_pushing_ppo_jax_opt.gif"
---

<p style="float: center; position: relative; margin-right: 5px; width:70%">
  <a>
    <img src="{{ page.image }}" alt="{{ page.title }}" style="border-radius: 20px; cursor: pointer; transition: transform 0.2s ease-in-out; width: 100%"/>
    <span class="image-text">Fast and Efficient Simulation Training with MuJoCo + JAX (30min)</span>
  </a>
</p>

<img src="/images/portfolio/panda_finray_box_pushing_real_world.gif" width="70%" style="border-radius:5%; cursor: pointer; transition: transform 0.2s ease-in-out;"/>

<div style="clear: both;"></div>


We are developing reinforcement learning (RL) policies for contact-rich robotic manipulation tasks in simulation and transferring them effectively to the real world. Contact-rich interactions—such as sliding, pivoting, or insertion are especially challenging due to their sensitivity to dynamics and high precision requirements. By leveraging physics-based simulators, we train robust control policies and explore strategies for bridging the sim-to-real gap.


<p style="float: left; position: relative; margin-right: 5px;">
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
</p>


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
 <!-- This work contributes to building more generalizable and adaptable robotic systems that can handle uncertainty, model mismatch, and variability in real environments while maintaining high performance on fine-grained, physical tasks. -->
</p>