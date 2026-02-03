---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **M.S. in Computer Science and Engineering** (GPA: 4.11/4.3)
  * National Yang Ming Chiao Tung University, Taiwan
  * July 2021 – November 2023

Work Experience
======
* **Software Engineer** - Synology Inc., New Taipei, Taiwan (May 2024 – Present)
  * Led **AI Advisor** project, a Synology chatbot serving 50k global users per month. The project was explicitly commended by the CEO to executive leadership for delivering exceptional accuracy and user experience.
    * Built an evaluation pipeline for response quality and improved over 50%+ via iterative tuning.
    * Cut non-API latency by 30% through multiprocess, gRPC/REST connection control and caching.
    * Developed NAS/NVR AI agents integrated with internal databases for real-time product recommendation.
    * Collaborated cross-functionally with Marketing, Design, and MIS teams to align technical deliverables.
  * Led **Synology InSyde**, an unreleased Synology DSM AI Agent enabling multi-step task automation and intelligent Drive operations through tool-based reasoning with finite-state control.
  * Contributed to **Auto-Invoice Recognition** system, designing the core recognition workflow and evaluation pipeline, achieving 90%+ parsing accuracy on e-receipts and cash invoices.

* **Research Assistant** - Institute of Information Science, Academia Sinica, Taipei, Taiwan (November 2023 – May 2024)
  * Led a structured paper survey on CNN-Transformer hybrids; distilled design patterns and integrated Transformer blocks into CNN policy/value nets for board-game RL.
  * Implemented training/evaluation utilities on an AlphaZero pipeline (self-play, MCTS, checkpointing, metrics) and authored internal benchmarks that later informed publication-grade experiments.

Skills
======
* **Languages:** Python, C++, Go
* **Infrastructure:** Linux, Docker, Kubernetes, Database management (MongoDB, PostgreSQL)
* **System Design:** RESTful APIs, gRPC, Protocol Buffers; Caching; Microservice integration
* **ML / AI:** PyTorch; Transformers (ViT), CNNs; RL (AlphaZero/MCTS, PPO, DQN); Model training & evaluation
* **Expertise:** AI System Design, Reliability/fault tolerance, Performance Optimization, Reinforcement Learning
* **Soft Skills:** Cross-team collaboration, Technical Leadership, Clear Communication

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Awards
======
* **2025 iThome Ironman 30 Technical Writing Challenge** - Honorable Mention Award (October 2025)
  * Agent-Brain: Designing an LLM Agent Workflow from Scratch
  * Built a modular LLM agent system from scratch, implementing finite-state reasoning stage with tools integration
