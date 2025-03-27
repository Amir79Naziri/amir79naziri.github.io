---
title: "Exploring Visual Prompt Tuning for Demographic Adaptation in Foundation Models for Medical Imaging"
collection: publications
category: manuscripts
permalink: /publication/2024-10-10-Exploring-Visual-Prompt-Tuning-for-Demographic-Adaptation-in-Foundation-Models-for-Medical-Imaging
excerpt: 'Visual Prompt Tuning (VPT) enables efficient adaptation of large medical foundation models with minimal resources. Compared to linear probing and full fine-tuning, VPT performs better on imbalanced demographic data, achieving results close to full fine-tuning, especially for underrepresented groups. It offers a resource-efficient alternative when data and computing power are limited.'
date: 2024-10-10
venue: 'Adaptive Foundation Models: Evolving AI for Personalized and Efficient Learning'
# slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://openreview.net/forum?id=L2hKYZVIWE'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

Pre-trained medical foundation models are large, and they require significant computational resources for training. Visual Prompt Tuning (VPT) allows foundation models to efficiently adapt to new tasks with minimal changes to the model's architecture, reducing the need for extensive fine-tuning. Here, we explore demographic (race) adaptation of foundation models (MAE and MoCoV3) for disease classification in medical imaging using naturally imbalanced data. We compare three adaptation strategies: linear probing, full fine-tuning, and VPT. We find that VPT obtains a clear boost in performance, starting with prompt length 5 over linear probing. In the case of race demographics (e.g. Asian with 5.7\% of the full dataset), a VPT model trained on a demographic (Asian) performed similarly to a fully fine-tuned model trained on same dateset. A fully fine-tuned foundation model on a diverse and large dataset performs better than a model adapted only for a specific subset of data. However, it needs large data and computing resources, which may not always be available. These findings show that VPT can efficiently adapt foundation models for small datasets, achieving performance comparable to full fine-tuning.