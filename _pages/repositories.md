---
layout: page
permalink: /repositories/
title: Repositories
description: I co-developed HarmonicBalance.jl is a Julia package for solving nonlinear differential equations using the method of harmonic balance.
nav: true
nav_order: 3
---


## GitHub Repositories

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}

---

### HarmonicBalance.jl
#### The Harmonic Balance Method
The **Harmonic Balance Method** is a powerful analytical technique for determining the steady-state behavior of nonlinear, periodically driven systems.  **HarmonicBalance.jl** is a Julia package that implements this method efficiently and flexibly. By approximating the system’s response as a sum of harmonic components with slowly varying amplitudes, this method transforms the original nonlinear, non-autonomous system into an autonomous set of differential equations. This transformation is achieved through a generalized Van der Pol transformation, which remaps the **time-dependent system** into a rotating reference frame where the equations become **time-invariant**. 

#### Solving via Homotopy Continuation
To solve these autonomous equations and identify all possible steady-state solutions reliably, we employ the method of **Homotopy Continuation**. This numerical approach systematically deforms a simple system, for which solutions are known, into the complex target system, tracking solutions throughout the deformation process. This ensures that **all steady states** are found in a guaranteed manner, providing a comprehensive understanding of the system’s behavior.

#### Key features

- Simple interface to scan **phase diagrams** across multiple parameters.
- Built-in tools for detecting and analyzing **Limit Cycles**.
- Ongoing integration with **Quantum Algebra packages** for quantum systems in the mean field limit.
- Actively maintained with frequent feature updates.

<p align="center">
  <img src="https://raw.githubusercontent.com/QuantumEngineeredSystems/HarmonicBalance.jl/refs/heads/master/logo.png" alt="HarmonicBalance.jl Logo" style="width:80%;">
</p>

> The package is open-source and open to contributions.