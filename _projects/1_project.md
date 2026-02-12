---
layout: page
title: "Physics-Informed Neural Network"
description: "Nonlinear Dynamics Solver using Spectral PINN"
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
selected: true
---

<!-- Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    --- -->

<h3 class="mt-4">Double Pendulum Results</h3>

<div class="row justify-content-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project1/PINNDoublePendulum.png" title="Double Pendulum Main" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Fig 1. Double Pendulum Simulation Environment
</div>

<div class="row mt-3">
    <div class="col-6">
        {% include figure.liquid path="assets/img/project1/double1.0.gif" title="Double GIF 1" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
            (a) $l_1$ = $l_2$ = 1.0m
        </div>
    </div>
    <div class="col-6">
        {% include figure.liquid path="assets/img/project1/double0.25.gif" title="Double GIF 2" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
            (b) $l_1$ = $l_2$ = 0.25m
        </div>
    </div>
</div>

<hr> <h3 class="mt-4">CartPole Results</h3>

<div class="row justify-content-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project1/PINNCartPoleImg.png" title="CartPole Main" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Fig 2. CartPole Simulation Environment. $M$ = $m$ = 1kg, $l$ = 0.25m.
</div>

<div class="row mt-3">
    <div class="col-6">
        {% include figure.liquid path="assets/img/project1/cartpole80.gif" title="CartPole GIF 1" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
            (a) $\theta_0 = 80^\circ$
        </div>
    </div>
    <div class="col-6">
        {% include figure.liquid path="assets/img/project1/cartpole120.gif" title="CartPole GIF 2" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
            (b) $\theta_0 = 120^\circ$
        </div>
    </div>
</div>