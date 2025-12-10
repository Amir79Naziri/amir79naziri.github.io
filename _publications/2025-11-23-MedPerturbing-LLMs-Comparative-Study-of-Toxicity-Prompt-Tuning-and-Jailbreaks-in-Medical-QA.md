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

Large Language Models (LLMs) are increasingly deployed in high-stakes environments, including healthcare, where safety, fairness, and robustness are essential. This work investigates the toxicity of commonly used general-purpose LLMs when applied to medical question answering. We examine three scenarios: (i) standard baseline querying, (ii) safety-oriented prompt guidelines designed to reduce harmful or biased outputs, and (iii) adversarial jailbreak prompts crafted to bypass model safeguards.

Using MedPerturb—a dataset containing medical questions systematically perturbed across gender, race, and age—we evaluate five LLMs ranging from 2B to 9B parameters across three established toxicity metrics. Our findings show that while prompt guidelines can meaningfully reduce toxic outputs and mitigate demographic biases, jailbreak prompts remain highly effective at circumventing safety mechanisms. All evaluated models display limited robustness to such adversarial attacks, underscoring a critical barrier to safe clinical deployment.

By answering three central questions—how much toxicity LLMs exhibit in standard medical scenarios, how effectively prompt tuning mitigates toxicity, and how vulnerable models are to jailbreaks—this study provides a structured assessment of the risks and limitations of LLM usage in healthcare. The results highlight the need for stronger safeguards and more resilient model-level protections to prevent harmful misuse and support safe real-world integration.