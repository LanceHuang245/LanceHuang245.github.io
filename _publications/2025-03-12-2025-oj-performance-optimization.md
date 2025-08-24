---
title: "Research on Performance Optimization of Online Judging System Based on Golang and Docker Container Pooling"
collection: publications
category: manuscripts
permalink: /publication/2025-oj-performance-optimization
excerpt: 'This paper proposes an optimization strategy based on container pooling for Online Judging systems to address the significant startup delays and resource wastage associated with creating new containers for each submission. By pre-creating “hot containers” and resetting their environment after each task, this approach eliminates the need to restart a container for every submission, greatly improving resource utilization and system reliability.'
date: 2025-03-12
venue: 'Chinese Journal of Conputer Application(in press)'
slidesurl: ''
paperurl: ''
citation: 'Linxing Huang. (in press). &quot;Research on Performance Optimization of Online Judging System Based on Golang and Docker Container Pooling.&quot; <i>Chinese Journal of Conputer Application</i>, 2025(18).'
---

This paper presents an Online Judging System designed using a tech stack that includes Golang, Vue, Redis, Docker, among others. The system employs Docker containers to isolate and execute user-submitted code. In traditional online judging systems, high task concurrency is handled by a cold start approach—creating a new container for each submission—which results in significant startup delays and resource wastage, ultimately limiting throughput. For this reason, this paper proposes an optimization strategy based on container pooling. At system startup, a predefined number of “hot containers” are created so that, and replace Redis task queue with RabbitMQ, once a task is submitted, an existing container can immediately be used for judging. After the task is completed, an “environment reset” is triggered, eliminating the need to restart a container for every task and greatly improving overall resource utilization and reliability. Experimental results show that with container pooling, the system achieves marked improvements in both processing speed and resource efficiency. This paper also explores key technical challenges encountered during implementation and potential future directions, offering an effective optimization approach for deploying online judging systems in large-scale, high concurrency environments.