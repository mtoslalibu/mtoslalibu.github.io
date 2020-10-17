---
title: "An automated, cross-layer instrumentation framework for diagnosing performance problems in distributed applications"
collection: publications
permalink: /publication/pythia
excerpt: 'An automated instrumentation framework, Pythia, that runs alongside deployed distributed applications. In response to a newly-observed performance problem, Pythia searches the space of possible instrumentation choices to enable the instrumentation needed to help diagnose it'
date: 2019-10-01
venue: 'Proceedings of the ACM Symposium on Cloud Computing (SoCC 20)'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3357223.3362704'
citation: ''
---
**Abstract:**
Diagnosing performance problems in distributed applications is extremely challenging. A significant reason is that it is hard to know where to place instrumentation a priori to help diagnose problems that may occur in the future. We present the vision of an automated instrumentation framework, Pythia, that runs alongside deployed distributed applications. In response to a newly-observed performance problem, Pythia searches the space of possible instrumentation choices to enable the instrumentation needed to help diagnose it. Our vision for Pythia builds on workflow-centric tracing, which records the order and timing of how requests are processed within and among a distributed application's nodes (i.e., records their workflows). It uses the key insight that localizing the sources high performance variation within the workflows of requests that are expected to perform similarly gives insight into where additional instrumentation is needed.

 
