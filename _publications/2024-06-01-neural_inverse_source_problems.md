---
title: "Neural Inverse Source Problems"
collection: publications
permalink: /publication/2024-06-01-neural_inverse_source_problems
excerpt: 'We propose a Physics-Informed Neural Network (PINN) approach for solving inverse source problems in robotics, jointly identifying unknown source functions and system states from partial, noisy observations. Our method integrates diverse constraints, avoids complex discretizations, accommodates real measurement gradients, and is not limited by training data quality.'
date: 2024-06-01
venue: '8th Conference on Robotic Learning (CoRL)'
image: "/images/projects/nisp.gif"
paperurl: 'https://arxiv.org/abs/2411.01665'
website: 'https://www.mmintlab.com/nisp'
authors: 'Youngsun Wi, Jayjun Lee, <b>Miquel Oller</b>, Nima Fazeli'
citation: "{{ authors }} &quot;{{ title }}&quot;.<i> {{venue}} {{ date | date: '%Y' }}</i>."
---


<img src="{{ page.image }}" alt="{{ page.title }}" style="border-radius: 20px;">

Reconstructing unknown external source functions is an important perception capability for a large range of robotics domains including manipulation, aerial, and underwater robotics. In this work, we propose a Physics-Informed Neural Network (PINN) based approach for solving the inverse source problems in robotics, jointly identifying unknown source functions and the complete state of a system given partial and noisy observations. Our approach demonstrates several advantages over prior works (Finite Element Methods (FEM) and data-driven approaches): it offers flexibility in integrating diverse constraints and boundary conditions; eliminates the need for complex discretizations (e.g., meshing); easily accommodates gradients from real measurements; and does not limit performance based on the diversity and quality of training data. We validate our method across three simulation and real-world scenarios involving up to 4th order partial differential equations (PDEs), constraints such as Signorini and Dirichlet, and various regression losses including Chamfer distance and L2 norm.

Project website: [{{ page.title }}]({{ page.website }})


[Download paper here]({{page.paperurl}})
