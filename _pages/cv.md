---
layout: archive
title: "Curriculum Vitae"
permalink: /
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Research Interests
======
My research interests center on machine learning and its practical applications, with a particular focus on the systems infrastructure that supports efficient model development and deployment. I am broadly interested in distributed systems, high-performance computing, and the intersection of compiler design with modern ML frameworks and execution runtimes.

Education
======
**Bachelor of Engineering, Computer Application Engineering**  
Quanzhou Vocational and Technical University, Quanzhou, Fujian, China  
September 2022 – June 2026 | GPA: 80.92/100

Technical Projects
======

**Feas Online Judge** *(May 2024 – Present)*  
*Independent Developer*

A production-grade online judge system for competitive programming, implemented as a Go-based microservices architecture with an emphasis on high concurrency and automated content moderation.

- Designed a Docker container pooling strategy that increased concurrent code
  evaluation capacity by 500%
- Engineered an asynchronous judging pipeline via RabbitMQ, achieving a
  four-fold improvement in system throughput and a substantial reduction in
  queue latency
- Developed and deployed two domain-specific ML models—*ImageGuard* (image
  moderation) and *ProfanityDetector* (text filtering)—reducing content policy
  violations by approximately 85%
- Implemented a real-time user platform in Vue.js with live submission tracking
  via Server-Sent Events (SSE) and integrated community forums
- Supports evaluation of solutions in Java, C++, Python, Pascal, Rust, and PHP

**Zephyr** *(June 2023 – Present)*  
*Independent Developer*

A cross-platform weather application for iOS and Android, developed with
Flutter and a Golang backend service.

- Implemented Redis-based data caching to ensure low-latency access to global
  weather data
- Designed custom Android home-screen widgets for ambient real-time weather
  display

<p style="text-align: center;">
  <a href="https://github.com/LanceHuang245" target="_blank" rel="noopener noreferrer" class="btn">View More Projects on GitHub</a>
</p>

Professional Experience
======

**Software Engineer Intern**  
Xiamen Xunlian Information Technology Co., Ltd. (Bitdinosaur Technology Co., Ltd.), Xiamen, Fujian  
September 2025 – March 2026

- Engineered a proactive risk-monitoring module in Go, leveraging PostgreSQL
  views to automatically detect and flag anomalous account and IP behaviors
- Refactored user data access layers, reducing API response latency from
  approximately 1,700 ms to under 180 ms (>99% reduction)
- Designed and implemented a backend analytics dashboard API providing
  real-time operational data for internal management and on-chain address risk
  assessment
- Re-architected notification push, IAM, and subscription systems under a
  microservices paradigm, improving scalability, maintainability, and feature
  extensibility

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Honors & Awards
======
- Third Prize, Huawei ICT Competition, Programming Track, Fujian Province (2025)
- Third Prize, Huawei ICT Competition, Linux Track, Fujian Province (2023)
- Second Prize, Program Algorithm Design Competition, Quanzhou Vocational and
  Technical University (2022)

Technical Skills
======
**Programming Languages**  
Proficient: Go, Dart, Python  
Familiar: JavaScript, C++

**Frameworks & Libraries**  
Backend: Flask, RabbitMQ, Consul, Redis, MySQL, PostgreSQL  
Frontend & Mobile: Vue.js, React, Flutter  
Machine Learning: PyTorch, TensorFlow, Hugging Face Transformers

**Systems & Infrastructure**  
Docker, Linux server administration, Nginx, Git-based CI/CD pipelines