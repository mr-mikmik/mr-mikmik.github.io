---
title: "TactileVAD: Geometric Aliasing-Aware Dynamics for High-Resolution Tactile Control"
collection: publications
permalink: /publication/2023-08-30-tactile-vad
excerpt: 'Our paper introduces TactileVAD, a decoder-only control method that resolves tactile geometric aliasing, improving performance and reliability in touch-based manipulation across various tactile sensors.'
date: 2023-08-30
venue: '7th Conference on Robotic Learning (CoRL)'
image: "/images/projects/tactile_cartpole_speedup_lowres.gif"
paperurl: 'https://openreview.net/pdf?id=FefFLN5FvIM'
# authors: '<b>Oller, M. </b>, Berenson, D., & Fazeli, N.'
authors: '<b>Miquel Oller</b>, Dmitry Berenson, Nima Fazeli'
citation: '<b>Oller, M. </b>, Berenson, D., & Fazeli, N. &quot; "TactileVAD: Geometric Aliasing-Aware Dynamics for High-Resolution Tactile Control". &quot; <i>CoRL 2023</i>.'
---

![TactileVAD](/images/projects/tactile_cartpole_speedup_lowres.gif)

Touch-based control is a promising approach to dexterous manipulation. However, existing tactile control methods often overlook tactile geometric aliasing which can compromise control performance and reliability. This type of aliasing occurs when different contact locations yield similar tactile signatures. To address this, we propose TactileVAD, a generative decoder-only linear latent dynamics formulation compatible with standard control methods that is capable of resolving geometric aliasing. We evaluate TactileVAD on two mechanically-distinct tactile sensors, SoftBubbles (pointcloud data) and Gelslim 3.0 (RGB data), showcasing its effectiveness in handling different sensing modalities. Additionally, we introduce the tactile cartpole, a novel benchmarking setup to evaluate the ability of a control method to respond to disturbances based on tactile input. Evaluations comparing TactileVAD to baselines suggest that our method is better able to achieve goal tactile configurations and hand poses.

Project website: [https://mmintlab.com/tactile-vad](https://www.mmintlab.com/research/tactile-vad)


[Download paper here](https://openreview.net/pdf?id=FefFLN5FvIM)

<!-- Recommended citation: Your Name, You. (2015). "Paper Title Number 3." <i>Journal 1</i>. 1(3). -->