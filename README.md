# Overview
This is a fork of lm-evaluation-harness with an implementation of GSM-MC, a multiple-choice variant of GSM8k.
The benchmark is implemented purely in yaml and can be found at lm-eval/tasks/gsm-mc.yaml

Validation was done using LLaMa3.1-8B and the model performed close to the one reported in the original paper.
|Tasks |Version|Filter|n-shot| Metric |   |Value |   |Stderr|
|------|-------|------|-----:|--------|---|-----:|---|-----:|
|gsm_mc|Yaml   |none  |     0|acc     |↑  |0.3321|±  | 0.013|


This was done as a final project for the AI Alignment Course by BlueDot Impact.
https://aisafetyfundamentals.com/


# Citation
The original paper of GSM-MC can be found here: https://arxiv.org/abs/2405.11966
Zhang, Z., Xu, L., Jiang, Z., Hao, H., & Wang, R. (2024). Multiple-choice questions are efficient and robust LLM evaluators. arXiv. https://arxiv.org/abs/2405.11966
