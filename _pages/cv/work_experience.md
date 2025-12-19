---
layout: single
title: "Work Experience"
permalink: /cv/work-experience/
author_profile: false
toc: true
toc_sticky: true
toc_label: "Jump to"
---

This page chronicles my professional journey through various roles in AI, research, and software engineering, highlighting key projects and contributions.

### AI Consultant

| | |
|:---|:---|
| **Company** | **[AY Automate](https://www.ayautomate.com)** |
| **Period** | Nov 2023 - Jun 2025 |
| **Location** | Remote |
| **Type** | Freelance |
| **General Scope** | Develop AI-based custom solutions for clients from different sectors. |
| **Project 1 (US)** | **LLM-Based Teacher Assistant:**<br>This project serves as a reference implementation for deploying a **Streamlit-based, LLM-powered chatbot** on **Microsoft Azure**. It demonstrates a robust containerization workflow, utilizing **Docker** for packaging, **Azure Container Registry (ACR)** for image management, and **Azure Web App** for hosting the conversational interface.<br><br>**Keywords:** Streamlit, Azure Web App, Docker, Azure Container Registry (ACR), MLOps, LLM Deployment, Python. |
| **Project 2 (Australia)** | **Sports Prediction:**<br>This project represents a comprehensive machine learning initiative designed to forecast outcomes across four major sporting disciplines: **NRL**, **AFL**, **NBA**, and **MMA**. Developed as a four-milestone evolution, the platform unifies distinct predictive engines under a single, high-performance **FastAPI** architecture to deliver real-time probabilities, score margins, and confidence intervals.<br><br> The development lifecycle proceeded through four distinct milestones: <br>- **Milestone 1 (NRL):** Established the foundational ETL (Extract, Transform, Load) pipeline and inference logic, enabling win probability and total score forecasting for National Rugby League matches.<br>- **Milestone 2 (AFL):** Scaled the architecture to accommodate the high-variance scoring patterns of Australian Rules Football, introducing automated model retraining capabilities.<br>- **Milestone 3 (NBA):** Enhanced predictive accuracy by integrating complex financial datasets (Team Salary data via HoopsHype) with game statistics, allowing for "Moneyball-style" analysis of team performance versus valuation.<br>- **Milestone 4 (MMA):** Adapted the predictive framework from team-based dynamics to individual combat sports, focusing on fighter-specific metrics and historical matchup analysis.<br><br>The final system offers a unified API endpoint for all sports, supporting batched predictions, automated data scraping, and "back-to-back" game detection, all deployable via **Docker**.<br><br>**Keywords:** Sports Analytics, NRL, AFL, NBA, MMA, FastAPI, Machine Learning, Time Series Forecasting, Data Engineering, ETL, Feature Engineering, Automated Retraining, Python. |
| **Project 3 (UK)** | **Sales Forecasting:**<br>This project conducts a comprehensive analysis and forecasting of retail product sales using multiple time-series methodologies. The workflow begins with a robust Exploratory Data Analysis (EDA) and Preprocessing Pipeline designed to clean 102,471 entries, handle missing values, and filter outliers across 781 unique product lines.<br><br> To address the challenges of data diversity and inconsistent frequencies, three distinct modeling approaches were evaluated:<br>- **SARIMAX:** Implemented to capture seasonality, though it showed limited effectiveness due to weak historical dependencies and high data noise.<br>- **LSTM (Long Short-Term Memory):** Demonstrated superior performance with a **Mean Absolute Error (MAE) of 0.11**.<br>- **TimeGPT:** Applied to a strict subset of 125 products that met specific criteria for frequency consistency (weekly) and historical depth (>1.5 years), leveraging foundation models for forecasting.<br><br>**Keywords:** Sales Forecasting, Time Series, LSTM, SARIMAX, TimeGPT, Retail Analytics, Deep Learning, Data Preprocessing. |

### AI Research Engineer

| | |
|:---|:---|
| **Lab** | **[Ai movement UM6P](https://aim.um6p.ma/en/home/)** |
| **Period** | Feb 2024 - Aug 2024 |
| **Location** | Rabat, Morocco |
| **Type** | Graduation Internship |
| **Mission** | **Deep-RL for Satellite Constellation:**<br>This thesis investigates the application of Multi-Agent Deep Reinforcement Learning (MADRL) for collaborative target acquisition and coverage optimization in satellite constellations. The study aims to enhance the operational efficiency of Earth observation satellites by leveraging advanced MADRL techniques. Conducted within the Ai Movement UM6P research center, this comprehensive study involves environment development, algorithm design, and performance evaluation.<br><br>Key components of this research include maintaining and upgrading the PyLEO environment for Agile Earth Observation Satellites (AEOS) simulation, modeling the problem as a Decentralized Markov Decision Process (Dec-MDP), and testing DQN and DDPG algorithms in single-agent scenarios with multiple state space representations and action spaces. Additionally, the study extends the padded DDPG to a basic multi-agent scenario with no communication, highlighting the challenges in applying MADRL to AEOS environments. The research also involved a thorough literature review on advancements in Deep Reinforcement Learning (DRL), as well as their applications in AEOS and the general field of Unmanned Aerial Vehicles (UAVs).<br><br>**Keywords** : Deep RL, Agile Earth Observation Satellites, Dec-POMDP, Multi Agent Systems, MADDPG |

### Research Assistant

| | |
|:---|:---|
| **Lab** | **[Ai movement UM6P](https://aim.um6p.ma/en/home/)** |
| **Period** | Jun 2023 - Oct 2023 |
| **Location** | Rabat, Morocco |
| **Type** | Academic Internship |
| **Mission** | **MARL for Nano-Satellites:**<br>Our project is aimed at developing a state-of-the-art multi-agent reinforcement learning (MARL) framework for optimizing the performance of distributed satellite systems in low Earth orbit. These systems are integral for various applications, from global communication to Earth observation. Our interdisciplinary approach merges computer engineering, deep reinforcement learning, and celestial mechanics to address the complex challenges faced by a swarm of nano-satellites.<br><br>The project focuses on the design, implementation, and testing of a decentralized partially observable Markov decision process (Dec-POMDP) model for multi-agent satellite networks. Each agent, representing a nano-satellite, collaborates with the team to execute tasks efficiently while coping with dynamic network topologies and resource limitations.<br><br>**Keywords**: Dec-POMDP, MARL, MA3C, DDPG, Deep RL, nano-satellites network, low earth orbit. |

### Data Scientist

| | |
|:---|:---|
| **Company** | **[Architeo](https://www.architeo.ma)** |
| **Period** | Sep 2022 - Oct 2022 |
| **Location** | Remote |
| **Type** | Academic Internship |
| **Mission** | **Smart Chatbot Development:**<br>Our project focuses on the design and development of an intelligent chatbot for Architeo, an IT consulting firm, submitted as part of the AI Summer Competition 2022. The system addresses specific business specifications, including answering common client queries, qualifying prospects, scheduling appointments based on company availability, and collecting user satisfaction scores.<br><br>The implementation adopts a Machine Learning Operations workflow to ensure reliable deployment and maintenance throughout the lifecycle. The technical architecture relies on the RASA framework, utilizing RASA NLU for intent classification and entity extraction, and RASA Core for dialogue management through defined stories and slots. This open source approach allows the agent to process natural language in French and English while managing dynamic data such as schedule states.<br><br>**Keywords**: NLP, Chatbot, RASA, MLOps, Intent Classification, Dialogue Management. |

### Software Engineer

| | |
|:---|:---|
| **Lab** | **[CNESTEN](https://www.cnesten.org.ma)** |
| **Period** | Jun 2022 - Aug 2022 |
| **Location** | Kenitra, Morocco |
| **Type** | Academic Internship |
| **Mission** | **Radiation Monitoring System:**<br>This project aimed to develop an IoT monitoring system for Radiation Portal Monitors (RPMs) at CENM Entrance. This system allows the remote supervision of the abnormal radioactive activities in the vehicles getting in the CENM or out of it and the control in real-time of the operating status of the detectors and their associated measurement chain. Furthermore, this system offers other functionalities of database exploration. <br><br> This is a multidisciplinary project of computer engineering ranging from full-stack development, networks, database administration, data pre-processing and visualization, to cybersecurity and IoT, all applied in the nuclear instrumentation sector. The developed system is composed of 3 sub-units: an acquisition unit to collect data, a gateway to format the data and transfer it, and an endpoint to interact with the data collected and the measurement chain parameters of the RPM detectors. <br><br> **Keywords**: Computer System, System Architecture, Real-Time Monitoring, Web Application, TCP/IP Protocol, Internet of Things, Micro-controller, Nuclear Instrumentation. |