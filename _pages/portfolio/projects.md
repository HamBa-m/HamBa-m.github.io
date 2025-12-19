---
layout: single
title: "Projects"
permalink: /portfolio/projects/
author_profile: false
toc: true
toc_sticky: true
toc_label: "Jump to"
---
This page showcases a selection of my key projects across various domains, highlighting my skills in AI, data science, software engineering, and research.

## Industry & Commercial Solutions
*Projects that solve real-world business problems and have market potential.*

<div class="notice--primary" markdown="1">

### Aabar
A centralized web application designed to monitor and manage underground water resources by simplifying well drilling licensing, ensuring regulatory compliance, and predicting water availability through advanced data analytics. It combats illegal drilling and promotes sustainable water management, targeting government agencies, agricultural businesses, environmental organizations, and research institutions focused on water conservation.

The app predicts water depth using a hybrid method combining radius-based regression (KNN) with graph-based aggregation (GNN), where wells within a 5 km radius influence predictions weighted by spatial proximity. For locations lacking nearby wells, a Random Forest Regressor uses soil and weather data from Google Earth Engine to make accurate predictions. Additionally, Aabar employs an open-source multilingual LLaMa language model for query handling and uses Retrieval-Augmented Generation (RAG) to provide precise information based on water law number 36-15.

**Collaborators:** Abdelmonaim Bounite
**Tags:** Water, Hydrology, Prediction, AI, Random Forest, GNN, KNN, RAG, LLM

<a href="https://github.com/MPUWM/aabar" class="btn btn--inverse">View GitHub Repository</a>
<!-- <a href="#" class="btn btn--light-outline">Read Detailed Article</a> -->

</div>

<div class="notice--primary" markdown="1">

### SparkBuild
An innovative platform that leverages artificial intelligence (AI), more precisely graph convolutional networks (GCN) in combination with genetic algorithms, to predict and optimize the energy consumption of buildings. It provides accurate predictions and recommendations for optimal building layout, aiming to reduce overall energy consumption in the construction sector.

The platform uses deep learning to analyze the geometric data of buildings, their positions, weather data, and space usage, enabling the prediction and optimization of energy consumption. Technologies used include ReactJS, Flask, MongoDB, PyTorch, Scikit-learn, pandas, PyTorch Geometric, and NumPy.

**Collaborators:** Ahmed Idrissi, Rihab Id'mhand, Noura Ed-dahby, Aya Kourdou
**Tags:** Energy, Construction, Optimization, Prediction, AI, Deep Learning, GCN, Genetic Algorithm

<a href="https://github.com/sparkbuild" class="btn btn--inverse">View GitHub Repository</a>
<!-- <a href="#" class="btn btn--light-outline">Read Detailed Article</a> -->

</div>

<div class="notice--primary" markdown="1">

### Pharma Wizard
An AI-based solution that handles the problem of supply chain shortages in pharmaceutical products, as one of the current and sensitive problems in Morocco.

Developed using an LSTM network and trained to forecast the future demand in medicaments in around 500 cities, with an R² score up to 0.99 after data normalization. Furthermore, it was deployed into a web application to provide a user-friendly UI for stock managers to monitor the state of the market and plan for future deliveries. A business plan was also elaborated for an eventual launching of this start-up idea.

**Collaborators:** Adil Lakhdar Chaoui, Mouad Berqia
**Tags:** Supply Chain, Healthcare, Planning, Forecasting, AI, Deep Learning, LSTM

<a href="https://github.com/HamBa-m/SmartPharma" class="btn btn--inverse">View GitHub Repository</a>
<!-- <a href="#" class="btn btn--light-outline">Read Detailed Article</a> -->

</div>

<div class="notice--primary" markdown="1">

### e-Tayoga
An innovative agricultural platform that leverages real-time NASA Earth observation data through the Google Earth Engine API to provide farmers with critical insights on land conditions such as temperature, water availability, and soil moisture. Its interactive dashboard helps farmers monitor crop health, plan irrigation, and track weather patterns, enabling more efficient and sustainable resource management.

The platform also had other pending non-developed features, like a multilingual virtual assistant (BOUCHTA) designed to support farmers with recommendations and predictions via voice and text inputs, a gamified forum where farmers share knowledge, and an alert system that sends timely notifications about water shortages, crop diseases, and extreme weather.

**Collaborators:** Ahmed Idrissi, Noura Ed-dahby, Nouhaila Atabet, Maroua Chattat
**Tags:** Agriculture, Planning, Forecasting, AI, Machine Learning, Data Engineering, Data Science, LLM & RAG

<a href="https://github.com/e-tayoga/e-Tayoga" class="btn btn--inverse">View GitHub Repository</a>
<!-- <a href="#" class="btn btn--light-outline">Read Detailed Article</a> -->

</div>

<div class="notice--primary" markdown="1">

### A Smart Micro-Grid with RL
A project about making scholar institutions capable of achieving energetic independence with autonomous and scalable microgrids on production, consumption, and distribution levels using reinforcement learning (RL).

Inspired by the actual state-of-the-art in smart grids, based on much research about renewable energies and university campuses, and optimized with a creative RL reward function, which helps reduce the usage of urban electricity and increase the usage of green energies in a hybrid smart grid with green and fossil sources. During simulations, our system was able to achieve up to 20% optimization regarding our objective, in comparison to a baseline algorithm that uses a conditional block of code (if/else) with the same purpose.

**Collaborators:** Hicham Filali, Bouchra Sahri, Hajar El Idrissi, Omar El Taqi
**Tags:** Energy, Micro-grid, Planning, AI, Reinforcement Learning, Data Science, R&D

<!-- <a href="#" class="btn btn--inverse">View GitHub Repository</a> -->
<a href="https://www.linkedin.com/feed/update/urn:li:activity:7067921094808088577/" class="btn btn--light-outline">Read Detailed Article</a>

</div>

<div class="notice--primary" markdown="1">

### Multi-Owner Bank Account Authentication System
This project studies Shamir's Secret Sharing (SSS), a cryptographic method that splits a secret into parts requiring a minimum number to reconstruct it. It explores SSS's math and security proofs and uses Python to simulate encryption, decryption, and brute-force attacks to test its strength.

The goal is to design a banking authentication system for multi-owner accounts using SSS, ensuring that access requires multiple owners' approval. This enhances security by preventing single-user access and demonstrates practical applications of cryptography in finance.

**Tags:** Banking, Cybersecurity, Cryptography, Brute Force Attack, Formal Methods

<a href="https://github.com/HamBa-m/crypto-sss" class="btn btn--inverse">View GitHub Repository</a>
<!-- <a href="#" class="btn btn--light-outline">Read Detailed Article</a> -->

</div>

## Scientific & Educational Projects
*Projects developed for educational, research, or scientific exploration purposes, including simulations, academic studies, and software packages.*

<div class="notice--info" markdown="1">

### ExoWeb.AI
A distributed framework for exoplanet survey equipped with machine learning models that could train themselves autonomously using the data they classify based on the innovative self-supervised learning paradigm, and for which we proved the efficiency in our case study. This project was also presented as a talk at the 4th Annual Meeting of the African Astronomical Society (AfAS) in Marrakech, Morocco.

**Collaborators:** Rihab Boudkour, Meryem El Karati
**Tags:** Astronomy, Astrophysics, Exoplanetary, Data Science, Machine Learning, Distributed Systems

<a href="https://github.com/exowebai/stable" class="btn btn--inverse">View GitHub Repository</a>
<!-- <a href="#" class="btn btn--light-outline">Read Detailed Article</a> -->

</div>

<div class="notice--info" markdown="1">

### scinis-learn: a Machine Learning Python Library
Inspired by scikit-learn, this package implements several fundamental machine learning algorithms from scratch in Python 3.8, including Single Layer Perceptron, Pocket Perceptron, Adaline, Linear and Logistic Regression, Polynomial Regression, and multi-class classifiers like One-vs-All and One-vs-One. It also includes key learning theory tools such as non-linear transformation, K-fold cross validation, gradient descent, regularization, and theoretical concepts like VC dimension and covering numbers.

**Collaborators:** Hicham Filali, Mohammed Nechba, Bouchra Sahri, Mohamed Mouhajir, Hanaa El Afia
**Tags:** Machine Learning, Learning Theory, Mathematics, Optimization, Data Generation, Data Visualization

<a href="https://github.com/HamBa-m/scinis-learn" class="btn btn--inverse">View GitHub Repository</a>
<!-- <a href="#" class="btn btn--light-outline">Read Detailed Article</a> -->

</div>

<div class="notice--info" markdown="1">

### A Content Based Image Retrieval system (CBIR)
A computer vision technique that allows images to be retrieved from a database based on the similarity of their actual visual content, rather than relying on metadata or keywords. This process involves extracting distinctive features—such as color, texture, and shape—from each image and representing them numerically. The system then compares these features using similarity measures to identify and return images from the database that most closely match the query image.

**Collaborators:** Hicham Filali, Bouchra Sahri
**Tags:** Computer Vision, Mathematics, Software Development, Database Search, CBIR

<a href="https://github.com/HamBa-m/cbir" class="btn btn--inverse">View GitHub Repository</a>
<!-- <a href="#" class="btn btn--light-outline">Read Detailed Article</a> -->

</div>

<div class="notice--info" markdown="1">

### A Python Package for Unconstrained Optimization
This GitHub repository provides a Python package for unconstrained optimization. It includes implementations of multivariable algorithms like Gradient Descent, Conjugate Gradient, and Newton methods, as well as ten one-dimensional search methods such as Golden Section and Fibonacci. The package also features visualization tools and relies on libraries like NumPy, SciPy, and Matplotlib.

**Tags:** Mathematics, Optimization, Linear Algebra, Visualization

<a href="https://github.com/HamBa-m/hambam-unconstraint-optimization" class="btn btn--inverse">View GitHub Repository</a>
<!-- <a href="#" class="btn btn--light-outline">Read Detailed Article</a> -->

</div>

<div class="notice--info" markdown="1">

### Hierarchical Fuzzy Graph Coloring Algorithm
An innovative approach for detecting overlapping communities in complex networks, such as social networks where nodes can belong to multiple groups. HFGC begins by selecting influential "master" nodes as initial community seeds, assigning them unique labels, while other nodes start unlabeled. Through iterative label propagation, each node updates its community membership vector based on its neighbors, allowing for fuzzy and overlapping community assignments.

**Collaborators:** Mehdi Touil, Chaimae Jallouli
**Tags:** Mathematics, Graph Theory, Community Detection, Fuzzy Logic, Networks, Clustering

<a href="https://github.com/HamBa-m/HFGC" class="btn btn--inverse">View GitHub Repository</a>
<!-- <a href="#" class="btn btn--light-outline">Read Detailed Article</a> -->

</div>

<div class="notice--info" markdown="1">

### Flocking Birds Simulation
This Flocking Simulation repository implements the classic Boids algorithm to model and analyze collective bird-like behavior. It provides a framework where individual agents (boids) follow simple rules—separation, alignment, and cohesion—to produce realistic flocking dynamics. The system tracks key metrics such as polarization, angular variance, and kinetic energy.

**Collaborators:** Mehdi Touil
**Tags:** Mathematics, Multi-Agents, Swarm Intelligence, Simulation, 2D Animation

<a href="https://github.com/HamBa-m/adaptive-boids" class="btn btn--inverse">View GitHub Repository</a>
<!-- <a href="#" class="btn btn--light-outline">Read Detailed Article</a> -->

</div>

## GitHub Contributions
*Accepted pull requests in public repositories.*

<div class="notice--warning" markdown="1">

* **Time-LLM:** I added a try/except block to launch the model and tokenizer download if not already available locally. <a href="https://github.com/KimMeen/Time-LLM" class="btn btn--inverse btn--small">View GitHub Repository</a>
* **Microsoft Azure Documentation:** I helped fix a small issue in one of the first tutorials of Azure when using Intelligent OCR services. <a href="https://github.com/MicrosoftDocs/azure-docs/pull/121473" class="btn btn--inverse btn--small">View GitHub Repository</a>

</div>

## Other Projects
*Projects developed in volunteering context.*

<div class="notice--success" markdown="1">

### Grande Médiathèque Numérique EMPIMO
The EMPIMO Digital Library (GMN) is a collection of digital books created in August 2018 by the Moroccan Team for Preparing International Mathematical Olympiads (EMPIMO). All documents available in this library originate from the EMPIMO Facebook community; I have simply gathered and organized them.

**Tags:** Mathematics, Web Development, HTML, CSS, JavaScript, GitHub Webpages

<a href="https://empimo.github.io/library/" class="btn btn--light-outline">Visit Website</a>

</div>