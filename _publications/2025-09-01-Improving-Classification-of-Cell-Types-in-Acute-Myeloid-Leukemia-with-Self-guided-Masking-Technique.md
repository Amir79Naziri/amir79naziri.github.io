---
title: "Improving Classification of Cell Types in Acute Myeloid Leukemia with Self-guided Masking Technique"
collection: publications
category: manuscripts
permalink: /publication/2025-Improving-Classification-of-Cell-Types-in-AML-with-Self-guided-Masking
excerpt: "This work presents a self-guided masking strategy to enhance cell-type classification in Acute Myeloid Leukemia (AML). By integrating masking techniques with modern machine learning models, the approach improves robustness and accuracy in distinguishing AML-related cell types."
date: 2025-09-01
venue: "NeurIPS 2025 Workshop on AI Virtual Cells and Instruments: A New Era in Drug Discovery and Development"
paperurl: "{{ site.baseurl }}/files/11_Improving_Classification_of.pdf"
---

Acute myeloid leukemia (AML) is a rare but important disease. Because it has many different features and behaviors, classifying its cell types with traditional methods is both difficult and costly. Transformer-based foundation models (FMs) are useful for analyzing biological data, and they usually use random masking during training. But normal uniform random masking selects genes without checking how important they are. To solve this, we propose a self-guided masking method. This method learns which gene positions are most useful to mask at each training step. We show that our approach improves FM training and performs better than uniform masking in cell-type classification for AML.
