---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

**Julian Sidik**  
[github.com/jsidik](https://github.com/jsidik) | [julianksidik@gmail.com](mailto:julianksidik@gmail.com) | [jsidik@gatech.edu](mailto:jsidik@gatech.edu)  
Mobile 650 898 3993 | U.S. Permanent Resident | Sunnyvale, CA

Education
======
**Georgia Institute of Technology** — Atlanta, GA  
*Master of Science in Computer Science* — Dec 2026  
• Relevant Courses: Health Informatics, Artificial Intelligence, Software Development

**University of California, Davis** — Davis, CA  
*Bachelor of Science in Computer Science & Engineering* — Jun 2025  
• Relevant Courses: ECS 171 – Machine Learning, EEC 172 – Embedded Systems, Data Structures & Algorithms, Computer Architecture, Software Engineering, Operating Systems, Computer Networks

Experience
======
**Software Engineer Intern** — May 2025 – Sep 2025  
*PT Telindo Nusantara* — Jakarta, Indonesia  
• Developed and deployed backend services supporting TN-CLOUD cloud-based telephony platform, implementing SIP call event logging, user provisioning APIs, and call detail record (CDR) processing pipelines for enterprise clients  
• Built internal provisioning dashboard (React + Node.js) to automate IP-PBX configuration and user onboarding workflows, reducing manual configuration time per client deployment and improving deployment turnaround across 5+ enterprise accounts

**Undergraduate Student Researcher** — Mar 2025 – Jun 2025  
*Visualization and Interface Design Innovation Lab, UC Davis* — Davis, CA  
• Architected and implemented Graph Neural Network (GNN) system processing 10K+ node heterogeneous graphs from EHR datasets, improving cancer patient survival prediction accuracy using attention-based embeddings  
• Built interpretability framework using graphlet frequency analysis to explain model predictions on Cancer Genome Atlas (TCGA) datasets, enabling clinicians to understand feature importance

**Computer Science Tutor** — Jan 2024 – Jun 2025  
*Department of Computer Science, UC Davis* — Davis, CA  
• Delivered technical instruction to 50+ students on advanced algorithms (graph traversal, dynamic programming, divide-and-conquer) and data structures (BSTs, hash tables, heaps)

Projects
======
**(ECS 193 Senior Design Project) AI-Powered Surgical Instrument Counting System** — *PyTorch, Swift, REST APIs*  
• Engineered end-to-end ML system detecting 30+ surgical instrument types, processing 600+ instruments/hour to eliminate counting errors in OR workflows  
• Built scalable RESTful API backend with PostgreSQL, implementing caching layer to serve 500+ concurrent users at &lt;100ms latency for real-time inference  
• Developed and published iOS and Android app with CoreML model compression, enabling offline prediction and auto-syncing discrepancy alerts to hospital inventory systems

**Multi-Modal LLM Benchmarking Framework** — *InstructBLIP, CLIP, Transformers*  
• Fine-tuned 4 vision-language models (InstructBLIP variants, CLIP, custom ResNet-LSTM) on MS-COCO dataset, achieving state-of-the-art 145.8 CIDEr score with improved inference speed  
• Implemented comparative evaluation pipeline using SPICE, CIDEr, BLEU, and METEOR metrics across 10K+ image-caption pairs, identifying optimal model for medical image description tasks

Technical Skills
======
* **Programming Languages:** Python, Java, C++, C#, JavaScript/TypeScript, HTML/CSS, SQL  
* **Frameworks & Libraries:** PyTorch, TensorFlow, ReactJS, Angular, .NET Core, Django, Spring Boot, Express.js  
* **Tools & Technologies:** Git/GitHub, Docker, Unix/Linux, MongoDB, PostgreSQL, Redis, Jenkins, CI/CD, Jira, Figma  
* **Cloud & AI/ML:** AWS (EC2, RDS, Lambda, S3, DynamoDB, CloudFormation), CUDA, Computer Vision  
* **Languages:** English (Fluent), Indonesian (Fluent), Chinese (Conversational)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
