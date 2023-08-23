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
* B.S. in Computer Science, University of California, Los Angeles (UCLA), 2025 (expected)
* 3.94 GPA
* Coursework: Data Structures and Algorithms, Computer Architecture, Software Construction, Algorithms and Complexity, Operating Systems, Neural Networks and Deep Learning, Linear Algebra (Honors), Formal Languages and Automata

Work experience
======
* Summer 2023: SWE / ML Ops Intern, AWS
  * Architected flexible ingestion workflow writing over 50000 records per week to a NoSQL database at 8 abstraction levels.
  * Wrote batch processing job for millions of records per day with AWS Glue and PySpark.
  * Followed test-driven development to deliver production-ready code, leveraging PyTest for unit testing and JUnit for integration testing, and proposing and implementing a comprehensive suite of alarms and metrics.

* Summer 2022: Data Automation Intern, II-VI
  * Rewrote SQL query generating summary data table for Epitaxial layer growth using incremental loading and indexing, improving query time by 10000%.
  * Upgrade 2 legacy data collection user interfaces from asp.net to Flask-React tech stack, saving 2 hours per week and reducing IT team burden.
  * Proposed merging auto-generated experimental data into a single source on AWS cloud data platform, allowing for efficient data retrieval and reducing SQL server burden by 10%.

* Feb 2022 - Sep 2022: Lead Developer, Walk
  * Linked frontend pages to backend API endpoints using React Native, Django, and mySQL.
  * Assembled walk summary page and UI using React Native and CSS.
  * Won 2nd place out of 12 teams in startup accelerator competition.
  
Research
======
* Apr 2023 - Present: UCLA PlusLab
  * Extend epidemic event extraction to low-resource multilingual settings.
  * Create curated multilingual datasets for target languages through manual annotation and MTurk crowdsourcing.
* May 2022 - Present: Quantum Ethics Project
  * Assess the trainability of Variational Quantum Algorithms and rank these algorithms by immediate social impact and compatibility with
intermediate scale noisy devices.
  * Collaborate with international group of researchers to anticipate bad uses to advise regulatory frameworks and minimize potential harm.
* Feb 2020 - Jul 2020: Pioneer Academics
  * Synthesized a 31-page thesis about public reaction to COVID-19 lockdowns on Twitter with UC Berkeley’s Professor Eric Friedman
(ejf@icsi.berkeley.edu).
  * Programmed in Jupyter Notebook to scrape Twitter data, using Python package NodeX to process over 500,000 Tweets.
  * Analyzed user reactions and interactions with sentiment analysis and network analysis, concluding a 200% increase in negative reaction to
lockdowns, and isolation of strongly opinionated communities.

Organizations
======
* Sep 2021 - Present: Projects Officer, UCLA ACM AI
  * Applied data augmentation, regularization, and transfer learning to classify Cassava leaves, improving training accuracy to 85%.
  * Collaborate with team of 5 officers to construct new projects track, classifying Quora insincere questions using contextual embeddings,recurrent neural architectures, and transformer-based models such as GPT-2 and BERT, achieving top recall of 88%.
* Jan 2022 - Jun 2022: Game Developer, UCLA ACM Studio
  * Develop in team of 12 for student-led top down adventure-style video game "Wisp".
  * Build game interface and symbol recognition system in C# and Unity.
  * Use reinforcement learning to develop 4 Hero Artificial Intelligence models.

Skills
======
* Languages: Python, C++, Javascript, Java, Bash
* Technologies/Frameworks: Pytorch, Tensorflow, Qiskit, Pennylane, Express JS, Flask, Git, Microsoft SQL Server, AWS Cloud tools

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
