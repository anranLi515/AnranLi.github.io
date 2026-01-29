---
layout: archive
title: "Research Interests"
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---

My research interests focus on trustworthy AI, medical large language models, federated learning and graph learning. I have been working on the following topics: 
* **Memorization, Privacy, and Safety of Medical LLMs**: We focus on investigating memorization of LLMs in medicine, assessing its prevalence (how frequently it occurs), characteristics (what is memorized), volume (how much content is memorized), and potential downstream impacts (how memorization may affect medical applications). We systematically analyze common adaptation scenarios: (1) continued pretraining on medical corpora, (2) fine-tuning on standard medical benchmarks, and (3) fine-tuning on real-world clinical data, including over 13,000 unique inpatient records from Yale New Haven Health System.
* **Federated and Parameter-Efficient Framework for Large Language Model Training in Medicine**: We present a model model-agnostic, parameter-efficient federated learning framework for training LLMs in medicine. The framework dramatically reduces communication and computation overhead by transmitting only low-rank adapter parameters, and improves convergence under real-world cross-institutional heterogeneity by using the data-aware aggregation mechanism. We demonstrate its effectiveness through a downstream case study in clinical information extraction (IE). Evaluations covered three complementary settings: (1) in-domain training and testing, (2) external validation on independent patient cohorts, and (3) a new-site adaptation case study using real-world clinical notes from the Yale New Haven Health System. 
* **Data Selection for Federated Learning**: We aim to select a collection of high-quality training samples for a given FL task under a monetary budget in a privacy-preserving way. We provide a systematic analysis of important data related factors affecting the model performance and propose a holistic design to privately and efficiently select high-quality data samples considering all these factors. 
* **Task-oriented data quality assessment**: We propose a task-oriented data quality assessment framework, which balances between the intrinsic and contextual quality. We craft the assessment metrics, quantify them, and fuse them to rank candidate datasets by quality given specific tasks. We have implemented a quality assessment platform that supports multimodal data, e.g., image, text, tabular and audio. 
