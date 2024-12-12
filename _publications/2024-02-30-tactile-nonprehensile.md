---
title: "Tactile-Driven Non-Prehensile Object Manipulation via Extrinsic Contact Mode Control"
collection: publications
permalink: /publication/2024-02-30-tactile-nonprehensile
excerpt: 'We consider the problem of non-prehensile manipulation with highly compliant and high-resolution tactile sensors. Our approach considers contact mechanics and sensor dynamics to achive desired object poses and transmitted forces and is amenable for gradient-based optimization.'
date: 2024-02-30
venue: 'Robotic Science and Systems (RSS)'
image: "/images/projects/extrinsic_pivoting_cropped.gif"
paperurl: 'https://arxiv.org/abs/2405.18214'
website: 'https://www.mmintlab.com/research/tactile-nonprehensile'
authors: '<b>Miquel Oller</b>, Dmitry Berenson, Nima Fazeli'
citation: '<b>Oller, M. </b>, Berenson, D., & Fazeli, N., "Tactile-Driven Non-Prehensile Object Manipulation via Extrinsic Contact Mode Control", <i>RSS 2024</i>.'
videoid: '-vlK6Ou2S_c'
---


<img src="{{ page.image }}" alt="{{ page.title }}" style="border-radius: 20px;">


We consider the problem of non-prehensile manipulation using grasped objects. This problem is a superset of many common manipulation skills including instances of tool-use (e.g., grasped spatula flipping a burger) and assembly (e.g., screwdriver tightening a screw). Here, we present an algorithmic approach for non-prehensile manipulation leveraging a gripper with highly compliant and high-resolution tactile sensors. Our approach solves for robot actions that drive object poses and forces to desired values while obeying the complex dynamics induced by the sensors as well as the constraints imposed by static equilibrium, object kinematics, and frictional contact. Our method is able to produce a variety of manipulation skills and is amenable to gradient-based optimization by exploiting differentiability within contact modes (e.g., specifications of sticking or sliding contacts). We evaluate 4 variants of controllers that attempt to realize these plans and demonstrate a number of complex skills including non-prehensile planar sliding and pivoting on a variety of object geometries. The perception and control capabilities that drive these skills are the building blocks toward dexterous and reactive autonomy in unstructured environments.


<!-- VIDEO -->
{% if page.videourl %}
    {% include video.html videourl=page.videourl %}
{% endif %}
{% if page.videoid %}
    {% include youtube.html videoid=page.videoid %}
{% endif %}

Project website: [{{ page.title }}]({{ page.website }})


[Download paper here]({{page.paperurl}})
