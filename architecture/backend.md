---
title: Backend
has_children: false
parent: Architecture
nav_order: 2
---

# Backend

Our backend runs within a Docker container containing Python 3.8 and openJDK.

* Extract text from files (PDF etc..): Apache Tika
* Text Preprocessing: ...
* Auto-Summarization: Sumy/ NLTK
* Named entitiy detection: Azure Text Analytics for Health
* Trust Score: Bing Trust score
* Medical dictionary: Merriam-Webster Medical dictionary v3




Note: As the Apache Tika server will started "on-demand" (e.g. first incoming request), you can get quite a long cold-start delay.
We're working on it.
 


# Run it yourself
1. Form the repo into your account or org
2. Setup for local testing
3. Run tests
4. Setup for deployment
5. Deployment to Azure
