---
title: “From Bias to Breakdown: Benchmarking Failure Mode Analysis of Single-cell RNA Sequencing Foundation Models in Acute Myeloid Leukemia”
collection: publications
category: manuscripts
permalink: /publication/2025-From-Bias-to-Breakdown
excerpt: “This work benchmarks single-cell RNA-seq foundation models on Acute Myeloid Leukemia, revealing significant performance drops in underrepresented disease conditions and motivating structured failure-mode analysis beyond overall accuracy.”
date: 2025-11-23
venue: “Proceedings of the AAAI Symposium Series, Vol. 7, Issue 1, pp. 553–557”
paperurl: “https://ojs.aaai.org/index.php/AAAI-SS/article/view/36931”
authors: “Amirreza Naziri, Arash Asgari, Aijun An, Eleftherios Sachlos, Laleh Seyyed-Kalantari”
---

Foundation models (FMs) trained on large-scale single-cell RNA-seq (scRNA‐seq) data have shown strong performance across various biological tasks. These performances are often reported across a large set of test benchmarks across all samples. However, the pretraining data of these models are often highly imbalanced across disease types, patients' conditions, and demographics. For instance, disease samples are rarer and more challenging to collect, and the pretraining sets contain many more healthy cells. Such imbalances can hurt performance on underrepresented disease cases and the equality of the model outcome. To evaluate this hypothesis, we benchmark off-the-shelf scRNA-seq foundation models for cell-type classification in acute myeloid leukemia (AML), a rare but clinically important disease that represents low-prevalence settings. Here, besides overall performance, we conduct subgroup analysis of the outcome across cell types and disease conditions (clinical timepoints). Our results suggest that despite high overall F1 scores in cell-type classification, performance drops in disease conditions and varies across cell types. These findings highlight a limitation of current scRNA-seq foundation models and motivate more balanced pretraining and failure mode analysis rather than an overall performance report.