---
title: "Tactile Neural De-rendering"
collection: publications
permalink: /publication/2024-08-30-tactile-neural-derendering
excerpt: 'We introduce Tactile Neural De-rendering, a novel approach that leverages a generative model to reconstruct a local 3D representation of an object based solely on its tactile signature.'
date: 2024-08-30
venue: 'Under Review'
image: "/images/projects/tactile_neural_derendering.png"
paperurl: 'https://arxiv.org/abs/2409.13923'
website: 'https://www.mmintlab.com/research/tactile-neural-derendering/'
authors: 'J.A. Eyzaguirre, <b>Miquel Oller</b>, Nima Fazeli'
citation: "{{ authors }} &quot;{{ title }}&quot;.<i> {{venue}} {{ date | date: '%Y' }}</i>."
videoid: 'UV5dBaxj3Wc'
---


<img src="{{ page.image }}" alt="{{ page.title }}" style="border-radius: 20px;">

Tactile sensing has proven to be an invaluable tool for enhancing robotic perception, particularly in scenarios where visual data is limited or unavailable. However, traditional methods for pose estimation using tactile data often rely on intricate modeling of sensor mechanics or estimation of contact patches, which can be cumbersome and inherently deterministic. In this work, we introduce Tactile Neural De-rendering, a novel approach that leverages a generative model to reconstruct a local 3D representation of an object based solely on its tactile signature. By rendering the object as though perceived by a virtual camera embedded at the fingertip, our method provides a more intuitive and flexible representation of the tactile data. This 3D reconstruction not only facilitates precise pose estimation but also allows for the quantification of uncertainty, providing a robust framework for tactile-based perception in robotics.

<!-- VIDEO -->
{% if page.videourl %}
    {% include video.html videourl=page.videourl %}
{% endif %}
{% if page.videoid %}
    {% include youtube.html videoid=page.videoid %}
{% endif %}

Project website: [{{ page.title }}]({{ page.website }})


[Download paper here]({{page.paperurl}})
