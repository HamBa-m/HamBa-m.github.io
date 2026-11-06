---
layout: single
title: "Research & Publications"
permalink: /research/
author_profile: false
toc: true
toc_sticky: true
toc_label: "On This Page"
---

My doctoral research investigates **Adversarial Robustness in Cooperative Multi-Agent Learning**, focusing on the relationship between individual vulnerability and collective performance in teams whose decisions are learned through interaction.

---

## Doctoral Research: Adversarial Robustness in Cooperative MARL

Cooperative multi-agent reinforcement learning (MARL) enables teams of autonomous agents to coordinate in shared environments where their actions directly affect one another. While behavioral diversity can support specialization, it also introduces asymmetric vulnerabilities: observations can be deliberately manipulated to mislead a trained policy. In a cooperative setting, the consequences need not remain confined to the agent receiving corrupted inputs—peer reactions can either contain the disruption or amplify its damage.

My research connects effects on the directly targeted agent, the responses of its peers, and the resulting team performance over time.

### Guiding Research Questions

* **Individual and Collective Effects:** How do localized observation perturbations affect the targeted agent versus the collective task, and how can these multi-level effects be meaningfully characterized beyond aggregate reward metrics?
* **Team Organization (Heterogeneity & Communication):** How do behavioral heterogeneity (differences in agents' learned behaviors) and inter-agent communication influence whether local disruptions are amplified, contained, or compensated?
* **Adaptive Protection:** How can the vulnerabilities identified through analytical and empirical study guide execution-time defenses that preserve pretrained policy parameters?

### Current Activities & Progress

* **Analytical Formulation:** Developing a theoretical framework that formally distinguishes the effect on a directly targeted agent, the responses of its peers, and the resulting team performance. The objective is to connect localized disturbances to collective outcomes and clarify the mathematical assumptions governing these relationships.
* **Experimental Investigation:** Implementing a simulation-based experimental framework studying adversarial robustness in cooperative MARL tasks. The platform compares varying degrees of policy heterogeneity and communication structures under adversarial perturbations.
* **Connecting Analysis and Evidence:** Evaluating whether analytical metrics faithfully describe interacting agent behaviors, establishing criteria to distinguish damaging peer responses from useful recovery, and assessing the role of diversity across tasks without assuming that heterogeneity unconditionally improves robustness.
* **Prospective Empirical Direction:** Exploring execution-time protection inspired by collective biological systems (such as artificial immune systems and differentiated fault detection), with **multi-robot teams** as a primary prospective testbed.

---

## Manuscripts Under Review

<div class="research-entry">
  <h4>A Survey on Adversarial Multi-Agent Deep Reinforcement Learning</h4>
  <div class="authors"><strong>Hamza Ba-mohammed</strong>, Latifa El Bouga, Amine Andam, Mostapha Essoullami, Douae Benhlima, Jamal Bentahar, Mustapha Hedabou</div>
  <div class="venue"><i class="fas fa-file-alt"></i> Under Major Revision — ACM Computing Surveys (ACM CSUR)</div>
  <div class="abstract">
    <p>This survey provides a comprehensive, taxonomy-driven synthesis of adversarial multi-agent deep reinforcement learning (adversarial MARL), establishing formal connections between multi-agent decision models (Markov games, POSGs, Dec-POMDPs) and game-theoretic solution concepts including min-max reasoning, Stackelberg formulations, and robust equilibria under observational and transition uncertainty.</p>
    
    <p><strong>Scope &amp; Conceptual Framework:</strong></p>
    <ul>
      <li><strong>Multi-Dimensional Attack Taxonomy:</strong> Formulates and compares adversarial strategies across attack timing (training-time poisoning vs. execution-time evasion), threat-model access privileges (white-box, gray-box, black-box), victim selection and cardinality, and bounded perturbation spaces.</li>
      <li><strong>Threat Model Realism:</strong> Analyzes practical access assumptions in multi-agent systems, critically examining under-explored attack surfaces including inter-agent communication channels and restricted-information settings.</li>
      <li><strong>Algorithmic &amp; Benchmark Analysis:</strong> Investigates vulnerability profiles across leading multi-agent architectures (comparing on-policy methods and value-factorization approaches) under standard multi-agent benchmarks.</li>
      <li><strong>Functional Defense Categorization:</strong> Structures defense literature around robustness evaluation versus robustness enhancement, synthesizing trade-offs among adversarial training, game-theoretic formulations, regularized objectives, and execution-time certified protections.</li>
    </ul>
  </div>
</div>

---

## Peer-Reviewed Conference Proceedings

<div class="research-entry">
  <h4>Assessing the Evolution of Meteorological Seasons and Climate Changes Using Hierarchical Clustering</h4>
  <div class="authors">Lazaar, M., <strong>Ba-mohammed, H.</strong>, Filali, H., Alami, Y.E.M.E.</div>
  <div class="venue"><i class="fas fa-book"></i> Published in: Proceedings of the International Conference on Artificial Intelligence &amp; Smart Environment (ICAISE 2024), Springer</div>
  <div class="abstract">
    Investigates unsupervised machine learning techniques—specifically hierarchical agglomerative clustering—for analyzing multi-decadal meteorological time-series data. Focusing on temperature and precipitation records from a semi-arid station as an empirical case study, the work demonstrates how hierarchical clustering identifies shifts in transitions between meteorological seasons over time, providing data-driven evidence for localized climate trend shifts.
  </div>
  <div style="margin-top: 0.8em;">
    <a href="https://link.springer.com/chapter/10.1007/978-3-031-48573-2_17" class="btn btn--inverse btn--small" target="_blank"><i class="fas fa-external-link-alt"></i> Springer Chapter</a>
  </div>
</div>

---

## Prior Research Projects & Capstones

<div class="research-entry">
  <h4>Multi-Agent Deep RL for Agile Earth Observation Satellite Constellations</h4>
  <div class="authors"><strong>Hamza Ba-mohammed</strong> (Engineering Capstone, Ai Movement UM6P)</div>
  <div class="venue"><i class="fas fa-satellite"></i> AI Movement UM6P Research Center (2024)</div>
  <div class="abstract">
    Formulated collaborative target acquisition and coverage optimization in Agile Earth Observation Satellites (AEOS) as a Decentralized Markov Decision Process (Dec-MDP / Dec-POMDP). Extended the PyLEO simulation platform, benchmarked single-agent and multi-agent algorithms (DQN, DDPG, and MADDPG), and explored multi-agent coordination under communication-constrained orbital dynamics.
  </div>
</div>

<div class="research-entry">
  <h4>Paralleled K-Nearest Neighbors Algorithm on the PRAM Model</h4>
  <div class="authors">El Atyqy, O., Filali, H., <strong>Ba-mohammed, H.</strong></div>
  <div class="venue"><i class="fas fa-file-code"></i> Technical Report (2023)</div>
  <div class="abstract">
    Designed and analyzed a parallelized variant of the K-Nearest Neighbors (KNN) algorithm using the Parallel Random-Access Machine (PRAM) theoretical model. Benchmarked speedup and memory efficiency against sequential baselines for high-performance computing contexts.
  </div>
  <div style="margin-top: 0.8em;">
    <a href="https://www.researchgate.net/publication/368586243_Paralleled_K-Nearest_Neighbors_Algorithm" class="btn btn--inverse btn--small" target="_blank"><i class="fas fa-external-link-alt"></i> ResearchGate</a>
  </div>
</div>

<div class="research-entry">
  <h4>Content-Based Image Retrieval (CBIR) Metric Evaluation</h4>
  <div class="authors"><strong>Ba-mohammed, H.</strong>, Filali, H., Sahri, B.</div>
  <div class="venue"><i class="fas fa-file-code"></i> Technical Report (2023)</div>
  <div class="abstract">
    Engineered a content-based image retrieval system based on color, texture, and shape features. Benchmarked Cosine, Euclidean, Chebyshev, and Manhattan distance metrics on the Corel dataset to determine retrieval precision across feature spaces.
  </div>
  <div style="margin-top: 0.8em;">
    <a href="https://www.researchgate.net/publication/367452891_Design_Development_and_Evaluation_of_a_Content_Based_Image_Retrieval_system_CBIR_based_on_color_texture_and_shape" class="btn btn--inverse btn--small" target="_blank"><i class="fas fa-external-link-alt"></i> ResearchGate</a>
  </div>
</div>

<div class="research-entry">
  <h4>Two-Stage Rocket Propulsion Optimization via SciPy</h4>
  <div class="authors"><strong>Ba-mohammed, H.</strong></div>
  <div class="venue"><i class="fas fa-rocket"></i> Research Initiation Paper (2022)</div>
  <div class="abstract">
    Analytical formulation based on the Tsiolkovsky rocket equation to optimize the propellant-to-payload mass ratio across two-stage launch vehicles. Utilized scalar bounded minimization in SciPy to determine optimal stage-mass distributions given target &Delta;V budgets.
  </div>
  <div style="margin-top: 0.8em;">
    <a href="https://www.researchgate.net/publication/358730494_Advanced_Rocket_Propulsion_Two_Stages_System_Optimization_with_SciPy" class="btn btn--inverse btn--small" target="_blank"><i class="fas fa-external-link-alt"></i> ResearchGate</a>
  </div>
</div>

---

## Open-Source Research Software

* **[scinis-learn](https://github.com/HamBa-m/scinis-learn):** A modular machine learning library built from scratch in Python 3.8. Implements perceptrons, logistic and polynomial regressors, multiclass schemes, and theoretical tools including VC-dimension estimation, covering numbers, and gradient optimization routines.
* **[adaptive-boids](https://github.com/HamBa-m/adaptive-boids):** 2D flocking dynamics simulation framework implementing Reynolds boids rules with telemetry metrics for collective polarization, angular variance, and kinetic energy.
* **[hambam-unconstraint-optimization](https://github.com/HamBa-m/hambam-unconstraint-optimization):** Mathematical optimization package featuring multivariable descent algorithms (Gradient Descent, Conjugate Gradient, Newton-Raphson) and 1D line search methods (Golden Section, Fibonacci).
* **[crypto-sss](https://github.com/HamBa-m/crypto-sss):** Simulation and formal verification of Shamir's Secret Sharing (SSS) threshold cryptography, with brute-force resistance analysis.
