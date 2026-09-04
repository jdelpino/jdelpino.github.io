---
layout: page
permalink: /research/
title: Research
description: Current research directions and recent work.  
nav: true
nav_order: 1
---


## Nonlinear Dynamics and Non-Equilibrium Phases of Matter

<div class="d-flex my-4" style="gap: 0.5rem; overflow: hidden;">
  <picture style="flex: 1 1 0; min-width: 0;">
    <source type="image/webp" srcset="{{ '/assets/img/publication_preview/unstable_limit_cycles_barrier-800.webp' | relative_url }}">
    <img src="{{ '/assets/img/publication_preview/unstable_limit_cycles_barrier.png' | relative_url }}" alt="Flow topology and limit-cycle phases in a nonlinear driven system" style="width: 100%; height: 155px; object-fit: contain; border-radius: 0.35rem;" loading="lazy">
  </picture>
  <picture style="flex: 1 1 0; min-width: 0;">
    <source type="image/webp" srcset="{{ '/assets/img/publication_preview/flow_ms-800.webp' | relative_url }}">
    <img src="{{ '/assets/img/publication_preview/flow_ms.png' | relative_url }}" alt="Topological classification of nonlinear flows" style="width: 100%; height: 155px; object-fit: contain; border-radius: 0.35rem;" loading="lazy">
  </picture>
  <picture style="flex: 1 1 0; min-width: 0;">
    <source type="image/webp" srcset="{{ '/assets/img/publication_preview/limitcycles-800.webp' | relative_url }}">
    <img src="{{ '/assets/img/publication_preview/limitcycles.png' | relative_url }}" alt="Limit cycles found with harmonic balance" style="width: 100%; height: 155px; object-fit: contain; border-radius: 0.35rem;" loading="lazy">
  </picture>
  <picture style="flex: 1 1 0; min-width: 0;">
    <source type="image/webp" srcset="{{ '/assets/img/publication_preview/hourglass-800.webp' | relative_url }}">
    <img src="{{ '/assets/img/publication_preview/hourglass.png' | relative_url }}" alt="Slow and fast dynamical phase transitions" style="width: 100%; height: 155px; object-fit: contain; border-radius: 0.35rem;" loading="lazy">
  </picture>
</div>

---

**_Can we map and predict complex dynamical phases beyond the linear regime?_**

**_What kinds of topology emerge in systems with nonlinearity and strong driving?_**

---

Nonlinear effects arise naturally in mechanical, optical, and electronic systems driven far from equilibrium. Even weak nonlinearities can produce **solitons**, **limit cycles**, **phase transitions**, and **multistability** at large amplitudes.

Understanding this behaviour requires more than energy levels or band structures. We classify **nonequilibrium phases of matter** through the geometry and topology of their dynamical flows: how systems settle into patterns, switch between states, and respond to perturbations.

We develop frequency-domain tools based on **harmonic balance** to find steady and periodic behaviour without simulating many initial conditions. These methods are particularly useful for discovering and analysing **limit cycles**—self-sustained oscillations that break time-translation symmetry.

Applications include **neuromorphic computing**, nanomechanical **frequency combs**, topological solitons, and quantum error correction. More broadly, this work reveals how topology constrains nonlinear dynamics and the transitions between nonequilibrium phases.

This research has been presented and applied in the following works:

- A. S. Gómez and **J. del Pino** – [[Phys. Rev. Research 8, 023319 (2026)]](https://doi.org/10.1103/fblj-fthq)
- G. Villa †, **J. del Pino** †, V. Dumont, G. Rastelli, M. Michałek, A. Eichler, and O. Zilberberg – [[Sci. Adv. 11, eadt9311 (2025)]](https://doi.org/10.1126/sciadv.adt9311)
- M. Fu, O. Ameye, F. Yang, J. Košata, **J. del Pino**, O. Zilberberg, and E. Scheer – [[Phys. Rev. Research 7, 033127 (2025)]](https://doi.org/10.1103/3mtc-j9r9)
- L. Catalini, **J. del Pino**, S. S. Kumar, V. Dumont, G. Margiani, O. Zilberberg, and A. Eichler – [[Phys. Rev. Research 7, 033058 (2025)]](https://doi.org/10.1103/y9gq-yjxy)
- **J. del Pino**, J. Košata, and O. Zilberberg – [[Phys. Rev. Research 6, 033180 (2024)]](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.6.033180)
- P. Álvarez, D. Pittilini, F. Miserocchi, S. Raamamurthy, G. Margiani, O. Ameye, **J. del Pino**, O. Zilberberg, and A. Eichler – [[Phys. Rev. Lett. 132, 207401 (2024)]](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.132.207401)
- V. Borovik, P. Breiding, **J. del Pino**, M. Michałek, and O. Zilberberg – [[J. Math. Pures Appl. 182, 195–222 (2024)]](https://doi.org/10.1016/j.matpur.2023.12.005)
- G. Margiani, **J. del Pino**, T. L. Heugel, N. E. Bousse, S. Guerrero, T. W. Kenny, O. Zilberberg, D. Sabonis, and A. Eichler – [[Phys. Rev. Research 5, L012029 (2023)]](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.5.L012029)
- J. Košata †, **J. del Pino** †, T. L. Heugel, and O. Zilberberg – [[SciPost Phys. Codebases 6 (2022)]](https://scipost.org/codebases.6)


† Equal contribution

### Open-Source Software: HarmonicBalance.jl

<div class="card my-4 shadow-sm">
  <div class="row g-0 align-items-center">
    <div class="col-md-4 p-3 text-center">
      <picture>
        <source type="image/webp" srcset="{{ '/assets/img/publication_preview/HBjl-800.webp' | relative_url }}">
        <img src="{{ '/assets/img/publication_preview/HBjl.png' | relative_url }}" alt="HarmonicBalance.jl phase diagram" style="max-height: 145px; max-width: 100%; object-fit: contain;" loading="lazy">
      </picture>
    </div>
    <div class="col-md-8">
      <div class="card-body">
        <p class="card-text">I co-develop HarmonicBalance.jl with <a href="https://www.linkedin.com/in/orjanameye/">Orjan Ameye</a> and <a href="https://www.linkedin.com/in/jan-košata-58b77777/">Jan Košata</a>. The open-source Julia package finds and analyses steady states, limit cycles, stability, and phase diagrams in nonlinear driven systems.</p>
        <a class="btn btn-sm btn-primary" href="https://github.com/QuantumEngineeredSystems/HarmonicBalance.jl">GitHub</a>
        <a class="btn btn-sm btn-outline-primary" href="https://quantumengineeredsystems.github.io/HarmonicBalance.jl/stable/">Documentation</a>
        <a class="btn btn-sm btn-outline-primary" href="https://doi.org/10.21468/SciPostPhysCodeb.6">Paper</a>
        <a class="btn btn-sm btn-outline-secondary" href="{{ '/repositories/' | relative_url }}">Learn more</a>
      </div>
    </div>
  </div>
</div>


## Artificial Gauge Fields and Nonreciprocal Transport

<div class="d-flex my-4" style="gap: 0.5rem; overflow: hidden;">
  <picture style="flex: 1 1 0; min-width: 0;">
    <source type="image/webp" srcset="{{ '/assets/img/publication_preview/multiplaquette-800.webp' | relative_url }}">
    <img src="{{ '/assets/img/publication_preview/multiplaquette.png' | relative_url }}" alt="Programmable synthetic magnetism in a nano-optomechanical network" style="width: 100%; height: 155px; object-fit: contain; border-radius: 0.35rem;" loading="lazy">
  </picture>
  <picture style="flex: 1 1 0; min-width: 0;">
    <source type="image/webp" srcset="{{ '/assets/img/publication_preview/nanobeam-800.webp' | relative_url }}">
    <img src="{{ '/assets/img/publication_preview/nanobeam.png' | relative_url }}" alt="Bosonic Kitaev chain in a nano-optomechanical network" style="width: 100%; height: 155px; object-fit: contain; border-radius: 0.35rem;" loading="lazy">
  </picture>
  <picture style="flex: 1 1 0; min-width: 0;">
    <source type="image/webp" srcset="{{ '/assets/img/publication_preview/particle_hole-800.webp' | relative_url }}">
    <img src="{{ '/assets/img/publication_preview/particle_hole.png' | relative_url }}" alt="Non-Hermitian chiral phononics" style="width: 100%; height: 155px; object-fit: contain; border-radius: 0.35rem;" loading="lazy">
  </picture>
</div>

---

**_Can we make light or sound behave as if they feel a magnetic field?_**

**_What happens when we break time symmetry to make energy flow in one direction?_**

**_How can gain, loss, and topology work together to control signals in quantum systems?_**

---

**Gauge fields** describe how particles interact and play a central role in condensed-matter physics. In the quantum Hall effect, for example, a magnetic field breaks **time-reversal symmetry** and produces robust, directional **topological edge states**.

In driven resonator systems, we engineer **artificial gauge fields** that break time-reversal symmetry for neutral excitations such as photons and phonons. Carefully designed modulations generate effects analogous to the **Aharonov–Bohm phase** and enable **nonreciprocal transport**, in which energy flows preferentially in one direction.

Combining artificial gauge fields with **parametric interactions**, gain, and loss creates non-Hermitian dynamics with no direct counterpart in conventional materials. This interplay enables unidirectional amplification, control of exceptional points, and new ways to manipulate signals and quantum states.

This physics has been demonstrated and explored in several recent works:
- J. J. Slim, **J. del Pino**, and E. Verhagen – [[Nat. Commun. 16, 7471 (2025)]](https://doi.org/10.1038/s41467-025-62541-z)
- J. J. Slim †, C. Wanjura †, M. Brunelli, **J. del Pino**, E. Verhagen, and A. Nunnenkamp – [[Nature 627, 767–771 (2024)]](https://www.nature.com/articles/s41586-024-07174-w)
- C. Wanjura †, J. J. Slim †, **J. del Pino**, M. Brunelli, E. Verhagen, and A. Nunnenkamp – [[Nat. Phys. 19, 1429–1436 (2023)]](https://www.nature.com/articles/s41567-023-02128-x)
- **J. del Pino** and O. Zilberberg – [[Phys. Rev. Lett. 130, 171901 (2023)]](https://doi.org/10.1103/PhysRevLett.130.171901)
- **J. del Pino** †, J. J. Slim †, and E. Verhagen – [[Nature 606, 82–87 (2022)]](https://www.nature.com/articles/s41586-022-04609-0)
- J. P. Mathew †, **J. del Pino** †, and E. Verhagen – [[Nat. Nanotechnol. 15, 198–202 (2020)]](https://www.nature.com/articles/s41565-019-0630-8)
- R. Duggan †, **J. del Pino** †, E. Verhagen, and A. Alù – [[Phys. Rev. Lett. 123, 023602 (2019)]](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.123.023602)

† Equal contribution


## Quantum Optics with Organic Molecules

<div class="d-flex my-4" style="gap: 0.5rem; overflow: hidden;">
  <picture style="flex: 1 1 0; min-width: 0;">
    <source type="image/webp" srcset="{{ '/assets/img/publication_preview/TRemission-800.webp' | relative_url }}">
    <img src="{{ '/assets/img/publication_preview/TRemission.png' | relative_url }}" alt="Polaritonic molecular clock" style="width: 100%; height: 155px; object-fit: contain; border-radius: 0.35rem;" loading="lazy">
  </picture>
  <picture style="flex: 1 1 0; min-width: 0;">
    <source type="image/webp" srcset="{{ '/assets/img/publication_preview/tensornetwork-800.webp' | relative_url }}">
    <img src="{{ '/assets/img/publication_preview/tensornetwork.png' | relative_url }}" alt="Tensor-network simulation of organic polaritons" style="width: 100%; height: 155px; object-fit: contain; border-radius: 0.35rem;" loading="lazy">
  </picture>
  <picture style="flex: 1 1 0; min-width: 0;">
    <source type="image/webp" srcset="{{ '/assets/img/publication_preview/NJPQT-800.webp' | relative_url }}">
    <img src="{{ '/assets/img/publication_preview/NJPQT.png' | relative_url }}" alt="Collective vibrational strong coupling" style="width: 100%; height: 155px; object-fit: contain; border-radius: 0.35rem;" loading="lazy">
  </picture>
</div>

---

**_How does strong coupling to confined light reshape molecular dynamics?_**

**_Can optical cavities control vibrations, relaxation, and spectroscopy?_**

---

Organic molecules combine electronic excitations with rich vibrational environments. When they couple strongly to a confined optical mode, they form **polaritons**: hybrid light–matter states whose dynamics can differ sharply from those of either component alone.

We develop quantum and tensor-network descriptions of collective strong coupling, non-Markovian dynamics, and molecular vibrations. This work also explores how these effects appear in Raman scattering and ultrafast emission, and how they can enable new optical devices.

Selected works, in reverse chronological order:

- R. E. F. Silva, **J. del Pino**, F. J. García-Vidal, and J. Feist – [[Nat. Commun. 11 (2020)]](https://doi.org/10.1038/s41467-020-15196-x)
- **J. del Pino**, F. A. Y. N. Schröder, A. W. Chin, J. Feist, and F. J. García-Vidal – [[Phys. Rev. Lett. 121, 227401 (2018)]](https://doi.org/10.1103/PhysRevLett.121.227401)
- **J. del Pino**, F. A. Y. N. Schröder, A. W. Chin, J. Feist, and F. J. García-Vidal – [[Phys. Rev. B 98, 165416 (2018)]](https://doi.org/10.1103/PhysRevB.98.165416)
- **J. del Pino**, F. J. García-Vidal, and J. Feist – [[Phys. Rev. Lett. 117, 277401 (2016)]](https://doi.org/10.1103/PhysRevLett.117.277401)
- **J. del Pino**, J. Feist, and F. J. García-Vidal – [[J. Phys. Chem. C 119, 29132–29137 (2015)]](https://doi.org/10.1021/acs.jpcc.5b11654)
- **J. del Pino**, J. Feist, and F. J. García-Vidal – [[New J. Phys. 17, 053040 (2015)]](https://doi.org/10.1088/1367-2630/17/5/053040)
