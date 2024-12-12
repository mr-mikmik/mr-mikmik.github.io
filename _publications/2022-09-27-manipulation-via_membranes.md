---
title: "Manipulation via Membranes: High-Resolution and Highly Deformable Tactile Sensing and Control"
collection: publications
permalink: /publication/2022-09-27-manipulation-via_membranes
excerpt: 'Our method learns soft tactile sensor membrane deformation dynamics to control a grasped object’s pose and force transmitted to the environment during contact-rich manipulation tasks such as drawing and in-hand pivoting.'
date: 2022-09-27
venue: '6th Conference on Robotic Learning (CoRL)'
paperurl: 'https://arxiv.org/pdf/2209.13432.pdf'
website: 'https://www.mmintlab.com/research/manipulation-via-membranes/'
authors: '<b>Miquel Oller</b>, Mireia Planas, Dmitry Berenson, Nima Fazeli'
citation: '<b>Oller, M. </b>, i Lisbona, M. P., Berenson, D., & Fazeli, N. &quot; "Manipulation via Membranes: High-Resolution and Highly Deformable Tactile Sensing and Control". &quot; <i>CoRL 2022 </i>.'
image: "/images/projects/bubble_pivoting_optimized-2.gif"
videoid: '0dVwitZW66E'
---


<img src="{{ page.image }}" alt="{{ page.title }}" style="border-radius: 20px;">


Collocated tactile sensing is a fundamental enabling technology for dexterous manipulation. However, deformable sensors introduce complex dynamics between the robot, grasped object, and environment that must be considered for fine manipulation. Here, we propose a method to learn soft tactile sensor membrane dynamics that accounts for sensor deformations caused by the physical interaction between the grasped object and environment. Our method combines the perceived 3D geometry of the membrane with proprioceptive reaction wrenches to predict future deformations conditioned on robot action. Grasped object poses are recovered from membrane geometry and reaction wrenches, decoupling interaction dynamics from the tactile observation model. We benchmark our approach on two real-world contact-rich tasks: drawing with a grasped marker and in-hand pivoting. Our results suggest that explicitly modeling membrane dynamics achieves better task performance and generalization to unseen objects than baselines.

<!-- VIDEO -->
{% if page.videourl %}
    {% include video.html videourl=page.videourl %}
{% endif %}
{% if page.videoid %}
    {% include youtube.html videoid=page.videoid %}
{% endif %}


Project website: [{{ page.title }}]({{ page.website }})


[Download paper here]({{page.paperurl}})
