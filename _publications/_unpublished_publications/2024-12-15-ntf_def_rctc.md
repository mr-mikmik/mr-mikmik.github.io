---
title: "Estimating Deformable-Rigid Contact Interactions for a Deformable Tool via Learning and Model-Based Optimization"
collection: publications
permalink: /publication/2024-12-15-ntf_def_rctc
excerpt: 'We present a hybrid learning and first-principles approach to model deformable tools dexterously manipulating rigid objects, capturing simultaneous motion, force transfer, contacts, and both intrinsic and extrinsic dynamics.'
date: 2024-12-15
venue: 'Under Review'
image: "/images/projects/ntf_def_rig_ctc.gif"
paperurl: 'https://arxiv.org/abs/2409.13923' # TODO: Update
website: 'https://www.mmintlab.com/research/tactile-neural-derendering/' # TODO: Update
authors: 'Mark Van der Merwe, <b>Miquel Oller</b>, Dmitry Berenson, Nima Fazeli'
citation: "{{ authors }} &quot;{{ title }}&quot;.<i> {{venue}} {{ date | date: '%Y' }}</i>."
videoid: 'UV5dBaxj3Wc'
---


<img src="{{ page.image }}" alt="{{ page.title }}" style="border-radius: 20px;">

Dexterous manipulation requires careful reasoning over extrinsic contacts. The prevalence of deforming tools in human environments, the use of deformable sensors, and the increasing number of soft robots yields a need for approaches that enable dexterous manipulation through contact reasoning where not all contacts are well characterized by classical rigid body contact models. Here, we consider the case of a deforming tool dexterously manipulating a rigid object. We propose a hybrid learning and first-principles approach to the modeling of simultaneous motion and force transfer of tools and objects. The learned module is responsible for jointly estimating the rigid object’s motion and the deformable tool’s imparted contact forces. We then propose a Contact Quadratic Program to recover forces between the environment and object subject to quasi-static equilibrium and Coulomb friction. The results is a system capable of modeling both intrinsic and extrinsic motions, contacts, and forces during dexterous deformable manipulation. We train our method in simulation and show that our method outperforms baselines under varying block geometries and physical properties, during pushing and pivoting manipulations, and demonstrate transfer to real world interactions.

<!-- VIDEO -->
<!-- {% if page.videourl %}
    {% include video.html videourl=page.videourl %}
{% endif %}
{% if page.videoid %}
    {% include youtube.html videoid=page.videoid %}
{% endif %} -->

Project website: [{{ page.title }}]({{ page.website }})


[Download paper here]({{page.paperurl}})
