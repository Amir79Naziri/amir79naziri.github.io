---
title: "From Bias to Breakdown: Benchmarking Failure Mode Analysis of Single-cell RNA Sequencing Foundation Models in Acute Myeloid Leukemia"
collection: publications
category: manuscripts
permalink: /publication/2025-From-Bias-to-Breakdown
excerpt: “This work benchmarks single-cell RNA-seq foundation models on Acute Myeloid Leukemia, revealing significant performance drops in underrepresented disease conditions and motivating structured failure-mode analysis beyond overall accuracy.”
date: 2025-11-23
venue: “Proceedings of the AAAI Symposium Series, Vol. 7, Issue 1, pp. 553–557”
paperurl: “https://ojs.aaai.org/index.php/AAAI-SS/article/view/36931”
authors: “Amirreza Naziri, Arash Asgari, Aijun An, Eleftherios Sachlos, Laleh Seyyed-Kalantari”
---

Foundation models trained on large-scale single-cell RNA sequencing (scRNA-seq) data have demonstrated impressive performance across diverse biological tasks. However, the datasets used for pretraining tend to be highly imbalanced across disease states, patient conditions, and demographic groups. In particular, disease samples—such as those from Acute Myeloid Leukemia (AML)—are much less common than healthy samples, creating a structural imbalance that may undermine real-world reliability.

To investigate this challenge, we benchmark several off-the-shelf scRNA-seq foundation models for cell-type classification in AML, a rare yet clinically critical disease. In addition to assessing overall performance, we perform detailed subgroup analyses across cell types and disease conditions, including distinct clinical timepoints.

Our findings reveal that although the models achieve strong overall F1 scores, their performance drops substantially in disease conditions and varies meaningfully across specific cell types. These results point to a key limitation in current scRNA-seq foundation models: high average accuracy masks important failure modes affecting underrepresented biological settings. This work highlights the need for more balanced pretraining strategies and thorough failure-mode evaluations to ensure equitable and reliable model performance in clinical research.