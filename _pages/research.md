---
layout: single
title: "Research & Publications"
description: "Doctoral research agenda in cooperative Multi-Agent Reinforcement Learning, survey manuscripts, and prior research work by Hamza Ba-mohammed."
permalink: /research/
redirect_from:
  - /academia/publications/
  - /academia/publications.html
author_profile: false
classes: full-width
toc: true
toc_sticky: true
toc_label: "On This Page"
---

My doctoral research investigates **Adversarial Robustness in Cooperative Multi-Agent Learning**, focusing on the relationship between individual vulnerability and collective performance in teams whose decisions are learned through interaction.

---

## Doctoral Research (PhD Track)

Cooperative multi-agent reinforcement learning (MARL) enables teams of autonomous agents to coordinate in shared environments where their actions directly affect one another. While behavioral diversity can support specialization, it also introduces asymmetric vulnerabilities: observations can be deliberately manipulated to mislead a trained policy. In a cooperative setting, the consequences need not remain confined to the agent receiving corrupted inputs—peer reactions can either contain the disruption or amplify its damage.

My research connects effects on the directly targeted agent, the responses of its peers, and the resulting team performance over time.

### Guiding Research Questions

* **Individual and Collective Effects:** How do localized observation perturbations affect the targeted agent versus the collective task, and how can these multi-level effects be meaningfully characterized beyond aggregate reward metrics?
* **Team Organization (Heterogeneity & Communication):** How do behavioral heterogeneity (differences in agents' learned behaviors) and inter-agent communication influence whether local disruptions are amplified, contained, or compensated?
* **Adaptive Protection:** How can the vulnerabilities identified through analytical and empirical study guide execution-time defenses that preserve pretrained policy parameters?

### Doctoral Publications

<div class="research-entry">
  <h4>A Survey on Adversarial Multi-Agent Deep Reinforcement Learning</h4>
  <div class="authors"><strong>Hamza Ba-mohammed</strong>, Latifa El Bouga, Amine Andam, Mostapha Essoullami, Douae Benhlima, Jamal Bentahar, Mustapha Hedabou</div>
  <div class="venue"><i class="fas fa-file-alt"></i> Under Major Revision — ACM Computing Surveys (ACM CSUR)</div>
  <div class="abstract">
    <p>A comprehensive, taxonomy-driven synthesis of adversarial multi-agent deep reinforcement learning (adversarial MARL). The survey maps formal decision models (Markov games, POSGs, Dec-POMDPs) to game-theoretic solution concepts, critically examining observational and transition uncertainties.</p>
    
    <p><strong>Key Contributions:</strong></p>
    <ul>
      <li><strong>Multi-Dimensional Attack Taxonomy:</strong> Classifies adversarial strategies across perturbation timing (poisoning vs. evasion), threat-model access (white-box, gray-box, black-box), victim cardinality, and communication attack surfaces.</li>
      <li><strong>Functional Defense Categorization:</strong> Structures defenses into robustness evaluation vs. enhancement (adversarial training, regularized objectives, certified bounds, and execution-time shields).</li>
      <li><strong>Critical Synthesis of Published Benchmarks:</strong> Reviews empirical methodologies, threat realism, and evaluation gaps across standard multi-agent benchmark environments.</li>
    </ul>
    <div style="margin-top: 1em; display: flex; gap: 8px; flex-wrap: wrap;">
      <a href="https://drive.google.com/file/d/1qRYIgG5URSCmis2cHR3FswqYwdiuUNZD/view?usp=drive_link" class="btn btn--primary btn--small" target="_blank"><i class="fas fa-file-pdf"></i> Doctoral Days Poster (PDF)</a>
      <a href="https://github.com/HamBa-m/sci-scraper" class="btn btn--inverse btn--small" target="_blank"><i class="fab fa-github"></i> Companion Pipeline: sci-scraper</a>
      <a href="/assets/images/gallery/doctoral_days_2025.jpeg" class="btn btn--light-outline btn--small" target="_blank"><i class="fas fa-camera"></i> Presentation Photo</a>
    </div>
  </div>
</div>

---

## Prior Research Work

Research conducted during master's / engineering track and preparatory studies (ENSIAS / AI Movement UM6P):

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

<div class="research-entry">
  <h4>Multi-Agent Deep RL for Agile Earth Observation Satellite Constellations</h4>
  <div class="authors"><strong>Hamza Ba-mohammed</strong> (Engineering Capstone, Ai Movement UM6P)</div>
  <div class="venue"><i class="fas fa-satellite"></i> AI Movement UM6P Research Center (2024)</div>
  <div class="abstract">
    Formulated collaborative target acquisition and coverage optimization in Agile Earth Observation Satellites (AEOS) as a Decentralized Partially Observable Markov Decision Process (Dec-POMDP). Extended the PyLEO simulation platform, benchmarked single-agent RL baselines (independent DQN, DDPG) alongside multi-agent coordination methods (MADDPG), and explored cooperative scheduling under communication-constrained orbital dynamics.
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

<div class="research-entry">
  <h4>Open-Source Algorithmic &amp; Scientific Software</h4>
  <div class="authors"><strong>Hamza Ba-mohammed</strong> (Engineering &amp; Foundation Codebases)</div>
  <div class="venue"><i class="fab fa-github"></i> Open-Source Repositories</div>
  <div class="abstract">
    Modular algorithmic toolkits and simulation frameworks developed during engineering studies, spanning collective multi-agent flocking, first-principles machine learning, multivariable descent optimization, and cryptography.
  </div>
  <div style="margin-top: 0.8em; display: flex; gap: 8px; flex-wrap: wrap;">
    <a href="https://github.com/HamBa-m/adaptive-boids" class="btn btn--inverse btn--small" target="_blank"><i class="fab fa-github"></i> adaptive-boids</a>
    <a href="https://github.com/HamBa-m/scinis-learn" class="btn btn--inverse btn--small" target="_blank"><i class="fab fa-github"></i> scinis-learn</a>
    <a href="https://github.com/HamBa-m/hambam-unconstraint-optimization" class="btn btn--inverse btn--small" target="_blank"><i class="fab fa-github"></i> unconstrained-optimization</a>
    <a href="https://github.com/HamBa-m/crypto-sss" class="btn btn--inverse btn--small" target="_blank"><i class="fab fa-github"></i> crypto-sss</a>
  </div>
</div>
