---
title: “MedPerturbing LLMs: A Comparative Study of Toxicity, Prompt Tuning, and Jailbreaks in Medical QA”
collection: publications
category: manuscripts
permalink: /publication/
excerpt: “This study evaluates toxicity in large language models applied to medical question answering. It compares baseline behavior, guideline-based prompt mitigation, and adversarial jailbreak prompting using the MedPerturb dataset, revealing significant vulnerabilities in current LLM safety mechanisms.”
date: 2025-11-23
venue: “Proceedings of the AAAI Symposium Series, Vol. 7, Issue 1, pp. 438–447”
paperurl: “https://ojs.aaai.org/index.php/AAAI-SS/article/view/36916”
authors: “Arash Asgari, Amirreza Naziri, Laleh Seyyed-Kalantari”
---

Large Language Models (LLMs) are increasingly adopted across domains, including sensitive areas such as healthcare. However, their deployment raises significant safety concerns, particularly with respect to toxicity. In this paper, we evaluate the toxicity of widely used general-purpose LLMs in medical question–answering tasks. We investigate three complementary scenarios: (i) baseline querying, (ii) prompt guidelines designed to mitigate toxic outputs, and (iii) adversarial jailbreak prompting intended to elicit harmful content. To measure toxicity, we apply three established metrics to five LLMs ranging from 2B to 9B parameters, using MedPerturb, a dataset of medical questions systematically perturbed across gender, race, and age. Our results show that while carefully crafted guidelines can reduce toxic outputs and mitigate demographic biases, adversarial instructions are highly effective at bypassing safety mechanisms. Our evaluation reveals that all models exhibit limited resilience to jailbreak attacks, highlighting a critical vulnerability that restricts their safe deployment in clinical contexts. By answering three key questions—(1) what levels of toxicity these models exhibit in standard medical scenarios, (2) how far prompt tuning can reduce toxicity, and (3) how vulnerable they are to jailbreaks, our study provides a structured assessment of the risks and limitations of LLMs in healthcare, and shows the importance of establishing robust guidelines and protections to promote the safe deployment of LLMs in healthcare and to guard against harmful misuse.